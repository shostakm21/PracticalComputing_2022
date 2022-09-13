#Cape Shores Analyses
##HMM Small list (oxygen, nitrate reductases)

1. Make HMM directory with ones of interest
2. 

|Test|Analysis|
|---|----|
|s4|d3t|
|der|sum|


```
srun -N 1 -c 2 --mem=100000 --partition=batch --pty bash

```
Then when it assigns you a node you run your script

```
python3 hmm-metabolism.py -hmm_dir metabolic-hmms-banfield-ag-small -bin_dir /work/mcallis_FIELD/F1Y/prodigal -bin_ext faa -out F1Y_small -m hmm-meta.txt
```
If running a batch file you can do something like this...

```
#!/bin/bash
#SBATCH --job-name=HMM
#SBATCH --ntasks=1
#SBATCH --mem=100000

python3 hmm-metabolism.py -hmm_dir metabolic-hmms-banfield-ag-small -bin_dir /work/mcallis_FIELD/F1Y/prodigal -bin_ext faa -out F1Y_small -m hmm-meta.txt
```

##HMM H2W Small List

Run by Sean, output in /work/field_test_SMM/hmm_test/F1Y_small.csv

##HMM All contigs Processing

First I copied all prodigal output .faa files in one folder /work/field/hmm_test/prodigal. We are using all prodigal results for all samples (D2W, F1W, F1Y, H2W, CF2) using the complete assembly from spades (no subassembly).

Then I need to run all metabolisms against all HMM datasets for complete metabolisms

```
srun -N 1 -c 2 --mem=100000 --partition=batch --pty bash
```
Run HMMall.sh which has the following below

```
python3 /work/field/hmm_test/HMM-programV.2/hmm-metabolisms.py -hmm_dir /work/field/hmm_test/HMM-programV.2/metabolic-hmms-banfield-ag -bin_dir /work/field/hmm_test/prodigal -bin_ext faa -out HMM_all -m /work/field/hmm_test/HMM-programV.2/hmm-meta.txt
```

This failed due to loss of internet connection. Removed the .csv file that was made and all temporary files in the directory bin (folders that weren't there before). Then ran as a bash file (sbatch HMMmetabolismALL.sh)

##HMM H2W Bins Looking for Cyc2
Run HMM for H2W bins using only the cyc2 HMM models. Copied over the cluster 1, 2, and 3 hmms into a new folder /work/field/hmm_test/HMM-programV.2/metabolic-hmms-cyc2. Then copied over all ORFS from H2W DAS Tool bin (/work/mcallis_FIELD/H2W/H2W_binning/DASTool/ORFS/) using cp *.faa to copy over all of the .faa files into an ORFS folder in the hmm_test directory /work/field/hmm_test/H2W_ORFS.

```
srun -N 1 -c 2 --mem=50000 --partition=batch --pty bash
```
When assigned a node...

```
python3 /work/field/hmm_test/HMM-programV.2/hmm-metabolisms.py -hmm_dir /work/field/hmm_test/HMM-programV.2/metabolic-hmms-cyc2 -bin_dir /work/field/hmm_test/H2W_ORFS -bin_ext faa -out H2W_cyc2 -m /work/field/hmm_test/HMM-programV.2/hmm-meta.txt
```
Note output error message that it could not remove directory. This meant that it made a folder in the directory with the ORFS which I need to remove myself. From the hmm_test folder run rm -r *-HMM to remove all of these folders (which are empty). Not sure why this error is happening, could be a read/write permissions issue.



##HMM H2W Bins Looking for all HMMs
Run HMM for H2W bins using all HMM models. Using the renamed ORFS from H2W.

```
sbatch HMMmetabolismH2Wall.sh

```

This script contains the following:
```
python3 /work/field/hmm_test/HMM-programV.2/hmm-metabolisms.py -hmm_dir /work/field/hmm_test/HMM-programV.2/metabolic-hmms-banfield-ag -bin_dir /work/field/hmm_test/ORFs_renamed -bin_ext faa -out H2W_ORFs_all -m /work/field/hmm_test/HMM-programV.2/hmm-meta.txt
```

Note output error message that it could not remove directory. This meant that it made a folder in the directory with the ORFS which I need to remove myself. From the hmm_test folder run rm -r *-HMM to remove all of these folders (which are empty). Not sure why this error is happening, could be a read/write permissions issue.


##HMM F1Y Bins Looking for Cyc2
Run HMM for F1Y bins using only the cyc2 HMM models. Copied over the cluster 1, 2, and 3 hmms into a new folder /work/field/hmm_test/HMM-programV.2/metabolic-hmms-cyc2. Then copied over all ORFS from F1Y DAS Tool bin (/work/mcallis_FIELD/F1Y/F1Y_binning/DASTool/ORFs_renamed/) using cp *.faa to copy over all of the .faa files into an ORFS folder in the hmm_test directory /work/field/hmm_test/F1Y/ORFs_renamed.

```
srun -N 1 -c 2 --mem=50000 --partition=batch --pty bash
```
When assigned a node...

```
python3 /work/field/hmm_test/HMM-programV.2/hmm-metabolisms.py -hmm_dir /work/field/hmm_test/HMM-programV.2/metabolic-hmms-cyc2 -bin_dir /work/field/hmm_test/F1Y/ORFs_renamed -bin_ext faa -out F1Y_cyc2 -m /work/field/hmm_test/HMM-programV.2/hmm-meta.txt
```


##HMM F1Y Bins Looking for all HMMs
Run HMM for F1Y bins using all HMM models. Using the renamed ORFS from F1Y.

```
sbatch HMMmetabolismHF1Yall.sh

```

This script contains the following:
```
python3 /work/field/hmm_test/HMM-programV.2/hmm-metabolisms.py -hmm_dir /work/field/hmm_test/HMM-programV.2/metabolic-hmms-banfield-ag -bin_dir /work/field/hmm_test/F1Y/ORFs_renamed -bin_ext faa -out F1Y_ORFs_all -m /work/field/hmm_test/HMM-programV.2/hmm-meta.txt
```

Note output error message that it could not remove directory. This meant that it made a folder in the directory with the ORFS which I need to remove myself. From the hmm_test folder run rm -r *-HMM to remove all of these folders (which are empty). Not sure why this error is happening, could be a read/write permissions issue.



#Running the proces from start to finish using SEan's scripts, but on my account
Using H2W_S10 subassembly to test all of this out. Note that a lot of paths had to be added to my bash file to make things work.

##Step 1 QC Assembled Contigs
contig_qc_generic


##Step 2: Binning QC'd Contigs
```
/home/mcallis/scripts/FIELD_binning/01_binning_programs.sh H2W_S1_contigqc/H2W_S1_simpname_qccontigs_final.fasta H2W_S1_contigqc/H2W_S1_v_postqcDB_sorted.bam H2W_S1_contigqc/H2W_S1_v_postqcDB_sorted.bam.bai H2W_S1_1.fq.gz H2W_S1_2.fq.gz H2W_S1_fake_unpaired.fq.gz H2W_S1 250
```



#Random commands to keep track of:
-MAC switching between programs Command+Tab
-cp -r for folders (rf if there is anything executable like scripts)
-Nano NAME.sh (Control+K will delete a line, command V will paste the script you want to use), then Control X, rename it, yes, enter.
-squeue -u efield (to check my jobs)
