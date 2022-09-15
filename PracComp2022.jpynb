{
  "nbformat": 4,
  "nbformat_minor": 0,
  "metadata": {
    "colab": {
      "provenance": [],
      "toc_visible": true,
      "mount_file_id": "https://github.com/shostakm21/PracticalComputing_2022/blob/master/PracComp2022.ipynb",
      "authorship_tag": "ABX9TyMhJGs3soWv0H4xCGAZA/JI",
      "include_colab_link": true
    },
    "kernelspec": {
      "name": "python3",
      "display_name": "Python 3"
    },
    "language_info": {
      "name": "python"
    }
  },
  "cells": [
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "view-in-github",
        "colab_type": "text"
      },
      "source": [
        "<a href=\"https://colab.research.google.com/github/shostakm21/PracticalComputing_2022/blob/master/PracComp2022.ipynb\" target=\"_parent\"><img src=\"https://colab.research.google.com/assets/colab-badge.svg\" alt=\"Open In Colab\"/></a>"
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "# Basics\n"
      ],
      "metadata": {
        "id": "cv-WaLHX7gVd"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "## Markdown Cont'd"
      ],
      "metadata": {
        "id": "b05_Vq8W73-8"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "* Uses asterices to create bullet points (unordered) lists\n",
        "\n",
        "1. Use numbers to create ordered lists\n",
        "\n",
        "*Top level\n",
        "  * Indent 1\n",
        "    * Indent 1a\n",
        "\n",
        "Line \n",
        "breaks \n",
        "dont \n",
        "matter\n",
        "But _blank lines_ create new paragraphs\n",
        "\n",
        "[Field Lab](http://www.efieldlab.com)"
      ],
      "metadata": {
        "id": "JBUHEh3-8A_f"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "## Python Basics"
      ],
      "metadata": {
        "id": "VAK_uZTg88io"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "## Putting a hash mark in front of a command will turn it off (not run it)"
      ],
      "metadata": {
        "id": "HgRffZBN-8He"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "## Variables\n",
        "\n",
        "First you must declare you variable."
      ],
      "metadata": {
        "id": "mffWb6948-7F"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "myage = 25\n",
        "given_name = \"Maggie\"\n",
        "family_name = \"Shostak\""
      ],
      "metadata": {
        "id": "-BSeGq-C9Bjg"
      },
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "print(given_name, \"is\", myage, \"years old\")"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "XX3f4Mj592Pf",
        "outputId": "88ef8f2d-455a-460b-a981-81dedb9da56e"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Maggie is 25 years old\n"
          ]
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "## Objects: Strings vs Integers"
      ],
      "metadata": {
        "id": "zt7DS2baAEQQ"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "#type(myage)\n",
        "#type(given_name)\n",
        "\n",
        "print(type(myage), type(given_name))"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "uur5LPeq-e2F",
        "outputId": "2cc57b40-3d73-4db0-b913-fc46e68dad73"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "<class 'int'> <class 'str'>\n"
          ]
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "We can change the type of the variable by defining it as such"
      ],
      "metadata": {
        "id": "f7dZpSBJ_G-i"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "myage_str = str(myage)\n",
        "\n",
        "type(myage_str)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "PSj6GTdR_JCF",
        "outputId": "cf69ad20-2cef-4918-ab16-1228e8673e17"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "str"
            ]
          },
          "metadata": {},
          "execution_count": 10
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "print(myage + 1)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "v-04hLD__YFd",
        "outputId": "6e7f3dcb-4e0d-4f53-82a1-92cde043990d"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "26\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "print(myage + myage)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "2w_y1UUq_dSq",
        "outputId": "e0840098-8cb8-4c9a-c5f4-dc644a5d57f4"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "50\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "print(myage_str + myage_str)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "o-dxPeGF_zkB",
        "outputId": "0837a16d-a3a2-453a-fd38-a762225dcdad"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "2525\n"
          ]
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "## You can index you strings in python.\n",
        "\n",
        "**_Python starts counting at zero!_**"
      ],
      "metadata": {
        "id": "rAcfT3CM_8tH"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "given_name[1]"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 37
        },
        "id": "yIAL1qTx_7_J",
        "outputId": "c683c73e-821d-4f34-b800-c222d29677fd"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "'a'"
            ],
            "application/vnd.google.colaboratory.intrinsic+json": {
              "type": "string"
            }
          },
          "metadata": {},
          "execution_count": 15
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "given_name[0]"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 37
        },
        "id": "Td9X7IcAAY1Y",
        "outputId": "eb45385c-e57c-4d12-bdc8-7eec3ea103d0"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "'M'"
            ],
            "application/vnd.google.colaboratory.intrinsic+json": {
              "type": "string"
            }
          },
          "metadata": {},
          "execution_count": 16
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "given_name[2:4]"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 37
        },
        "id": "0KI97KCiAbyb",
        "outputId": "6776f1b0-c387-47c4-d1be-9f3e54563050"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "'gg'"
            ],
            "application/vnd.google.colaboratory.intrinsic+json": {
              "type": "string"
            }
          },
          "metadata": {},
          "execution_count": 17
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "given_name[0:5]"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 37
        },
        "id": "0WhNwNGfAf24",
        "outputId": "818f178b-a05d-4113-afd1-1b349af26710"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "'Maggi'"
            ],
            "application/vnd.google.colaboratory.intrinsic+json": {
              "type": "string"
            }
          },
          "metadata": {},
          "execution_count": 18
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "given_name[1:]"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 37
        },
        "id": "0gSJtesJAwjT",
        "outputId": "b1e8be24-59f4-4e2b-f0eb-983b9f2d782c"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "'aggie'"
            ],
            "application/vnd.google.colaboratory.intrinsic+json": {
              "type": "string"
            }
          },
          "metadata": {},
          "execution_count": 19
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "### How to determine length of string **_(it does not start counting at zero)_**"
      ],
      "metadata": {
        "id": "_aXQzX_6A1eF"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "len(given_name)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "eQypclsQA0Jz",
        "outputId": "47cf22cd-0739-435e-c32c-0d9509df231b"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "6"
            ]
          },
          "metadata": {},
          "execution_count": 20
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "## Math: Integers vs Floats\n",
        "Floats have decimal places"
      ],
      "metadata": {
        "id": "TEWO4TFXBCQK"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "print(myage)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "0OUgIfa3BA3H",
        "outputId": "e9297189-c347-4ac1-fcff-edb7247b2cae"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "25\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "myage/4"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "M7KGJaYgBJy9",
        "outputId": "1a3253cc-51d9-47c1-99cb-d138d4593c93"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "6.25"
            ]
          },
          "metadata": {},
          "execution_count": 22
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "type(myage/4)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "-52MUf5yBRIB",
        "outputId": "a4beb62e-2b02-42bf-d730-18eec698caf3"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "float"
            ]
          },
          "metadata": {},
          "execution_count": 23
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "float(myage)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "ZScqGKFrBWY7",
        "outputId": "f0aa6b51-5987-4940-f2b1-b27dc8f27fdb"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "25.0"
            ]
          },
          "metadata": {},
          "execution_count": 24
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "myage + float(myage)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "SZlSjt9FBnyb",
        "outputId": "de64420b-ed62-4610-83bf-d8d2576934d5"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "50.0"
            ]
          },
          "metadata": {},
          "execution_count": 25
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "## Basics Wrap-up"
      ],
      "metadata": {
        "id": "4Q4Oh7q3BuRX"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "full_name_age = given_name+ 'O' +family_name+ 'is my full name, and I am' +str(myage)+ 'years old'"
      ],
      "metadata": {
        "id": "MLwz9LlIBx7R"
      },
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "print(full_name_age)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "IGTteSrYCie6",
        "outputId": "c60637a7-c55e-460b-ee56-d98cdef9309b"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "MaggieOShostakis my full name, and I am25years old\n"
          ]
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "This error results because you have characters & integers together: \n",
        "\n",
        "**_TypeError                                 Traceback (most recent call last)\n",
        "<ipython-input-29-6a14459cc019> in <module>\n",
        "----> 1 full_name_age = given_name+ \"O\" +family_name+ \"is my full name, and I am\" +myage+ \"years old\"_**\n",
        "\n",
        "TypeError: can only concatenate str (not \"int\") to str"
      ],
      "metadata": {
        "id": "LQGrny_KCYlg"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "## Math in Python"
      ],
      "metadata": {
        "id": "qEZY5RYDDrZv"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "6/2"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "_UWdMiBUDrGJ",
        "outputId": "cb5f8a96-777b-45bd-8693-77d69924b269"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "3.0"
            ]
          },
          "metadata": {},
          "execution_count": 36
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "5/2"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "0-lPT6qHDzBw",
        "outputId": "37a1d98b-3acd-4edd-8be5-4359647e83a4"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "2.5"
            ]
          },
          "metadata": {},
          "execution_count": 37
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "To round a number, use a double backslash (//)"
      ],
      "metadata": {
        "id": "2E9dcyciEWAv"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "5//2"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "0QtNXHkfEM9D",
        "outputId": "ac54b45a-e432-421d-d59c-65b0eaba1f03"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "2"
            ]
          },
          "metadata": {},
          "execution_count": 39
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "print(type(5/2), type(5//2))"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "569iFCU1EH9R",
        "outputId": "6b56b382-21f3-4aa1-ca81-7d9d02920e92"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "<class 'float'> <class 'int'>\n"
          ]
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "Putting a hash (#) after a command, then it will ignore anything after it."
      ],
      "metadata": {
        "id": "-NwqhxsUEaJn"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "2*2"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "dZq4nSgrE2K0",
        "outputId": "2ad383d4-2a60-4d8b-a03f-4c3df47e8e81"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "4"
            ]
          },
          "metadata": {},
          "execution_count": 40
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "### Built-in Summary Tools"
      ],
      "metadata": {
        "id": "-0CQHDZxE5ao"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "nums = (3,1,4,2,5)\n",
        "type(nums)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "0YYm4xyCE38G",
        "outputId": "1b20c7f6-80dc-4109-9d22-b3dabde1d16c"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "tuple"
            ]
          },
          "metadata": {},
          "execution_count": 1
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "max(nums)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "A98ZEErDFFX_",
        "outputId": "9b61211f-7f6c-4862-82b4-83382faedac8"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "5"
            ]
          },
          "metadata": {},
          "execution_count": 2
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "min(nums)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "mLa_hsZIFHRY",
        "outputId": "c21dd9a9-7938-48ba-cb01-8fd03e8f0f99"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "1"
            ]
          },
          "metadata": {},
          "execution_count": 3
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "pi=3.14159\n",
        "print(pi)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "F7gQWBITFRT2",
        "outputId": "67186f3f-52bf-4829-ea8c-f9f18ab1cc6c"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "3.14159\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "round(pi, ndigits=2)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "uUzl6IZTFWKF",
        "outputId": "142023f5-99db-459b-ba01-e07b53974b4a"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "3.14"
            ]
          },
          "metadata": {},
          "execution_count": 5
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "round(2.55, ndigits=0)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "-EAeUHexFfFg",
        "outputId": "4c75e5d3-1fd8-4f9a-e9fd-3a33c42d3fbb"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "3.0"
            ]
          },
          "metadata": {},
          "execution_count": 6
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "If you don't know what a function does use: \n",
        "```bash\n",
        "help(name_function)\n",
        "```"
      ],
      "metadata": {
        "id": "rI9OS_pkFqc3"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "help(round)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "D2-L2KK8FoXZ",
        "outputId": "5f15b140-325d-4a57-fac2-84752ce70f92"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Help on built-in function round in module builtins:\n",
            "\n",
            "round(number, ndigits=None)\n",
            "    Round a number to a given precision in decimal digits.\n",
            "    \n",
            "    The return value is an integer if ndigits is omitted or None.  Otherwise\n",
            "    the return value has the same type as the number.  ndigits may be negative.\n",
            "\n"
          ]
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "## Libraries"
      ],
      "metadata": {
        "id": "q2m_17AqqxXb"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "import math"
      ],
      "metadata": {
        "id": "4L7X1Riyq1B_"
      },
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "print(math.pi)"
      ],
      "metadata": {
        "id": "V9s4Ha_3rLnT",
        "outputId": "a4fab3e4-3d16-44aa-feff-39441ac86970",
        "colab": {
          "base_uri": "https://localhost:8080/"
        }
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "3.141592653589793\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "import math as m\n",
        "print('pi is', m.pi)\n"
      ],
      "metadata": {
        "id": "1G8bciz4rTYb",
        "outputId": "1853b93a-e649-4586-c32f-12260db53794",
        "colab": {
          "base_uri": "https://localhost:8080/"
        }
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "pi is 3.141592653589793\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "type(m.pi)"
      ],
      "metadata": {
        "id": "H_UuqNX1rrZC",
        "outputId": "4a5d0698-72ab-4f6a-b00b-86e83b633a96",
        "colab": {
          "base_uri": "https://localhost:8080/"
        }
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "float"
            ]
          },
          "metadata": {},
          "execution_count": 14
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "print('cosine of pi is', m.cos(m.pi))"
      ],
      "metadata": {
        "id": "VBkHDChlrxun",
        "outputId": "e9968afb-3abd-4a9f-bc30-da444b761cad",
        "colab": {
          "base_uri": "https://localhost:8080/"
        }
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "cosine of pi is -1.0\n"
          ]
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "If you need help with any commands, just type\n",
        "```\n",
        "Help()\n",
        "```"
      ],
      "metadata": {
        "id": "cvS4S0z4r71P"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "help(math)"
      ],
      "metadata": {
        "id": "WynaxqaBsjbB",
        "outputId": "9be21fcb-47b7-4c5c-f170-96f061a0c9ca",
        "colab": {
          "base_uri": "https://localhost:8080/"
        }
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Help on built-in module math:\n",
            "\n",
            "NAME\n",
            "    math\n",
            "\n",
            "DESCRIPTION\n",
            "    This module provides access to the mathematical functions\n",
            "    defined by the C standard.\n",
            "\n",
            "FUNCTIONS\n",
            "    acos(x, /)\n",
            "        Return the arc cosine (measured in radians) of x.\n",
            "    \n",
            "    acosh(x, /)\n",
            "        Return the inverse hyperbolic cosine of x.\n",
            "    \n",
            "    asin(x, /)\n",
            "        Return the arc sine (measured in radians) of x.\n",
            "    \n",
            "    asinh(x, /)\n",
            "        Return the inverse hyperbolic sine of x.\n",
            "    \n",
            "    atan(x, /)\n",
            "        Return the arc tangent (measured in radians) of x.\n",
            "    \n",
            "    atan2(y, x, /)\n",
            "        Return the arc tangent (measured in radians) of y/x.\n",
            "        \n",
            "        Unlike atan(y/x), the signs of both x and y are considered.\n",
            "    \n",
            "    atanh(x, /)\n",
            "        Return the inverse hyperbolic tangent of x.\n",
            "    \n",
            "    ceil(x, /)\n",
            "        Return the ceiling of x as an Integral.\n",
            "        \n",
            "        This is the smallest integer >= x.\n",
            "    \n",
            "    copysign(x, y, /)\n",
            "        Return a float with the magnitude (absolute value) of x but the sign of y.\n",
            "        \n",
            "        On platforms that support signed zeros, copysign(1.0, -0.0)\n",
            "        returns -1.0.\n",
            "    \n",
            "    cos(x, /)\n",
            "        Return the cosine of x (measured in radians).\n",
            "    \n",
            "    cosh(x, /)\n",
            "        Return the hyperbolic cosine of x.\n",
            "    \n",
            "    degrees(x, /)\n",
            "        Convert angle x from radians to degrees.\n",
            "    \n",
            "    erf(x, /)\n",
            "        Error function at x.\n",
            "    \n",
            "    erfc(x, /)\n",
            "        Complementary error function at x.\n",
            "    \n",
            "    exp(x, /)\n",
            "        Return e raised to the power of x.\n",
            "    \n",
            "    expm1(x, /)\n",
            "        Return exp(x)-1.\n",
            "        \n",
            "        This function avoids the loss of precision involved in the direct evaluation of exp(x)-1 for small x.\n",
            "    \n",
            "    fabs(x, /)\n",
            "        Return the absolute value of the float x.\n",
            "    \n",
            "    factorial(x, /)\n",
            "        Find x!.\n",
            "        \n",
            "        Raise a ValueError if x is negative or non-integral.\n",
            "    \n",
            "    floor(x, /)\n",
            "        Return the floor of x as an Integral.\n",
            "        \n",
            "        This is the largest integer <= x.\n",
            "    \n",
            "    fmod(x, y, /)\n",
            "        Return fmod(x, y), according to platform C.\n",
            "        \n",
            "        x % y may differ.\n",
            "    \n",
            "    frexp(x, /)\n",
            "        Return the mantissa and exponent of x, as pair (m, e).\n",
            "        \n",
            "        m is a float and e is an int, such that x = m * 2.**e.\n",
            "        If x is 0, m and e are both 0.  Else 0.5 <= abs(m) < 1.0.\n",
            "    \n",
            "    fsum(seq, /)\n",
            "        Return an accurate floating point sum of values in the iterable seq.\n",
            "        \n",
            "        Assumes IEEE-754 floating point arithmetic.\n",
            "    \n",
            "    gamma(x, /)\n",
            "        Gamma function at x.\n",
            "    \n",
            "    gcd(x, y, /)\n",
            "        greatest common divisor of x and y\n",
            "    \n",
            "    hypot(x, y, /)\n",
            "        Return the Euclidean distance, sqrt(x*x + y*y).\n",
            "    \n",
            "    isclose(a, b, *, rel_tol=1e-09, abs_tol=0.0)\n",
            "        Determine whether two floating point numbers are close in value.\n",
            "        \n",
            "          rel_tol\n",
            "            maximum difference for being considered \"close\", relative to the\n",
            "            magnitude of the input values\n",
            "          abs_tol\n",
            "            maximum difference for being considered \"close\", regardless of the\n",
            "            magnitude of the input values\n",
            "        \n",
            "        Return True if a is close in value to b, and False otherwise.\n",
            "        \n",
            "        For the values to be considered close, the difference between them\n",
            "        must be smaller than at least one of the tolerances.\n",
            "        \n",
            "        -inf, inf and NaN behave similarly to the IEEE 754 Standard.  That\n",
            "        is, NaN is not close to anything, even itself.  inf and -inf are\n",
            "        only close to themselves.\n",
            "    \n",
            "    isfinite(x, /)\n",
            "        Return True if x is neither an infinity nor a NaN, and False otherwise.\n",
            "    \n",
            "    isinf(x, /)\n",
            "        Return True if x is a positive or negative infinity, and False otherwise.\n",
            "    \n",
            "    isnan(x, /)\n",
            "        Return True if x is a NaN (not a number), and False otherwise.\n",
            "    \n",
            "    ldexp(x, i, /)\n",
            "        Return x * (2**i).\n",
            "        \n",
            "        This is essentially the inverse of frexp().\n",
            "    \n",
            "    lgamma(x, /)\n",
            "        Natural logarithm of absolute value of Gamma function at x.\n",
            "    \n",
            "    log(...)\n",
            "        log(x, [base=math.e])\n",
            "        Return the logarithm of x to the given base.\n",
            "        \n",
            "        If the base not specified, returns the natural logarithm (base e) of x.\n",
            "    \n",
            "    log10(x, /)\n",
            "        Return the base 10 logarithm of x.\n",
            "    \n",
            "    log1p(x, /)\n",
            "        Return the natural logarithm of 1+x (base e).\n",
            "        \n",
            "        The result is computed in a way which is accurate for x near zero.\n",
            "    \n",
            "    log2(x, /)\n",
            "        Return the base 2 logarithm of x.\n",
            "    \n",
            "    modf(x, /)\n",
            "        Return the fractional and integer parts of x.\n",
            "        \n",
            "        Both results carry the sign of x and are floats.\n",
            "    \n",
            "    pow(x, y, /)\n",
            "        Return x**y (x to the power of y).\n",
            "    \n",
            "    radians(x, /)\n",
            "        Convert angle x from degrees to radians.\n",
            "    \n",
            "    remainder(x, y, /)\n",
            "        Difference between x and the closest integer multiple of y.\n",
            "        \n",
            "        Return x - n*y where n*y is the closest integer multiple of y.\n",
            "        In the case where x is exactly halfway between two multiples of\n",
            "        y, the nearest even value of n is used. The result is always exact.\n",
            "    \n",
            "    sin(x, /)\n",
            "        Return the sine of x (measured in radians).\n",
            "    \n",
            "    sinh(x, /)\n",
            "        Return the hyperbolic sine of x.\n",
            "    \n",
            "    sqrt(x, /)\n",
            "        Return the square root of x.\n",
            "    \n",
            "    tan(x, /)\n",
            "        Return the tangent of x (measured in radians).\n",
            "    \n",
            "    tanh(x, /)\n",
            "        Return the hyperbolic tangent of x.\n",
            "    \n",
            "    trunc(x, /)\n",
            "        Truncates the Real x to the nearest Integral toward 0.\n",
            "        \n",
            "        Uses the __trunc__ magic method.\n",
            "\n",
            "DATA\n",
            "    e = 2.718281828459045\n",
            "    inf = inf\n",
            "    nan = nan\n",
            "    pi = 3.141592653589793\n",
            "    tau = 6.283185307179586\n",
            "\n",
            "FILE\n",
            "    (built-in)\n",
            "\n",
            "\n"
          ]
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "# Reading Tables as Data"
      ],
      "metadata": {
        "id": "DiCcr6rTsGc4"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "import pandas as pd"
      ],
      "metadata": {
        "id": "CxWlNCQ-sCr0"
      },
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "markdown",
      "source": [
        "**pandas** is a library for python that reads spreadsheets as data"
      ],
      "metadata": {
        "id": "oQbWaxDRsVrV"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "help(pd)"
      ],
      "metadata": {
        "id": "3ksvC9WUsddT",
        "outputId": "7542d082-8776-4513-8757-912ec0b32d30",
        "colab": {
          "base_uri": "https://localhost:8080/"
        }
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Help on package pandas:\n",
            "\n",
            "NAME\n",
            "    pandas\n",
            "\n",
            "DESCRIPTION\n",
            "    pandas - a powerful data analysis and manipulation library for Python\n",
            "    =====================================================================\n",
            "    \n",
            "    **pandas** is a Python package providing fast, flexible, and expressive data\n",
            "    structures designed to make working with \"relational\" or \"labeled\" data both\n",
            "    easy and intuitive. It aims to be the fundamental high-level building block for\n",
            "    doing practical, **real world** data analysis in Python. Additionally, it has\n",
            "    the broader goal of becoming **the most powerful and flexible open source data\n",
            "    analysis / manipulation tool available in any language**. It is already well on\n",
            "    its way toward this goal.\n",
            "    \n",
            "    Main Features\n",
            "    -------------\n",
            "    Here are just a few of the things that pandas does well:\n",
            "    \n",
            "      - Easy handling of missing data in floating point as well as non-floating\n",
            "        point data.\n",
            "      - Size mutability: columns can be inserted and deleted from DataFrame and\n",
            "        higher dimensional objects\n",
            "      - Automatic and explicit data alignment: objects can be explicitly aligned\n",
            "        to a set of labels, or the user can simply ignore the labels and let\n",
            "        `Series`, `DataFrame`, etc. automatically align the data for you in\n",
            "        computations.\n",
            "      - Powerful, flexible group by functionality to perform split-apply-combine\n",
            "        operations on data sets, for both aggregating and transforming data.\n",
            "      - Make it easy to convert ragged, differently-indexed data in other Python\n",
            "        and NumPy data structures into DataFrame objects.\n",
            "      - Intelligent label-based slicing, fancy indexing, and subsetting of large\n",
            "        data sets.\n",
            "      - Intuitive merging and joining data sets.\n",
            "      - Flexible reshaping and pivoting of data sets.\n",
            "      - Hierarchical labeling of axes (possible to have multiple labels per tick).\n",
            "      - Robust IO tools for loading data from flat files (CSV and delimited),\n",
            "        Excel files, databases, and saving/loading data from the ultrafast HDF5\n",
            "        format.\n",
            "      - Time series-specific functionality: date range generation and frequency\n",
            "        conversion, moving window statistics, date shifting and lagging.\n",
            "\n",
            "PACKAGE CONTENTS\n",
            "    _config (package)\n",
            "    _libs (package)\n",
            "    _testing (package)\n",
            "    _typing\n",
            "    _version\n",
            "    api (package)\n",
            "    arrays (package)\n",
            "    compat (package)\n",
            "    conftest\n",
            "    core (package)\n",
            "    errors (package)\n",
            "    io (package)\n",
            "    plotting (package)\n",
            "    testing\n",
            "    tests (package)\n",
            "    tseries (package)\n",
            "    util (package)\n",
            "\n",
            "SUBMODULES\n",
            "    _hashtable\n",
            "    _lib\n",
            "    _tslib\n",
            "    offsets\n",
            "\n",
            "FUNCTIONS\n",
            "    __getattr__(name)\n",
            "        # GH 27101\n",
            "\n",
            "DATA\n",
            "    IndexSlice = <pandas.core.indexing._IndexSlice object>\n",
            "    NA = <NA>\n",
            "    NaT = NaT\n",
            "    __docformat__ = 'restructuredtext'\n",
            "    __git_version__ = '66e3805b8cabe977f40c05259cc3fcf7ead5687d'\n",
            "    describe_option = <pandas._config.config.CallableDynamicDoc object>\n",
            "    get_option = <pandas._config.config.CallableDynamicDoc object>\n",
            "    options = <pandas._config.config.DictWrapper object>\n",
            "    reset_option = <pandas._config.config.CallableDynamicDoc object>\n",
            "    set_option = <pandas._config.config.CallableDynamicDoc object>\n",
            "\n",
            "VERSION\n",
            "    1.3.5\n",
            "\n",
            "FILE\n",
            "    /usr/local/lib/python3.7/dist-packages/pandas/__init__.py\n",
            "\n",
            "\n"
          ]
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "To read a data set, use \n",
        "```\n",
        "data = pd.read_csv\n",
        "```"
      ],
      "metadata": {
        "id": "lbaKHYzLtZbe"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "data = pd.read_csv('sample_data/california_housing_test.csv')\n",
        "print(data)"
      ],
      "metadata": {
        "id": "sAMwZjBfst5j",
        "outputId": "d50c38c0-a235-423f-cd7d-95a22402048f",
        "colab": {
          "base_uri": "https://localhost:8080/"
        }
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "      longitude  latitude  housing_median_age  total_rooms  total_bedrooms  \\\n",
            "0       -122.05     37.37                27.0       3885.0           661.0   \n",
            "1       -118.30     34.26                43.0       1510.0           310.0   \n",
            "2       -117.81     33.78                27.0       3589.0           507.0   \n",
            "3       -118.36     33.82                28.0         67.0            15.0   \n",
            "4       -119.67     36.33                19.0       1241.0           244.0   \n",
            "...         ...       ...                 ...          ...             ...   \n",
            "2995    -119.86     34.42                23.0       1450.0           642.0   \n",
            "2996    -118.14     34.06                27.0       5257.0          1082.0   \n",
            "2997    -119.70     36.30                10.0        956.0           201.0   \n",
            "2998    -117.12     34.10                40.0         96.0            14.0   \n",
            "2999    -119.63     34.42                42.0       1765.0           263.0   \n",
            "\n",
            "      population  households  median_income  median_house_value  \n",
            "0         1537.0       606.0         6.6085            344700.0  \n",
            "1          809.0       277.0         3.5990            176500.0  \n",
            "2         1484.0       495.0         5.7934            270500.0  \n",
            "3           49.0        11.0         6.1359            330000.0  \n",
            "4          850.0       237.0         2.9375             81700.0  \n",
            "...          ...         ...            ...                 ...  \n",
            "2995      1258.0       607.0         1.1790            225000.0  \n",
            "2996      3496.0      1036.0         3.3906            237200.0  \n",
            "2997       693.0       220.0         2.2895             62000.0  \n",
            "2998        46.0        14.0         3.2708            162500.0  \n",
            "2999       753.0       260.0         8.5608            500001.0  \n",
            "\n",
            "[3000 rows x 9 columns]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "data = pd.read_csv('sample_data/california_housing_test.csv', index_col='median_income')\n",
        "print(data)"
      ],
      "metadata": {
        "id": "inR8uHQZtDLK",
        "outputId": "44509e85-1a9e-4677-9830-25df87f0792d",
        "colab": {
          "base_uri": "https://localhost:8080/"
        }
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "               longitude  latitude  housing_median_age  total_rooms  \\\n",
            "median_income                                                         \n",
            "6.6085           -122.05     37.37                27.0       3885.0   \n",
            "3.5990           -118.30     34.26                43.0       1510.0   \n",
            "5.7934           -117.81     33.78                27.0       3589.0   \n",
            "6.1359           -118.36     33.82                28.0         67.0   \n",
            "2.9375           -119.67     36.33                19.0       1241.0   \n",
            "...                  ...       ...                 ...          ...   \n",
            "1.1790           -119.86     34.42                23.0       1450.0   \n",
            "3.3906           -118.14     34.06                27.0       5257.0   \n",
            "2.2895           -119.70     36.30                10.0        956.0   \n",
            "3.2708           -117.12     34.10                40.0         96.0   \n",
            "8.5608           -119.63     34.42                42.0       1765.0   \n",
            "\n",
            "               total_bedrooms  population  households  median_house_value  \n",
            "median_income                                                              \n",
            "6.6085                  661.0      1537.0       606.0            344700.0  \n",
            "3.5990                  310.0       809.0       277.0            176500.0  \n",
            "5.7934                  507.0      1484.0       495.0            270500.0  \n",
            "6.1359                   15.0        49.0        11.0            330000.0  \n",
            "2.9375                  244.0       850.0       237.0             81700.0  \n",
            "...                       ...         ...         ...                 ...  \n",
            "1.1790                  642.0      1258.0       607.0            225000.0  \n",
            "3.3906                 1082.0      3496.0      1036.0            237200.0  \n",
            "2.2895                  201.0       693.0       220.0             62000.0  \n",
            "3.2708                   14.0        46.0        14.0            162500.0  \n",
            "8.5608                  263.0       753.0       260.0            500001.0  \n",
            "\n",
            "[3000 rows x 8 columns]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "type(data)"
      ],
      "metadata": {
        "id": "IRG4sM8ltiwe",
        "outputId": "a99d1671-2be6-4874-d27f-8ea05c213832",
        "colab": {
          "base_uri": "https://localhost:8080/"
        }
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "pandas.core.frame.DataFrame"
            ]
          },
          "metadata": {},
          "execution_count": 23
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "data.info()"
      ],
      "metadata": {
        "id": "-21qAIdztlhQ",
        "outputId": "c93607ff-a01d-4c24-c24c-b310cbd5700c",
        "colab": {
          "base_uri": "https://localhost:8080/"
        }
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "<class 'pandas.core.frame.DataFrame'>\n",
            "Float64Index: 3000 entries, 6.6085 to 8.5608\n",
            "Data columns (total 8 columns):\n",
            " #   Column              Non-Null Count  Dtype  \n",
            "---  ------              --------------  -----  \n",
            " 0   longitude           3000 non-null   float64\n",
            " 1   latitude            3000 non-null   float64\n",
            " 2   housing_median_age  3000 non-null   float64\n",
            " 3   total_rooms         3000 non-null   float64\n",
            " 4   total_bedrooms      3000 non-null   float64\n",
            " 5   population          3000 non-null   float64\n",
            " 6   households          3000 non-null   float64\n",
            " 7   median_house_value  3000 non-null   float64\n",
            "dtypes: float64(8)\n",
            "memory usage: 210.9 KB\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "print(data.columns)"
      ],
      "metadata": {
        "id": "BOfEVo3_t8pM",
        "outputId": "6d4ebf03-b674-4693-e5e7-84f3e8734cca",
        "colab": {
          "base_uri": "https://localhost:8080/"
        }
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Index(['longitude', 'latitude', 'housing_median_age', 'total_rooms',\n",
            "       'total_bedrooms', 'population', 'households', 'median_house_value'],\n",
            "      dtype='object')\n"
          ]
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "Using\n",
        "```\n",
        "data.T\n",
        "```\n",
        "Will transpose the data (columns --> rows & vice versa)"
      ],
      "metadata": {
        "id": "fAFsoXFJuKDL"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "print(data.T)"
      ],
      "metadata": {
        "id": "Np__AE41uEXf",
        "outputId": "7cb55bc4-cee3-4666-e5f3-95968c8e913b",
        "colab": {
          "base_uri": "https://localhost:8080/"
        }
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "median_income          6.6085     3.5990     5.7934     6.1359    2.9375  \\\n",
            "longitude             -122.05    -118.30    -117.81    -118.36   -119.67   \n",
            "latitude                37.37      34.26      33.78      33.82     36.33   \n",
            "housing_median_age      27.00      43.00      27.00      28.00     19.00   \n",
            "total_rooms           3885.00    1510.00    3589.00      67.00   1241.00   \n",
            "total_bedrooms         661.00     310.00     507.00      15.00    244.00   \n",
            "population            1537.00     809.00    1484.00      49.00    850.00   \n",
            "households             606.00     277.00     495.00      11.00    237.00   \n",
            "median_house_value  344700.00  176500.00  270500.00  330000.00  81700.00   \n",
            "\n",
            "median_income         1.6635    1.6641     3.2250     3.6696     2.3333  ...  \\\n",
            "longitude            -119.56   -121.43    -120.65    -122.84    -118.02  ...   \n",
            "latitude               36.51     38.63      35.48      38.40      34.08  ...   \n",
            "housing_median_age     37.00     43.00      19.00      15.00      31.00  ...   \n",
            "total_rooms          1018.00   1009.00    2310.00    3080.00    2402.00  ...   \n",
            "total_bedrooms        213.00    225.00     471.00     617.00     632.00  ...   \n",
            "population            663.00    604.00    1341.00    1446.00    2830.00  ...   \n",
            "households            204.00    218.00     441.00     599.00     603.00  ...   \n",
            "median_house_value  67000.00  67000.00  166900.00  194400.00  164200.00  ...   \n",
            "\n",
            "median_income          2.6923     7.1997     6.2263     5.1048     5.5867  \\\n",
            "longitude             -118.23    -117.17    -122.33    -117.91    -117.93   \n",
            "latitude                34.09      34.28      37.39      33.60      33.86   \n",
            "housing_median_age      49.00      13.00      52.00      37.00      35.00   \n",
            "total_rooms           1638.00    4867.00     573.00    2088.00     931.00   \n",
            "total_bedrooms         456.00     718.00     102.00     510.00     181.00   \n",
            "population            1500.00     780.00     232.00     673.00     516.00   \n",
            "households             430.00     250.00      92.00     390.00     174.00   \n",
            "median_house_value  150000.00  253800.00  500001.00  500001.00  182500.00   \n",
            "\n",
            "median_income          1.1790     3.3906   2.2895     3.2708     8.5608  \n",
            "longitude             -119.86    -118.14   -119.7    -117.12    -119.63  \n",
            "latitude                34.42      34.06     36.3      34.10      34.42  \n",
            "housing_median_age      23.00      27.00     10.0      40.00      42.00  \n",
            "total_rooms           1450.00    5257.00    956.0      96.00    1765.00  \n",
            "total_bedrooms         642.00    1082.00    201.0      14.00     263.00  \n",
            "population            1258.00    3496.00    693.0      46.00     753.00  \n",
            "households             607.00    1036.00    220.0      14.00     260.00  \n",
            "median_house_value  225000.00  237200.00  62000.0  162500.00  500001.00  \n",
            "\n",
            "[8 rows x 3000 columns]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "To look at your data use:\n",
        "```\n",
        "print(data.describe())\n",
        "```"
      ],
      "metadata": {
        "id": "kqGx_gA8uzJq"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "print(data.describe())"
      ],
      "metadata": {
        "id": "a7GAPXjUuU4R",
        "outputId": "d57efa7f-9a36-4d5d-8c7d-5202b9e6604b",
        "colab": {
          "base_uri": "https://localhost:8080/"
        }
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "         longitude    latitude  housing_median_age   total_rooms  \\\n",
            "count  3000.000000  3000.00000         3000.000000   3000.000000   \n",
            "mean   -119.589200    35.63539           28.845333   2599.578667   \n",
            "std       1.994936     2.12967           12.555396   2155.593332   \n",
            "min    -124.180000    32.56000            1.000000      6.000000   \n",
            "25%    -121.810000    33.93000           18.000000   1401.000000   \n",
            "50%    -118.485000    34.27000           29.000000   2106.000000   \n",
            "75%    -118.020000    37.69000           37.000000   3129.000000   \n",
            "max    -114.490000    41.92000           52.000000  30450.000000   \n",
            "\n",
            "       total_bedrooms    population  households  median_house_value  \n",
            "count     3000.000000   3000.000000  3000.00000          3000.00000  \n",
            "mean       529.950667   1402.798667   489.91200        205846.27500  \n",
            "std        415.654368   1030.543012   365.42271        113119.68747  \n",
            "min          2.000000      5.000000     2.00000         22500.00000  \n",
            "25%        291.000000    780.000000   273.00000        121200.00000  \n",
            "50%        437.000000   1155.000000   409.50000        177650.00000  \n",
            "75%        636.000000   1742.750000   597.25000        263975.00000  \n",
            "max       5419.000000  11935.000000  4930.00000        500001.00000  \n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "print(data.T.describe())"
      ],
      "metadata": {
        "id": "07pDeFisvOsY",
        "outputId": "229225d1-752c-4c1e-c36d-77dd15ca4696",
        "colab": {
          "base_uri": "https://localhost:8080/"
        }
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "median_income         6.6085         3.5990         5.7934         6.1359  \\\n",
            "count               8.000000       8.000000       8.000000       8.000000   \n",
            "mean            43916.415000   22420.620000   34564.746250   41260.682500   \n",
            "std            121541.970835   62259.710451   95340.051195  116668.316062   \n",
            "min              -122.050000    -118.300000    -117.810000    -118.360000   \n",
            "25%                34.777500      40.815000      32.085000      14.000000   \n",
            "50%               633.500000     293.500000     501.000000      30.910000   \n",
            "75%              2124.000000     984.250000    2010.250000      53.500000   \n",
            "max            344700.000000  176500.000000  270500.000000  330000.000000   \n",
            "\n",
            "median_income        2.9375        1.6635        1.6641         3.2250  \\\n",
            "count              8.000000      8.000000      8.000000       8.000000   \n",
            "mean           10525.957500   8631.493750   8627.025000   21424.603750   \n",
            "std            28762.371344  23587.400994  23589.024838   58786.621064   \n",
            "min             -119.670000   -119.560000   -121.430000    -120.650000   \n",
            "25%               31.997500     36.877500     41.907500      31.360000   \n",
            "50%              240.500000    208.500000    221.500000     456.000000   \n",
            "75%              947.750000    751.750000    705.250000    1583.250000   \n",
            "max            81700.000000  67000.000000  67000.000000  166900.000000   \n",
            "\n",
            "median_income         3.6696         2.3333  ...       2.6923         7.1997  \\\n",
            "count               8.000000       8.000000  ...       8.0000       8.000000   \n",
            "mean            25009.070000   21326.757500  ...   19248.6075   32543.138750   \n",
            "std             68452.345193   57740.247048  ...   52835.6918   89416.267414   \n",
            "min              -122.840000    -118.020000  ...    -118.2300    -117.170000   \n",
            "25%                32.550000      33.310000  ...      45.2725      28.960000   \n",
            "50%               608.000000     617.500000  ...     443.0000     484.000000   \n",
            "75%              1854.500000    2509.000000  ...    1534.5000    1801.750000   \n",
            "max            194400.000000  164200.000000  ...  150000.0000  253800.000000   \n",
            "\n",
            "median_income         6.2263         5.1048         5.5867         1.1790  \\\n",
            "count               8.000000       8.000000       8.000000       8.000000   \n",
            "mean            62620.882500   62951.836250   23031.616250   28611.820000   \n",
            "std            176728.371353  176595.895348   64435.814749   79354.891655   \n",
            "min              -122.330000    -117.910000    -117.930000    -119.860000   \n",
            "25%                48.347500      36.150000      34.715000      31.565000   \n",
            "50%                97.000000     450.000000     177.500000     624.500000   \n",
            "75%               317.250000    1026.750000     619.750000    1306.000000   \n",
            "max            500001.000000  500001.000000  182500.000000  225000.000000   \n",
            "\n",
            "median_income         3.3906        2.2895         3.2708         8.5608  \n",
            "count               8.000000      8.000000       8.000000       8.000000  \n",
            "mean            31001.740000   7999.575000   20328.372500   62874.848750  \n",
            "std             83338.462109  21822.508466   57446.044718  176626.669812  \n",
            "min              -118.140000   -119.700000    -117.120000    -119.630000  \n",
            "25%                32.295000     29.725000      14.000000      40.105000  \n",
            "50%              1059.000000    210.500000      37.050000     261.500000  \n",
            "75%              3936.250000    758.750000      58.500000    1006.000000  \n",
            "max            237200.000000  62000.000000  162500.000000  500001.000000  \n",
            "\n",
            "[8 rows x 3000 columns]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "To save your data use:\n",
        "```\n",
        "data.T.to_csv('sample_data/california_housing_test_transposed.csv')\n",
        "```"
      ],
      "metadata": {
        "id": "lNvlEDrzu6lP"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "data.T.to_csv('sample_data/california_housing_test_transposed.csv')"
      ],
      "metadata": {
        "id": "4rwz6NTburKJ"
      },
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "markdown",
      "source": [
        "## Plotting Data"
      ],
      "metadata": {
        "id": "cC_EqyVCv62x"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "%matplotlib inline\n",
        "import matplotlib.pyplot as plt"
      ],
      "metadata": {
        "id": "JP1i-p1mv8ex"
      },
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "time = [0,1,2,3,4,5]\n",
        "response = [20,25,40,80,65,47]"
      ],
      "metadata": {
        "id": "P2yFIvFzwUrt"
      },
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "type(time)"
      ],
      "metadata": {
        "id": "yP3VMWxTwhhg",
        "outputId": "3acaf2b4-fcc1-4546-f05a-f5d8cf1b72f8",
        "colab": {
          "base_uri": "https://localhost:8080/"
        }
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "list"
            ]
          },
          "metadata": {},
          "execution_count": 36
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "print(time,response)"
      ],
      "metadata": {
        "id": "68rHeG6FwlXX",
        "outputId": "727d3c58-f08f-4764-eadd-277fb65aa4e1",
        "colab": {
          "base_uri": "https://localhost:8080/"
        }
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "[0, 1, 2, 3, 4, 5] [20, 25, 40, 80, 65, 47]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "To make associations (i.e., graph), need to use MatplotLib package"
      ],
      "metadata": {
        "id": "FHwGo1FUwuhS"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "plt.plot(time,response)\n",
        "plt.xlabel('time (hours)')\n",
        "plt.ylabel('response (cm)')"
      ],
      "metadata": {
        "id": "SpyyG9CnwsHa",
        "outputId": "b932ceab-e9ec-419e-9906-6e11968e95fc",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 316
        }
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "Text(0, 0.5, 'response (cm)')"
            ]
          },
          "metadata": {},
          "execution_count": 41
        },
        {
          "output_type": "display_data",
          "data": {
            "text/plain": [
              "<Figure size 432x288 with 1 Axes>"
            ],
            "image/png": "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\n"
          },
          "metadata": {
            "needs_background": "light"
          }
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "Using a ! in front of a line keeps python from running\n",
        "```\n",
        "!curl -L\n",
        "```\n",
        "Tells linux it is a link to use"
      ],
      "metadata": {
        "id": "Ssa0PjIWxF8t"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "!curl -L -o PracCompPyData.zip http://bit.ly/PracCompPyData"
      ],
      "metadata": {
        "id": "zXr5BpNPxHAc",
        "outputId": "df8ff5c7-8cb8-4646-cb60-744d3ee33535",
        "colab": {
          "base_uri": "https://localhost:8080/"
        }
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n",
            "                                 Dload  Upload   Total   Spent    Left  Speed\n",
            "100   137  100   137    0     0   1245      0 --:--:-- --:--:-- --:--:--  1245\n",
            "100   116    0   116    0     0    106      0 --:--:--  0:00:01 --:--:--   144\n",
            "100   340  100   340    0     0    206      0  0:00:01  0:00:01 --:--:--     0\n",
            "100   534    0   534    0     0    263      0 --:--:--  0:00:02 --:--:--   263\n",
            "100 38179  100 38179    0     0  17306      0  0:00:02  0:00:02 --:--:-- 17306\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "!unzip PracCompPyData.zip"
      ],
      "metadata": {
        "id": "9p4RB3tyxeRy",
        "outputId": "caa4ca15-d5c7-4728-ef9e-070e07314feb",
        "colab": {
          "base_uri": "https://localhost:8080/"
        }
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Archive:  PracCompPyData.zip\n",
            "  inflating: data/gapminder_all.csv  \n",
            "  inflating: data/gapminder_gdp_africa.csv  \n",
            "  inflating: data/gapminder_gdp_americas.csv  \n",
            "  inflating: data/gapminder_gdp_asia.csv  \n",
            "  inflating: data/gapminder_gdp_europe.csv  \n",
            "  inflating: data/gapminder_gdp_oceania.csv  \n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "data = pd.read_csv('data/gapminder_gdp_oceania.csv', index_col='country')\n",
        "print(data)"
      ],
      "metadata": {
        "id": "JW-SzIfdxl_3",
        "outputId": "7b0a56dd-7248-4bd3-cb25-a727d3f4af6f",
        "colab": {
          "base_uri": "https://localhost:8080/"
        }
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "             gdpPercap_1952  gdpPercap_1957  gdpPercap_1962  gdpPercap_1967  \\\n",
            "country                                                                       \n",
            "Australia       10039.59564     10949.64959     12217.22686     14526.12465   \n",
            "New Zealand     10556.57566     12247.39532     13175.67800     14463.91893   \n",
            "\n",
            "             gdpPercap_1972  gdpPercap_1977  gdpPercap_1982  gdpPercap_1987  \\\n",
            "country                                                                       \n",
            "Australia       16788.62948     18334.19751     19477.00928     21888.88903   \n",
            "New Zealand     16046.03728     16233.71770     17632.41040     19007.19129   \n",
            "\n",
            "             gdpPercap_1992  gdpPercap_1997  gdpPercap_2002  gdpPercap_2007  \n",
            "country                                                                      \n",
            "Australia       23424.76683     26997.93657     30687.75473     34435.36744  \n",
            "New Zealand     18363.32494     21050.41377     23189.80135     25185.00911  \n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "years = data.columns.str.strip('gdpPercap_')\n",
        "type(years)"
      ],
      "metadata": {
        "id": "VMziav3EyIaz",
        "outputId": "be486c92-953b-407f-cfd5-b59192dc9f3e",
        "colab": {
          "base_uri": "https://localhost:8080/"
        }
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "pandas.core.indexes.base.Index"
            ]
          },
          "metadata": {},
          "execution_count": 48
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "data.info()"
      ],
      "metadata": {
        "id": "LKskQY4YyYso",
        "outputId": "39ede60e-c211-42bb-9ed9-626cd9711b19",
        "colab": {
          "base_uri": "https://localhost:8080/"
        }
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "<class 'pandas.core.frame.DataFrame'>\n",
            "Index: 2 entries, Australia to New Zealand\n",
            "Data columns (total 12 columns):\n",
            " #   Column          Non-Null Count  Dtype  \n",
            "---  ------          --------------  -----  \n",
            " 0   gdpPercap_1952  2 non-null      float64\n",
            " 1   gdpPercap_1957  2 non-null      float64\n",
            " 2   gdpPercap_1962  2 non-null      float64\n",
            " 3   gdpPercap_1967  2 non-null      float64\n",
            " 4   gdpPercap_1972  2 non-null      float64\n",
            " 5   gdpPercap_1977  2 non-null      float64\n",
            " 6   gdpPercap_1982  2 non-null      float64\n",
            " 7   gdpPercap_1987  2 non-null      float64\n",
            " 8   gdpPercap_1992  2 non-null      float64\n",
            " 9   gdpPercap_1997  2 non-null      float64\n",
            " 10  gdpPercap_2002  2 non-null      float64\n",
            " 11  gdpPercap_2007  2 non-null      float64\n",
            "dtypes: float64(12)\n",
            "memory usage: 316.0+ bytes\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "print(data.columns)"
      ],
      "metadata": {
        "id": "BYSv70Jeye3b",
        "outputId": "a925942d-dcb0-4c66-e98c-baa4177416ca",
        "colab": {
          "base_uri": "https://localhost:8080/"
        }
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Index(['gdpPercap_1952', 'gdpPercap_1957', 'gdpPercap_1962', 'gdpPercap_1967',\n",
            "       'gdpPercap_1972', 'gdpPercap_1977', 'gdpPercap_1982', 'gdpPercap_1987',\n",
            "       'gdpPercap_1992', 'gdpPercap_1997', 'gdpPercap_2002', 'gdpPercap_2007'],\n",
            "      dtype='object')\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "print(data.T)"
      ],
      "metadata": {
        "id": "8CCEHoKhyuuL",
        "outputId": "9683db24-e10a-4095-dbfe-fab8bac2fd9a",
        "colab": {
          "base_uri": "https://localhost:8080/"
        }
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "country           Australia  New Zealand\n",
            "gdpPercap_1952  10039.59564  10556.57566\n",
            "gdpPercap_1957  10949.64959  12247.39532\n",
            "gdpPercap_1962  12217.22686  13175.67800\n",
            "gdpPercap_1967  14526.12465  14463.91893\n",
            "gdpPercap_1972  16788.62948  16046.03728\n",
            "gdpPercap_1977  18334.19751  16233.71770\n",
            "gdpPercap_1982  19477.00928  17632.41040\n",
            "gdpPercap_1987  21888.88903  19007.19129\n",
            "gdpPercap_1992  23424.76683  18363.32494\n",
            "gdpPercap_1997  26997.93657  21050.41377\n",
            "gdpPercap_2002  30687.75473  23189.80135\n",
            "gdpPercap_2007  34435.36744  25185.00911\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "print(data.describe())"
      ],
      "metadata": {
        "id": "_-97zxrNy0t-",
        "outputId": "92eebd85-e499-4c16-81b9-424a6c949dcc",
        "colab": {
          "base_uri": "https://localhost:8080/"
        }
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "       gdpPercap_1952  gdpPercap_1957  gdpPercap_1962  gdpPercap_1967  \\\n",
            "count        2.000000        2.000000        2.000000        2.000000   \n",
            "mean     10298.085650    11598.522455    12696.452430    14495.021790   \n",
            "std        365.560078      917.644806      677.727301       43.986086   \n",
            "min      10039.595640    10949.649590    12217.226860    14463.918930   \n",
            "25%      10168.840645    11274.086022    12456.839645    14479.470360   \n",
            "50%      10298.085650    11598.522455    12696.452430    14495.021790   \n",
            "75%      10427.330655    11922.958888    12936.065215    14510.573220   \n",
            "max      10556.575660    12247.395320    13175.678000    14526.124650   \n",
            "\n",
            "       gdpPercap_1972  gdpPercap_1977  gdpPercap_1982  gdpPercap_1987  \\\n",
            "count         2.00000        2.000000        2.000000        2.000000   \n",
            "mean      16417.33338    17283.957605    18554.709840    20448.040160   \n",
            "std         525.09198     1485.263517     1304.328377     2037.668013   \n",
            "min       16046.03728    16233.717700    17632.410400    19007.191290   \n",
            "25%       16231.68533    16758.837652    18093.560120    19727.615725   \n",
            "50%       16417.33338    17283.957605    18554.709840    20448.040160   \n",
            "75%       16602.98143    17809.077558    19015.859560    21168.464595   \n",
            "max       16788.62948    18334.197510    19477.009280    21888.889030   \n",
            "\n",
            "       gdpPercap_1992  gdpPercap_1997  gdpPercap_2002  gdpPercap_2007  \n",
            "count        2.000000        2.000000        2.000000        2.000000  \n",
            "mean     20894.045885    24024.175170    26938.778040    29810.188275  \n",
            "std       3578.979883     4205.533703     5301.853680     6540.991104  \n",
            "min      18363.324940    21050.413770    23189.801350    25185.009110  \n",
            "25%      19628.685412    22537.294470    25064.289695    27497.598692  \n",
            "50%      20894.045885    24024.175170    26938.778040    29810.188275  \n",
            "75%      22159.406358    25511.055870    28813.266385    32122.777858  \n",
            "max      23424.766830    26997.936570    30687.754730    34435.367440  \n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "data.columns = years.astype(int)"
      ],
      "metadata": {
        "id": "K_DC4Uovy755"
      },
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "print(data.columns)"
      ],
      "metadata": {
        "id": "arldJ_DzzGKO",
        "outputId": "71e41c80-5e67-45f0-feb0-238e86d1940b",
        "colab": {
          "base_uri": "https://localhost:8080/"
        }
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Int64Index([1952, 1957, 1962, 1967, 1972, 1977, 1982, 1987, 1992, 1997, 2002,\n",
            "            2007],\n",
            "           dtype='int64')\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "data.plot()"
      ],
      "metadata": {
        "id": "Q1fhjt7bzLL7",
        "outputId": "185c9df9-1fa6-494b-be1c-7e5041a85fbf",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 316
        }
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "<matplotlib.axes._subplots.AxesSubplot at 0x7f8931c8fa50>"
            ]
          },
          "metadata": {},
          "execution_count": 58
        },
        {
          "output_type": "display_data",
          "data": {
            "text/plain": [
              "<Figure size 432x288 with 1 Axes>"
            ],
            "image/png": "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\n"
          },
          "metadata": {
            "needs_background": "light"
          }
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "The use of the [ ] indicates an index"
      ],
      "metadata": {
        "id": "8rGOfFk1zicP"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "data.loc['Australia'].plot()"
      ],
      "metadata": {
        "id": "8tSiP68RzYQ7",
        "outputId": "b3db3430-4bb9-41b5-da5d-db594a6655cd",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 302
        }
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "<matplotlib.axes._subplots.AxesSubplot at 0x7f8931bd0c10>"
            ]
          },
          "metadata": {},
          "execution_count": 60
        },
        {
          "output_type": "display_data",
          "data": {
            "text/plain": [
              "<Figure size 432x288 with 1 Axes>"
            ],
            "image/png": "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\n"
          },
          "metadata": {
            "needs_background": "light"
          }
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "data.T.plot()\n",
        "plt.ylabel('GDP/capita')\n",
        "plt.xlabel('Year')"
      ],
      "metadata": {
        "id": "1TYlyob80f7u",
        "outputId": "bb665959-45f8-4526-92b8-9f56feb45ba7",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 316
        }
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "Text(0.5, 0, 'Year')"
            ]
          },
          "metadata": {},
          "execution_count": 64
        },
        {
          "output_type": "display_data",
          "data": {
            "text/plain": [
              "<Figure size 432x288 with 1 Axes>"
            ],
            "image/png": "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\n"
          },
          "metadata": {
            "needs_background": "light"
          }
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "plt.style.use('ggplot')\n",
        "data.T.plot()\n",
        "plt.ylabel('GDP/capita')\n",
        "plt.xlabel('Year')"
      ],
      "metadata": {
        "id": "ZSAEkFID06e-",
        "outputId": "b4820f1c-a022-413f-e364-f92cc28a26cd",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 320
        }
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "Text(0.5, 0, 'Year')"
            ]
          },
          "metadata": {},
          "execution_count": 65
        },
        {
          "output_type": "display_data",
          "data": {
            "text/plain": [
              "<Figure size 432x288 with 1 Axes>"
            ],
            "image/png": "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\n"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "Why put stuff in parentheses?\n",
        "It can tell you a type of outcome based on what you are using."
      ],
      "metadata": {
        "id": "HqsjgLx_1K_V"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "plt.style.use('ggplot')\n",
        "data.T.plot(kind='bar')\n",
        "plt.ylabel('GDP/capita')\n",
        "plt.xlabel('Year')"
      ],
      "metadata": {
        "id": "R_Kbw5981NZw",
        "outputId": "ba0890f2-51dd-400c-94e0-cedf53d5648a",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 335
        }
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "Text(0.5, 0, 'Year')"
            ]
          },
          "metadata": {},
          "execution_count": 67
        },
        {
          "output_type": "display_data",
          "data": {
            "text/plain": [
              "<Figure size 432x288 with 1 Axes>"
            ],
            "image/png": "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HsibIrxjxw5Onz6NyWSiRo0ajBgxAoD69evTvn17XnzxRZycnHj66aftT+0bOnQos2bNIjc3ly5dutiL0IABA1iwYAFr1qyhUaNGhIaGOmJoIiLyfxxSUO6++27WrVt3Q/u1e04K0qdPH/r06VPgZwr6nJ+fH3PmzPlzHRURkWLTnfIiImIIFRQRETGECoqIiBhCBUVERAyh1RNFpEzJGf7Izd/cGOu4jsht0xGKiIgYoshHKDk5OWzZsoXDhw+TlpaW773p06cb3jERkTuN0WtrOVqRj1Def/99oqOjad68OSdPnqRt27akpqbSokWLkuyfiIiUE0UuKLt27WLy5Mn06NEDZ2dnevTowfjx4zl06FBJ9k9ERMqJIheU7Oxs+9LxlStXJisri7p163L69OmS6puIiJQjRb6GUrduXX766SeaNGmCv78/n3zyCe7u7jdd1VdERO4sRT5CGTx4sH2BxqeeeopTp06xd+9e+4KOIiJyZyvyEYqvr6/9+SW1a9fmtddeA+DixYsl0zMRESlXinyE8sILLxTYPm7cOMM6IyIi5VeRj1BsNtsNbRkZGfbTYCJSMenOdSmqQgvKc889B+TN8rr28zXp6el07NixZHomIiLlSqEFZfTo0dhsNubMmcPo0aPzvVe9evWbPltYRETuLIUWlObNmwOwcuVKXF1dS7xDIiJSPt2yoGzYsMH+GN6oqKibbvf4448b2ysRESl3bllQkpOTC/xZROROUN4Xa3S0WxaU4cOH238eOXJkiXdGRETKr9t6wNbZs2f54YcfsFgsmM1m2rdvT+3atQv93IULF1iyZAkXL17EZDIRFhZGjx49SE9PZ/78+Zw/f54aNWowbtw4PDw8sNlsrFq1iv379+Pq6srIkSPx9/cHYOvWrWzYsAGAPn36EBISAsDJkydZsmQJ2dnZBAUFMWTIEEwm023+c4iISHEV+SaS77//npdffpmff/4ZNzc3fvnlFyZMmMD339/8kPAaZ2dnnnzySebPn8+sWbPYsmULZ86cISoqilatWrFo0SJatWplv06zf/9+EhMTWbRoESNGjGDFihVA3jTl9evXM3v2bGbPns369etJT08HYPny5TzzzDMsWrSIxMRE4uPji/PvISIixVTkI5Q1a9YwadIk+6wvgCNHjvDWW29x//333/Kz3t7eeHt7A+Du7k7dunWx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KSkppdQrEeOpoIiUsCFDhrB//34OHDgAQHZ2Nu+88w6DBg3C29v7T+8/JyfnT+9DxAia5SXiAD/88AMffPABkZGRbNiwgdOnTxMeHs7q1as5c+YMNWrUYPDgwbRo0QKA7777js8//5zk5GQ8PT159NFH6datGwCHDh1i8eLFPPTQQ2zatImAgABGjx5dmsMTAXQfiohDtG/fnh07drBw4UKOHj3K3LlzmTBhAqNGjbI/lz0yMpIFCxbg6emJl5cXEyZMwM/PjyNHjjB79mwaN26Mv78/kLf0eHp6OkuXLi2RO6tFikOnvEQcZNiwYRw8eJDw8HB27NhBUFAQrVu3xsnJiYCAABo3bsy+ffuAvJvsatWqhclkonnz5gQEBNiXVgcwmUz069ePSpUqUbly5dIakkg+OkIRcZDq1avj6elJvXr12L17Nzt37mTv3r3293NycuynvPbv38/69ev5/fffsdlsZGVl0aBBA/u2np6eKiRS5qigiJQCHx8fHnjgAZ599tkb3rt69SqRkZGMGjWK4OBgXFxceP311/NtYzKZHNVVkSLTKS+RUvDAAw+wd+9e4uPjyc3NJTs7m0OHDpGcnIzVauXq1at4enri7Oycb4aYSFmmIxSRUuDr68vLL7/MBx98wMKFC3FycqJJkyYMHz4cd3d3hgwZwvz587l69Sr33nsvwcHBpd1lkUJp2rCIiBhCp7xERMQQKigiImIIFRQRETGECoqIiBhCBUVERAyhgiIiIoZQQREREUOooIiIiCFUUERExBD/D6YccUbWa/eMAAAAAElFTkSuQmCC\n"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "To get a dotted line & change the color use\n",
        "```\n",
        "--\n",
        "```\n",
        "and the first letter of the color you want to use"
      ],
      "metadata": {
        "id": "ghMEcpj31iFw"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "plt.plot(time,response, 'g--')"
      ],
      "metadata": {
        "id": "MT22jkox1aZq",
        "outputId": "7377daa5-23d5-4b06-b78d-b6799cf88ba9",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 302
        }
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "[<matplotlib.lines.Line2D at 0x7f893176a690>]"
            ]
          },
          "metadata": {},
          "execution_count": 68
        },
        {
          "output_type": "display_data",
          "data": {
            "text/plain": [
              "<Figure size 432x288 with 1 Axes>"
            ],
            "image/png": "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\n"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "To create a dot plot use:\n",
        "```\n",
        "plt.plot(time,response, 'o')\n",
        "```"
      ],
      "metadata": {
        "id": "qMas6ioH1_Tb"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "plt.plot(time,response, 'o--')"
      ],
      "metadata": {
        "id": "tSTbxtWL1tMn",
        "outputId": "a2a0eba1-cea9-4ff3-b1aa-f56afb4ec4a7",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 302
        }
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "[<matplotlib.lines.Line2D at 0x7f8931be8650>]"
            ]
          },
          "metadata": {},
          "execution_count": 70
        },
        {
          "output_type": "display_data",
          "data": {
            "text/plain": [
              "<Figure size 432x288 with 1 Axes>"
            ],
            "image/png": "iVBORw0KGgoAAAANSUhEUgAAAXAAAAD4CAYAAAD1jb0+AAAABHNCSVQICAgIfAhkiAAAAAlwSFlzAAALEgAACxIB0t1+/AAAADh0RVh0U29mdHdhcmUAbWF0cGxvdGxpYiB2ZXJzaW9uMy4yLjIsIGh0dHA6Ly9tYXRwbG90bGliLm9yZy+WH4yJAAAgAElEQVR4nO3deXhV1d328e/aJ0AMQwbCYAIIQURBFDWUKNAECGodoX1LW5Q+lvZpq4gPtlrRWrCPUqKASbGx1LaixbdS+1apUsdIE6sUjQyCoAwtjqgQEkLIQMjZ6/3jYCyQkIFzss9wf66rVz07Z2ffiwO/rKy911rGWmsREZGI43gdQERE2kcFXEQkQqmAi4hEKBVwEZEIpQIuIhKhVMBFRCJUXEdfcPfu3e06LzU1lbKysiCnCW9qc2xQm6PfybY3LS2tyePqgYuIRCgVcBGRCKUCLiISoVTARUQilAq4iEiEatVTKKtWrWL16tUYY+jfvz833HAD+/fvp6CggKqqKjIyMpg1axZxcR3+UItIxHLXFmOfWs5nFWWQnIqZMh0nK8frWBJBWuyBl5eX89xzz5GXl8fixYtxXZc1a9bw2GOPcfnll/PAAw/QtWtXVq9e3RF5RaKCu7YYu7wQyveCtVC+F7u8EHdtsdfRJIK0agjFdV3q6+vx+/3U19eTlJTEli1byMrKAiAnJ4fS0tKQBhWJJvap5VB/6OiD9YcCx0VaqcUxj5SUFK688kquv/56OnfuzLnnnktGRgYJCQn4fL7G95SXlzd5flFREUVFRQDk5eWRmpravqBxce0+N1KpzdHrs4pmJnVUlMVE+2Plc/5cqNrbYgE/ePAgpaWlFBYWkpCQwP3338/GjRtbfYHc3Fxyc3MbX7d3NlKszdwCtTmqJacGhk+aOB4L7Y+Zz/kIz2Zibt68md69e9OjRw/i4uIYPXo027Zto6amBr/fDwTGyVNSUtodTiTmjL8cOnU6/nhqH+yRf1ciLWmxgKemprJjxw4OHTqEtZbNmzfTr18/hg8fztq1awEoLi4mMzMz5GFFosau7YAT6IkbAym9YORoTJ80cPR0r7ROi0MoQ4YMISsri9tuuw2fz8fAgQPJzc3l/PPPp6CggBUrVjBo0CAmTJjQEXlFIp79bDds+CfmK/8HZ8r0o369ttZijMHu/gAOHcIMGuJxWglnrXpwe+rUqUydOvWoY3369GHBggUhCSUSzeyLK8EXh5lwxXFfM8YA4K74LezYivn2jTgXju/oiBIh9LuaSAeylRXYNS9jLpqASUxu9n3Of98Cg8/EPpyP++eHNS4uTVIBF+lIH/wLOnXCTJp8wreZ7ok4s3+OGX859sWVuEt+jq2p7qCQEik0912kA5kRmTgLH8V06dLye+PiMNN+gNt/EPaNV6Bz5w5IKJFEBVykg9iKfZCU0qri/Z+ccRdjx04K3NysroJ/b8OM0FNfoiEUkQ5hGw7jLrgV+9iv23X+5zc37ao/4S75X9xnVmBdN5gRJQKpBy7SAewb/4CKMszI0Sf1fcxXvw0Hq7BP/xH70S6c78zGxJ8SpJQSadQDFwkxay32hSch/TQ4+/yT+l6mU2fMjNmYqd+FDa/j5v0EW/ZZkJJKpFEBFwm1t9fB7g8wl361cSjkZBhjcCZdjTN7XmAWp25uxiwVcJEQc18tgpRUTOa4oH5fM+w8nJ8VYHokY/1+7LrXsNYG9RoS3jQGLhJizvd+DHs+wYRgxypzZN0Uu+Zl7B9+hRkzEa65AdPUQlkSdVTARULIum6gmKYPCOl1zJhcKC/DrlqB/eQjnOtvxyRphdBopyEUkRCxn36Ee8f3sTvfCfm1jOPgXD0N54dz4OP3cef/CLtrR8ivK95SARcJEfviSqisgN59O+ya5oKLcObcCwndtCxtDNAnLBICtrIC+8/VmDETMT2aX7QqFEy/QTjzlmBOGxzIsv6fWgwrSqmAi4SAffkZ8PsxF5940apQaby5+e9tuL9egPvLu7AHD3iSRUJHBVwkyGxdDbb4OTj/Qkzvpvcy7CgmYyjmuptgxxbcX9yC/fh9T/NIcKmAiwRb53ic7/4I54pvep0EAGdMLs4tv4D6+sB6LBvWeh1JgkQFXCTIjONgzh2F6TfQ6yiNzOAzce5cDOmnYRsavI4jQaICLhJEbumruE/+AXu43usoxzFJPXFuy8MZNRYAu2UDtq7G41RyMlTARYLEum5gIs3mNyEuPGdCGscHgD2wH/fB+bgLfoLd84nHqaS9VMBFgmXzkUWrLgnOolWhZHok4cy8E/aX487/MXbrBq8jSTuogIsEifvCXyClFyZzrNdRWsUMG4nz08WQ3BO34Oe4RX/1OpK0kQq4SBDYf70LO7ZiJl0dkkWrQsX0PhVnzn0w8ktwsMrrONJGkfM3TSScJXTFXDgeM3aS10nazMSfElhD5Qj73g5ITMEk9/QwlbRGiwV89+7d5OfnN77es2cPU6dOJTs7m/z8fPbu3UuvXr24+eab6datW0jDioQrc2p/zIybvY7Rbo0zN/1+3IcWQv2hwIqGg8/0OJmcSItDKGlpaSxcuJCFCxdy77330rlzZ770pS+xcuVKRowYwZIlSxgxYgQrV67siLwiYcdd8zL2kw+9jhEUxufDmflT6NwFd9EduK8VeR1JTqBNY+CbN2+mb9++9OrVi9LSUrKzswHIzs6mtLQ0JAFFwpndX45dXohdvcrrKEFj0k8L3NwcMhz7yBLcxx/SYlhhqk1j4K+99hpjxowBoLKykuTkwCprSUlJVFZWNnlOUVERRUWBn+J5eXmkpqa2L2hcXLvPjVRqc/ireu7P1LguKVO/Q1w0/d1OTcXe/QAHHy3E/+nHJPbq1TjMEgxh2eYQClV7W13AGxoaWLduHdOmTTvua8aYZp97zc3NJTc3t/F1WVlZO2JCampqu8+NVGpzeLO1NbjPPYk5/yL2d4qHaPy7fdU1WL+ffeXl2H17ofYgpt+gk/62Yd3mEDjZ9qalNb0oWqt/pG7YsIFBgwaRlJQEQGJiIhUVFQBUVFTQo0ePdocTiUT2lRegthpzyRSvo4SU8QVmb7p/XBqYubnuNY8TyedaXcD/c/gEIDMzk5KSEgBKSkoYNWpU8NOJhLPDh+CcUZiBQ7xO0iGc6TOh30DcpffirnwM67peR4p5rSrgdXV1bNq0idGjRzcemzx5Mps2beKmm25i8+bNTJ7szcL1Il5xrvgmzo13eh2jw5ikFJxbfoEZk4v92xO4D/4CW6vFsLzUqjHw+Ph4Hn744aOOde/enblz54YklEg4s64Lu7ZDxtCwX/Mk2EynTvBfs2BABvbVlyC2mh92NJVepK02v4mb9xPY/KbXSTxhjMGZcAXOHYsx8QnYQ4ew29/2OlZMUgEXaSP3+SehZ28Ydp7XUTz1+Zov9m8rcBfdifviU1hrPU4VW1TARdrA7nwHdkbeolWhZC6bCudlYf+8DPtwPrb+kNeRYoYKuEgbuC88CV27R+SiVaESWAzrNszV12DXFuPedzu2PHae8faSuhAirWRrquFf72LGX4bpEu91nLBijMFc8Q1sv4G4K34Lfu272RFUwEVaySR0xcn7HbhaF6Q5ZuRonLMvwMTFBcbD39mIifF7BaGkIRSRVrCH6rCuH9O5CyY+wes4Ya3x5ubrJbj583D/uBTboB55KKiAi7SCfWYF7twbw3K3+XBlRo3DXDwF+/dncfPnYquaXvBO2k9DKCItsDXV2Feex5x9AaZTZ6/jRAzj82G+/h3c/gOxj/4Kd/6PYdzF8MoLfFZRBsmpmCnTcbJyvI4asdQDF2mB/ccLUFuDueSrXkeJSE7WeJzb8qCuFlb9Ccr3grVQvhe7vBB3bbHXESOWCrjICdjDh7FFT8NZ52JOG+x1nIhlBg6BLl2g4fDRX6g/hH1quSeZooEKuMgJ2PVrYH85zqXqfZ+08n3NHNcz4+2lMXCREzCjxmK6doezRnodJfKlpAaGT5o6Lu2iHrjICRjHhzn7/JhbdTAUzJTp0LnL8V/oP0hrqLSTCrhIM/yF83H//jevY0QNJysHM30mpPQCYwL/P3QEvPUGvLvJ63gRSUMoIk2wO7fCxtfhzHO9jhJVnKwcyMpp3CPSWgtvr8ecpT/n9lAPXKQJ7vNPQrfumLG5Lb9Z2s0YgxlxAQD2/Z24T/xeW7W1gQq4yDHsJx/CW29gxl+uRas6kH17Pfalv2IffQCr9WZaRUMoIsewLzwJnTtjxl/udZSYYi77Orgu9uk/QkMDzJiN8fm8jhXWVMBFjmHGXgyDz8J0T/Q6SkwxxmCu/CauzxeY3ONvgO/9WBtnnID+ZESOYU4/C3P6WV7HiFnOZV/HjeuE3bYZgx4vPBGNgYscYWuqcR9/CLuvickm0qGciyfjzPwpJq4T9uABrQLZDBVwkSPsK89jV6+Cgwe8jiKAcRys3x9YU/xX92APaa/NY6mAi/D5olXPaNGqMGN8PsyEy+Gdt3Af+F/soTqvI4WVVo2BV1dXs3TpUj788EOMMVx//fWkpaWRn5/P3r176dWrFzfffDPdunULdV6RkLBr/w6V5TgzZnsdRY7hjMnF9cVhHy7ALbgL56a5mFO0KxK0sge+bNkyRo4cSUFBAQsXLiQ9PZ2VK1cyYsQIlixZwogRI1i5cmWos4qEhHVd7ItPwYAM0IzAsORk5eB8/xb497vY//trr+OEjRYLeE1NDe+88w4TJkwAIC4ujq5du1JaWkp2djYA2dnZlJaWhjapSKjU12GGDMe57OtatCqMmcyxODfeifnqf3kdJWy0OISyZ88eevTowYMPPsj7779PRkYG1113HZWVlSQnJwOQlJREZWXT+90VFRVRVFQEQF5eHqmp7Vs6Mi4urt3nRiq1uQP96K6Ov+YR+pzbYPylAFi/n+onlpFw2ddwEpODnC74QvUZt1jA/X4/u3btYsaMGQwZMoRly5YdN1xijGm255Kbm0tu7hfrSZSVtW/x9s8Xv4klanPo2Y/eg0N1mMFndtg1j6XPue3sR+/hPvUY1f94CefH92DCvIifbHvT0tKaPN7iEErPnj3p2bMnQ4YMASArK4tdu3aRmJhIRUUFABUVFfTo0aPd4US84q58DPdXd+s54whj+g3EuWku7NuDu+gObEUzu/1EuRYLeFJSEj179mT37t0AbN68mX79+pGZmUlJSQkAJSUljBo1KrRJRYLMfvzBkUWrrtBu8xHInHkOzuyfw/5y3IW3x+QErFY9RjhjxgyWLFlCQ0MDvXv35oYbbsBaS35+PqtXr258jFAkktgXn9KiVRHODBmGM/vnuEvzAtu19ezldaQO1aoCPnDgQPLy8o47Pnfu3KAHEukItrwM+3oJJvtSTHcN/0UyM/hMnF881PhblK2rwcTHxnPimokpsWn3B5DQFTPpaq+TSBB8XrzdV1/C/dkN2E8+8jhRx1ABl5hkzj4f575lmNQ+XkeRIDKDhoLrBsbEP37f6zghpwIuMcfu+QTrulpnOgqZ9AE4t/4CfL7A0ykf/NvrSCGlAi4xxR6ux71vDvaxB72OIiFi+vYLFPHOXXAX34mtanqSYTRQF0Riil1bDJUVmFHjvI4iIWR6p+HcugC7dUNU76ykHrjEDOu62BeeggGD4cxzvI4jIWZS++B8+cjU+3+9i92+xeNEwacCLrHjrTfgs48xl35Ni1bFEGst7p9+h/vLu7DvvOV1nKBSAZeY4b5eDL36Ys6/0Oso0oGMMTg3/hRS++A+cDf27fVeRwoaFXCJGc5/34oz+y6Mz+d1FOlgpkcyzi3zoU86buE92LeiY/lrFXCJCbahIbA9V++mV3WT6Ge6J+Lccg+kD8S+UeJ1nKBQAZeoZz9+H3fOd7E7tnodRTxmunYPLD/7nf8BAj/YI5kKuEQ9+8JTUFsDp/bzOoqEAXNKAiauE7aqEveem3HX/t3rSO2mAi5RzZbvxb5Rghl3MaabFq2S/9C5C3RPDGyW/OpLXqdpFxVwiWq26GmwFpN7lddRJMyYLvE4s34GZ43EPvoAbsnzXkdqMxVwiVq2phr7youYzHFatEqaZDp3CTxiOCIT+9iDuP+MrOEUTaWX6HVKAs6sOyHM90sUb5lOnXFuuB37l0cxw0Z6HadN1AOXqGWMwQwdgemrm5dyYiauE843vodJTMY2NGDXrfE6UquogEtUctesxn38IW1WLG1mX30Jd2ke7l//iLXW6zgnpCEUiTrW9WP/9gQceVxMpC3Mly+G93ZgV60A/2GY8u2wXTtHBVyiz8bXYc9unB/8JGz/4Un4Mo4Pvn0jxMVhn/sLHG6AqTPC8u+ShlAkqlhrcZ9/Enr1BS1aJe1kHAdzzfWYiVdi//EilH3mdaQmqQcu0WXHFti1HXPNDwM9KZF2MsbAN76HmXAFpldfINBBCKeeuHrgEl2SUjA5l2Eumuh1EokCxhhM71MBcIv+in1kCdb1e5zqC+qBS1QxvdMw1/zQ6xgSjepqsWtehoYGmDE7LJYlblUBnzlzJvHx8TiOg8/nIy8vj4MHD5Kfn8/evXvp1asXN998M926dQt1XpFmucXPYgYNxZw22OsoEoWcK76J6+uEffJRrP8wzvduwcR52wdu9dXnzZtHjx5fLAa0cuVKRowYweTJk1m5ciUrV67k2muvDUlIkZbYfXuxK34LOZepgEvIOF/5Gm5cHPaJ3+P678W54Q5Px8TbPQZeWlpKdnY2ANnZ2ZSWRscOFxKZGhetmnS111EkyjmTrsZM+wHmrHM9v6HZ6h74/PnzAZg0aRK5ublUVlaSnBxYYyIpKYnKysomzysqKqKoqAiAvLw8UlNT2xc0Lq7d50Yqtbl13IMHKHv1ReLHTSJx6LAQJQsdfc4R6Ov/1fifh//1LnH9BmK6xDf79lC1t1UF/O677yYlJYXKykruuece0tKO3pbKGNPsT6Lc3Fxyc3MbX5eVlbUraGpqarvPjVRqc+u4f3sCW1dLfc5lEfnnpc85ctmDB3B/diMMGIxz452Y+FOafN/JtvfYmvu5Vg2hpKSkAJCYmMioUaPYuXMniYmJVFRUAFBRUXHU+LhIh3J8mFHjMP0GeZ1EYozp1gNzzfWwYwvuL+/C1tZ06PVbLOB1dXXU1tY2/vemTZsYMGAAmZmZlJQENgYtKSlh1KhRoU0q0gznK1/D+f6tXseQGOWMzg78/du1HTd/Lrb6YIddu8UhlMrKShYtWgSA3+9n7NixjBw5ksGDB5Ofn8/q1asbHyMU6UjW9cO7m+CskZ7fTJLYZi4Yg+Pz4S69D/vy05irpnXMdW0Hr5e4e/fudp0XLWNmbaE2n5hdtwZ3aR7OrJ9hzonc3wD1OUcP+94O6J9x3CQfT8fARcJNYNGqv0DvU+Hs872OIwKAGTgE4/Nh9+/D/6t7sPvLQ3o9TaWXyLT9bXhvB+baG7RolYSfss/g3U24d88Gx8dnleWQnIqZMh0nKydol1EPXCKS+/yT0D0Rc+F4r6OIHMecPgwmXQ0H9sP+fWAtlO/FLi/EXVsctOuogEvEsTXVsPt9zMQrMZ27eB1HpGlrVh9/rP4Q9qnlQbuEhlAk4piErjjzHwJ/+CzrKXKc8mZuWjZ3vB3UA5eIYmuqsQ2HMXFxmC7qfUsYS2lm6nxzx9tBBVwiin3mcdw7r9du8xL2zJTpcOwQX+cugeNBoiEUiRi2ugr7jxcx512I6dTZ6zgiJ+Rk5eBCYMy7oiwkT6GogEvEsMXPwaE6zCVTvI4i0ipOVg5k5YRs4pKGUCQi2PpD2JefgRGZmH4DvY4jEhZUwCUi2A1roaoS55Kveh1FJGxoCEUigvnSlzHJqTAk8jZsEAkVFXAJe9bawGqDZwz3OopIWNEQioQ1ay1u/lzcl/7qdRSRsKMCLuFt22Z4563jn6cVERVwCW/uC0cWrbpogtdRRMKOCriELfvhLnh7fWDRKk3cETmOCriELfvCk9DlFEzOZV5HEQlLegpFwpa5eEpg4k7Xbl5HEQlLKuAStsyADMyADK9jiIQtDaFI2LEHD+A+8kvs3k+9jiIS1lTAJezY4mexr70M9Ye8jiIS1lTAJazYQ4ewL68KjH2nn+Z1HJGwpgIuYaX273+DgwdwLtWiVSItafVNTNd1mTNnDikpKcyZM4c9e/ZQUFBAVVUVGRkZzJo1i7g43ROV9nHXFmOfWk5V+V6Ii8MtL8PndSiRMNfqHvizzz5Lenp64+vHHnuMyy+/nAceeICuXbuyenUTOzCLtIK7thi7vBDK9wYONDTA8kLctcWe5hIJd60q4Pv27WP9+vVMnDgRCCwwtGXLFrKysgDIycmhtLQ0dCklqtmnlh9/w7L+UOC4iDSrVWMejzzyCNdeey21tbUAVFVVkZCQgM8X+CU3JSWF8vLyJs8tKiqiqKgIgLy8PFJT27cjc1xcXLvPjVSx0ubPypvZaqqiLCbaHyuf83+KtTaHqr0tFvB169aRmJhIRkYGW7ZsafMFcnNzyc3NbXzd3n3hQrWnXDiLhTbbzevAALaJLyZHf/shNj7nY8Vam0+2vWlpaU0eb7GAb9u2jTfffJMNGzZQX19PbW0tjzzyCDU1Nfj9fnw+H+Xl5aSkpLQ7nMQeay32hSexT/4BkntC1QE4XP/FGzp3wUyZ7l1AkQjQYgGfNm0a06ZNA2DLli0888wz3HTTTdx///2sXbuWMWPGUFxcTGZmZsjDSvSwb7yC/cujmMyxmOtuwm5YGxjzriiD5FTMlOmBHb1FpFntfu7vmmuuoaCggBUrVjBo0CAmTNB6zdKyz7dHM6PGgjGYUeMCr7NyICsn5n61FjkZbSrgw4cPZ/jwwL6Effr0YcGCBSEJJdHJbt+C+/hDOP8zF5PUE/OlL3sdSSSiaeaNdAi35Hns47+B1L5wSGuciASDCriElG04jF3xW2zJ8zAiE+d7P8IkaH1vkWBQAZeQss+swJY8j/nK1zCTr8U4miAvEiwq4BISjTcrL/kqZuAQzHlZXkcSiTpajVCCzn29BHfRHdj6Q5iErireIiGiAi5BY10/7l8exf5uMVirDRlEQkxDKBIUtuYg7m8Xw9vrMNmXYr7535i4Tl7HEolqKuASFO6yX8I7GzHXXI+T8xWv44jEBBVwOSmf36x0vnYdTJqMOWO415FEYobGwKVdrLW4z/4Z+3BBoIj3TVfxFulgKuDSZvZQHfa3iwKLT7l+8Dd4HUkkJmkIRdrE7tuDWzgfPnoP83+uw1w8BWOM17FEYpIKuLSadf24+fPgwH6cWXMxIy7wOpJITFMBlxZZG9guxzg+nOk3QGIKpm96C2eJSKipgMsJ2YbD2D/+BvqkBabFDx3hdSQROUI3MaVZ9kAF7uI7sf94EWprvI4jIsdQD1yaZN/bgfvgAqg+gPn+rTijxnkdSUSOoQIux7FVlbiLfgrdeuDcdh9mQIbXkUSkCSrg0qhxCdjuiTjf+R8442xM90SvY4lIMzQGLgDY6oO4S/4Xu6kUAHPBGBVvkTCnAi7Y3R/g/uLH8M5b2IMHvI4jIq2kIZQYZ996A/d3i6FzF5xb7sGcPszrSCLSSirgMczu2hGYFj9gMM4Nt2NSenkdSUTaQAU8Bn1+s5KBp2Omz8SMzsZ07uJ1LBFpoxYLeH19PfPmzaOhoQG/309WVhZTp05lz549FBQUUFVVRUZGBrNmzSIuTj8Pwp3d+ynusgKc6TMxp/bHjLvY60gi0k4tVtxOnToxb9484uPjaWhoYO7cuYwcOZJVq1Zx+eWXM2bMGB566CFWr17NxRerGIQz++4m3N/cC64LlRVwan+vI4nISWjxKRRjDPHx8QD4/X78fj/GGLZs2UJWVmC38ZycHEpLS0ObVNrNWou7ehVu/lzonoRzx2LMmed4HUtETlKrxjxc1+W2227j008/5ZJLLqFPnz4kJCTg8/kASElJoby8vMlzi4qKKCoqAiAvL4/U1NT2BY2La/e5kSpYba5d/SwHHn+ILqPG0mP2PJyErkFIFxr6nGNDrLU5VO1tVQF3HIeFCxdSXV3NokWL2L17d6svkJubS25ubuPrsrKytqcEUlNT231upApWm+1Z52GuuZ7DX76E8ppaqKkNQrrQ0OccG2KtzSfb3rS0tCaPt2kiT9euXRk+fDjbt2+npqYGv98PQHl5OSkpKe0OJ8Fnd23Hv+in2OqDmE6dcHK+gnE0b0skmrT4L/rAgQNUV1cDgSdSNm3aRHp6OsOHD2ft2rUAFBcXk5mZGdqk0mrumtW4990OZZ9B1X6v44hIiLQ4hFJRUUFhYSGu62Kt5cILL+SCCy6gX79+FBQUsGLFCgYNGsSECRM6Iq+cgPX7sf9vGbboaRg6AucHt2G69/A6loiESIsF/LTTTuO+++477nifPn1YsGBBSEJJ+9gn/4Atehoz4QrM12dg9Fy+SFTTv/AoYi6eDP0H4mSN9zqKiHQA3dWKcHb9P/H/egHW78ckJqt4i8QQ9cAjlHVd7Ko/YZ95HAYOgdpq6KbxbpFYogIegWxdDe7DBbBhLebC8YEFqTp19jqWiHQwFfAI5P7mPtiyEfON72ImXhVYWVBEYo4KeARyrr4GJk3GDBvpdRQR8ZAKeASw1mJffhoqynG+/h3MwCFeRxKRMKACHobctcXYp5bzWUUZJPeElN6wcyuclxV42uTIImIiEttUwMOMu7YYu7wQ6g8FDpSXBf53/oWBmZVaz0REjlA1CDP2qeVfFO//9N5OFW8ROYp64GHAWgt7P8Fu2Qjle5t+U3nsLL0pIq2jAu4h+8mH2Jf+it26EfbtCRx0nMCWZ8dKiZ3F70WkdVTAO4htOAz/2obdugEz/DzMGWdDXS32zVdh6DmYS76KGT4S99/b4T/HwAE6d8FMme5deBEJSyrgIWQbDmOLnwv0sLe/DYfqAj3shG6BAn7a6Tj3P3bUqoG+3mm4HBkLryiD5FTMlOk4WTmetUNEwpMKeBDZAxXYrW9Bw2GcsZPAF4d9/i8Qn4C5aEJg4s0ZIzBH9qQ0jhMo6MdwsnIgKyfmtp0SkbZRAT9JdudW7IbXA73sj3YFDvYfBGMnYYzB+Xkhpms3b0OKSFRSAW8D65+Tvt8AAAcFSURBVLrw0XvY7ZsxE67EOA72n3/HvvYynH4WZsr0QC97QEbjOSreIhIqKuAtsFWV2E1vwtaN2Hc2QlUlAGbYeZA2AHP1NMzU72K6xHucVERijQr4MWxdLWx7G07th+l9Kuzajn3kl9AjCTP8PDhrJGbYuZikngCYHskeJxaRWBXzBdy6Lry/E7tlQ6CH/a9t4G/AXDUNc+U3Yeg5OPN+CekDtWyriISVmCzgdu+ncPAAZtAZ4PfjLroD6uthQAYm96pAT/v0swAwXbpAv0EeJxYROV5MFHBbcxDe3YTdujHwtMjeT+G00/HdeT+mUyecWXMh/TRM90Svo4qItFpUFnDb0AAf/jvQwwbcR5bAhrXQ5RQYejZm4pVHbYZgzjzHq6giIu0WFQXcWgufffxFD3vbZqirxbn3YUxKKs6lX4PcqyBjKCauk9dxRUSCosUCXlZWRmFhIfv378cYQ25uLpdddhkHDx4kPz+fvXv30qtXL26++Wa6dQv+M89Hb27wxbRyW3UAfD5MQlfsG69gf7c4cEKvvpjR2YEedtfuAJiMoUHPJSLiNWOttSd6Q0VFBRUVFWRkZFBbW8ucOXO49dZbKS4uplu3bkyePJmVK1dy8OBBrr322hYvuHv37laHO25zAwDHB0k9oWIvZtoPcXK+gq2swG58HTNsJKZX31Z//3AXi1Pp1ebYEGttPtn2pqWlNXm8xR0CkpOTycgIzCw85ZRTSE9Pp7y8nNLSUrKzswHIzs6mtLS03eGa0+TmBq4fDpRjrvoWZujZAJjEZJzsS6OqeIuItKRNY+B79uxh165dnH766VRWVpKcHJjEkpSURGVlZZPnFBUVUVRUBEBeXh6pqa1f1/qzimZ+Yvn99L7uxrZEj0hxcXFt+vOKBmpzbIi1Noeqva0u4HV1dSxevJjrrruOhISEo75mjGl2kktubi65ubmNr9v0a0RyatM71CTHxq9fsfZrJqjNsSLW2uzZEApAQ0MDixcvZty4cYwePRqAxMREKioqgMA4eY8ePdodrjlmynTo3OXog9rcQEQEaEUBt9aydOlS0tPTueKKKxqPZ2ZmUlJSAkBJSQmjRo0KfrisHMz0mZDSC4yBlF6Y6TO1uYGICK0YQtm2bRuvvPIKAwYM4NZbbwXgW9/6FpMnTyY/P5/Vq1c3PkYYCtrcQESkaS0W8DPPPJMnnniiya/NnTs36IFERKR1WjUGLiIi4UcFXEQkQqmAi4hEKBVwEZEI1eJaKCIiEp4ipgc+Z84cryN0OLU5NqjN0S9U7Y2YAi4iIkdTARcRiVC+u+666y6vQ7TW58vaxhK1OTaozdEvFO3VTUwRkQilIRQRkQilAi4iEqEiYlf6jRs3smzZMlzXZeLEiUyePNnrSCH14IMPsn79ehITE1m8eLHXcUKuuY2zo1l9fT3z5s2joaEBv99PVlYWU6dO9TpWh3Bdlzlz5pCSkhITjxPOnDmT+Ph4HMfB5/ORl5cXtO8d9gXcdV1+//vfc+edd9KzZ09uv/12MjMz6devn9fRQiYnJ4dLL72UwsJCr6N0CJ/Px/Tp04/aOPucc86J6s+4U6dOzJs3j/j4eBoaGpg7dy4jR47kjDPO8DpayD377LOkp6dTW1vrdZQOM2/evJBsehP2Qyg7d+6kb9++9OnTh7i4OC666KKQbKAcToYNG0a3bt28jtFhmts4O5oZY4iPjwfA7/fj9/ub3ZYwmuzbt4/169czceJEr6NEhbDvgZeXl9OzZ8/G1z179mTHjh0eJpJQ+s+Ns6Od67rcdtttfPrpp1xyySUMGTLE60gh98gjj3DttdfGVO8bYP78+QBMmjTpqD2CT1bYF3CJHSfaODsaOY7DwoULqa6uZtGiRXzwwQcMGDDA61ghs27dOhITE8nIyGDLli1ex+kwd999NykpKVRWVnLPPfeQlpbGsGHDgvK9w76Ap6SksG/fvsbX+/btIyUlxcNEEgpNbZwdK7p27crw4cPZuHFjVBfwbdu28eabb7Jhwwbq6+upra1lyZIl3HTTTV5HC6nP61ViYiKjRo1i586dQSvgYT8GPnjwYD755BP27NlDQ0MDa9asITMz0+tYEkTNbZwdzQ4cOEB1dTUQeCJl06ZNpKene5wqtKZNm8bSpUspLCxk9uzZnH322VFfvOvq6hqHi+rq6ti0aVNQf0iHfQ/c5/MxY8YM5s+fj+u6jB8/nv79+3sdK6QKCgrYunUrVVVV/PCHP2Tq1KlMmDDB61gh09zG2eeff77HyUKnoqKCwsJCXNfFWsuFF17IBRdc4HUsCbLKykoWLVoEBG5Wjx07lpEjRwbt+2sqvYhIhAr7IRQREWmaCriISIRSARcRiVAq4CIiEUoFXEQkQqmAi4hEKBVwEZEI9f8B0MsGNVUNH4YAAAAASUVORK5CYII=\n"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "gdp_australia = data.loc['Australia']\n",
        "gdp_nz = data.loc['New Zealand']\n",
        "\n",
        "plt.plot(years, gdp_australia, 'g--', label= 'Australia')\n",
        "plt.plot(years, gdp_nz, 'o-', label= 'New Zealand')\n",
        "\n",
        "plt.legend(loc='lower right')\n",
        "plt.ylabel('GDP/capita')\n",
        "plt.xlabel('Year')"
      ],
      "metadata": {
        "id": "MlPqQtXN2Tk3",
        "outputId": "51084a83-1d2c-474e-f190-f6d82ccf99bb",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 320
        }
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "Text(0.5, 0, 'Year')"
            ]
          },
          "metadata": {},
          "execution_count": 83
        },
        {
          "output_type": "display_data",
          "data": {
            "text/plain": [
              "<Figure size 432x288 with 1 Axes>"
            ],
            "image/png": "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\n"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "plt.scatter(gdp_australia,gdp_nz)"
      ],
      "metadata": {
        "id": "pl7eaDsG3Uu0",
        "outputId": "01a822e4-4143-49cf-ca3b-3b8e196cadcf",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 302
        }
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "<matplotlib.collections.PathCollection at 0x7f89314fbad0>"
            ]
          },
          "metadata": {},
          "execution_count": 82
        },
        {
          "output_type": "display_data",
          "data": {
            "text/plain": [
              "<Figure size 432x288 with 1 Axes>"
            ],
            "image/png": "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BofDwcaNG8nKygLA7/dTWVlJKBRi2bJl4duf29raKCkpobu7m9TUVLZu3YrTOfa/Ju3t7ZSVldHV1YVhGHi9Xp599llbHPOhsk/0497T08M//MM/0NvbS19fH4sWLWLNmjVD7uvdu3fZt28fly9fZtq0abz88svMmDEDiPzvYywNlbusrIzz588TFxcHwIsvvshjjz02er/r5kPq3Llz5qVLl8wf//jH4bHDhw+bVVVVpmmaZlVVlXn48GHTNE3z7Nmz5p49e8xQKGReuHDB3Llzp2maptnd3W2++OKLZnd394D/Nk3T3LFjh3nhwix5EEAAAATfSURBVAUzFAqZe/bsMevr60c54eAGy/3v//7v5vHjx+9b9rPPPjNfeeUVs6enx7x+/br50ksvmX19fWZfX5/50ksvma2trebdu3fNV155xfzss89M0zTNoqIi87e//a1pmqb53nvvmSdOnBidYBYCgYB56dIl0zRN8/bt22ZBQYH52Wef2eKYD5V9oh/3UChk3rlzxzRN07x79665c+dO88KFC0Pu669//WvzvffeM03TNH/729+a77zzjmma0f19jKWhcu/bt8/87//+7/uWH63f9Yd2GsquT8MdLPdQfD4fOTk5xMbGMmPGDFJSUmhubqa5uZmUlBRmzpyJ0+kkJycHn8+HaZqcO3eORYsWAf2Ppx8vuRMSEsL/WpoyZQqzZ88mEAjY4pgPlX0oE+W4G4bBt771LQD6+vro6+vDMIwh9/XMmTPhfzkvWrSITz/9FNM0I/77GGtD5R7KaP2uP7RlMZixehrueHDixAleeeUVysvLw49ViTRfd3c3cXFxxMTEDFh+vGlra+PKlSukpaXZ7ph/OTtM/OMeCoXYvn07mzZtYsGCBcycOXPIff1yvpiYGOLi4uju7n4oj/lXc6enpwPwwQcf8Morr/Cv//qv3L17Fxi93/UJVRZfNppPwx1r3//+93n33Xf553/+ZxISEvi3f/u3sd6lEfP5559TVFTEhg0bwnO390z0Y/7V7HY47g6Hg7feeov9+/dz6dIlWlpaxnqXRsVXc//v//4vP/jBDygpKeHNN98kGAxy/Pjx0d2nUf20EWbXp+FOnz4dh8OBw+Fg2bJlXLp0CSDifNOmTeP27dv09fUNWH686O3tpaioiMWLF7Nw4ULAPsd8sOx2Oe4AU6dOZf78+TQ1NQ25r1/O19fXx+3bt5k2bdpDe8zhz7n9fj8JCQkYhkFsbCxLly6lubkZGL3f9QlVFveehgvc9zTc2tpaTNOkqalpwNNwGxsbCQaDBINBGhsbycrKIiEhIfw0XNM0qa2txePxjGW0r3Xvf5YA//M//8Ojjz4K9Oeuq6vj7t27tLW1ce3aNdLS0pg7dy7Xrl2jra2N3t5e6urq8Hg8GIbB/PnzOX36NNB/J8V4yW2aJvv372f27Nk8//zz4XE7HPOhsk/04/6nP/2JW7duAf13CH3yySfMnj17yH3967/+a06ePAnA6dOnmT9/PoZhRPz3MdaGyn3veN+7DvPl4z0av+sP7Te4S0pKOH/+PN3d3cTHx7NmzRqefPJJiouLaW9vv+82yoMHD9LY2MikSZPIz89n7ty5ANTU1FBVVQX031q2dOlSAC5dukR5eTk9PT1kZWXxox/9aFxMcQyW+9y5c/zhD3/AMAySk5PZvHlzeB7/2LFjfPTRRzgcDjZs2BB+qm99fT2HDh0iFAqxdOlSVq5cCcD169cpKSkhGAzy+OOPs3XrVmJjY8cs7z2///3veeONN5gzZ074OKxdu5b09PQJf8yHyv7xxx9P6OP+xz/+kbKyMkKhEKZp8tRTT7F69eoh97Wnp4d9+/Zx5coVXC4XL7/8MjNnzgQi//sYS0Pl/sd//Ef+9Kc/AfAXf/EXbN68mW9961uj9rv+0JaFiIiMngk1DSUiIiNDZSEiIpZUFiIiYkllISIillQWIiJiSWUhIiKWVBYiImLp/wPA7HXQApgN8QAAAABJRU5ErkJggg==\n"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "To get rid of the gg plot use:\n",
        "```\n",
        "plt.style.use()\n",
        "```"
      ],
      "metadata": {
        "id": "Qbk9wWGa34qP"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "plt.style.use('default')\n",
        "\n",
        "gdp_australia = data.loc['Australia']\n",
        "gdp_nz = data.loc['New Zealand']\n",
        "\n",
        "plt.plot(years, gdp_australia, 'g--', label= 'Australia')\n",
        "plt.plot(years, gdp_nz, 'p-', label= 'New Zealand')\n",
        "\n",
        "plt.legend(loc='lower right')\n",
        "plt.ylabel('GDP/capita')\n",
        "plt.xlabel('Year')"
      ],
      "metadata": {
        "id": "7dX_bPfm39ZK",
        "outputId": "7b0aa802-940f-438c-b6e3-f437cd77c533",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 486
        }
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "Text(0.5, 0, 'Year')"
            ]
          },
          "metadata": {},
          "execution_count": 87
        },
        {
          "output_type": "display_data",
          "data": {
            "text/plain": [
              "<Figure size 640x480 with 1 Axes>"
            ],
            "image/png": "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\n"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "print(plt.style.available)"
      ],
      "metadata": {
        "id": "0igCPYVp4eoe",
        "outputId": "1455dc3c-76f1-4f31-b476-b6271e43b744",
        "colab": {
          "base_uri": "https://localhost:8080/"
        }
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "['Solarize_Light2', '_classic_test_patch', 'bmh', 'classic', 'dark_background', 'fast', 'fivethirtyeight', 'ggplot', 'grayscale', 'seaborn', 'seaborn-bright', 'seaborn-colorblind', 'seaborn-dark', 'seaborn-dark-palette', 'seaborn-darkgrid', 'seaborn-deep', 'seaborn-muted', 'seaborn-notebook', 'seaborn-paper', 'seaborn-pastel', 'seaborn-poster', 'seaborn-talk', 'seaborn-ticks', 'seaborn-white', 'seaborn-whitegrid', 'tableau-colorblind10']\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "plt.style.use('dark_background')\n",
        "\n",
        "gdp_australia = data.loc['Australia']\n",
        "gdp_nz = data.loc['New Zealand']\n",
        "\n",
        "plt.plot(years, gdp_australia, 'g--', label= 'Australia')\n",
        "plt.plot(years, gdp_nz, 'p-', label= 'New Zealand')\n",
        "\n",
        "plt.legend(loc='lower right')\n",
        "plt.ylabel('GDP/capita')\n",
        "plt.xlabel('Year')"
      ],
      "metadata": {
        "id": "COHnYkkB4pWe",
        "outputId": "e92967e6-4049-4e5a-cffa-f7a0dffae58e",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 500
        }
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "Text(0.5, 0, 'Year')"
            ]
          },
          "metadata": {},
          "execution_count": 97
        },
        {
          "output_type": "display_data",
          "data": {
            "text/plain": [
              "<Figure size 640x480 with 1 Axes>"
            ],
            "image/png": "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\n"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "### Fancier Plotting and Stats"
      ],
      "metadata": {
        "id": "alJw76XC89cz"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "Creating random distributions\n",
        "\n",
        "- numpy allows mathemathical operations/statistics"
      ],
      "metadata": {
        "id": "UKnFld3i8_9r"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "%matplotlib inline\n",
        "import matplotlib.pyplot as plt\n",
        "\n",
        "import numpy as np\n",
        "\n",
        "randx= np.random.randint(0,1000,size=100)\n",
        "print(randx)"
      ],
      "metadata": {
        "id": "wS4fVBux9UQI",
        "outputId": "ad8e5d2a-57cf-4713-a9b7-fb966a029cf7",
        "colab": {
          "base_uri": "https://localhost:8080/"
        }
      },
      "execution_count": 5,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "[229 139 328  28  37 897 812 443 813 967 887 785 726 596 448 265 348 678\n",
            " 806 565 407  35 756  85 938 743 465 544 374 780 798 981 275 906 909 122\n",
            " 884  53 171 631 427 527 445 272 229 821 337  93 764 273 216 871 352 664\n",
            " 395 882 369 196 528 180 604 690 749 284 192 545 402 124 250 540  32 441\n",
            " 896 128 831 380 847 178 558 929 436  58 125 719 152  47 340 620 309 502\n",
            "  12 394 235 185 196 271 817 328 921 886]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "randy= np.random.randint(0,1000, size=100)\n",
        "print(randy)"
      ],
      "metadata": {
        "id": "_SCHBYO9-Twx",
        "outputId": "6fbd8ecd-8554-4473-ce1f-6c30a62cefe3",
        "colab": {
          "base_uri": "https://localhost:8080/"
        }
      },
      "execution_count": 7,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "[108 480 140 949 821 121 897   0 432  54 401 324 323 612 275 792 178 606\n",
            "  87 812 556 679 935 944 409 675 715 688  79 690 104 308 109  99 869 444\n",
            " 510 489 259 617 770 389 751 913 702 596 490 561  97 547 968 111 771 742\n",
            " 899 297 202 903 751 157 749 442  55 313 723 315 430 672  94 970 722 647\n",
            " 278 730 776 960 190 282 413 228 331 590 723 607 884 209 229 754 830 179\n",
            "  87 385 862 592 578 573 998 952 275 332]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "To plot your random sample data, use:\n",
        "```\n",
        "plt.style.use(\"name_style\")\n",
        "plt.type_plot(samplex,sampley)\n",
        "```"
      ],
      "metadata": {
        "id": "0xPVkdHc_t65"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "plt.style.use(\"Solarize_Light2\")\n",
        "plt.scatter(randx,randy)"
      ],
      "metadata": {
        "id": "SRe3u2MJ-mGw",
        "outputId": "8667197f-df6e-4576-9d44-6a8b9ca46bef",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 282
        }
      },
      "execution_count": 10,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "<matplotlib.collections.PathCollection at 0x7f8000b44cd0>"
            ]
          },
          "metadata": {},
          "execution_count": 10
        },
        {
          "output_type": "display_data",
          "data": {
            "text/plain": [
              "<Figure size 432x288 with 1 Axes>"
            ],
            "image/png": "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\n"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "To determine the correlation between random data use:\n",
        "```\n",
        "np.corrcoef(samplex,sampley\n",
        "```"
      ],
      "metadata": {
        "id": "fKYX0cZc_kvQ"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "np.corrcoef(randx,randy)"
      ],
      "metadata": {
        "id": "VO7En_87_U_K",
        "outputId": "8fa8fb58-cac5-40ca-c882-db6680f4cbf8",
        "colab": {
          "base_uri": "https://localhost:8080/"
        }
      },
      "execution_count": 11,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "array([[ 1.        , -0.23211198],\n",
              "       [-0.23211198,  1.        ]])"
            ]
          },
          "metadata": {},
          "execution_count": 11
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "To make a line of best fit import seaborn package & pandas package, and an empty data frame:\n",
        "```\n",
        "rand_df=pd.DataFrame()\n",
        "```"
      ],
      "metadata": {
        "id": "9V0RY8hu_3Sc"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "import pandas as pd\n",
        "import seaborn as sns\n",
        "\n",
        "rand_df=pd.DataFrame()\n",
        "\n",
        "rand_df[\"x\"]=randx\n",
        "rand_df[\"y\"]=randy\n",
        "\n",
        "print(rand_df)"
      ],
      "metadata": {
        "id": "1RIC3XFp_5gv",
        "outputId": "f4b937c7-94c2-47fc-ab09-03478adcf7ce",
        "colab": {
          "base_uri": "https://localhost:8080/"
        }
      },
      "execution_count": 15,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "      x    y\n",
            "0   229  108\n",
            "1   139  480\n",
            "2   328  140\n",
            "3    28  949\n",
            "4    37  821\n",
            "..  ...  ...\n",
            "95  271  573\n",
            "96  817  998\n",
            "97  328  952\n",
            "98  921  275\n",
            "99  886  332\n",
            "\n",
            "[100 rows x 2 columns]\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "plt.scatter(\"x\",\"y\", data=rand_df)"
      ],
      "metadata": {
        "id": "6UDrLmRfAolq",
        "outputId": "a8d50af3-a146-46b7-f90e-dfa1196911d1",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 282
        }
      },
      "execution_count": 16,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "<matplotlib.collections.PathCollection at 0x7f7ff4794950>"
            ]
          },
          "metadata": {},
          "execution_count": 16
        },
        {
          "output_type": "display_data",
          "data": {
            "text/plain": [
              "<Figure size 432x288 with 1 Axes>"
            ],
            "image/png": "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\n"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "To add a regression line, use seaborn:\n",
        "```\n",
        "sns.regplot(\"x\",\"y\", data=rand_df)\n",
        "```"
      ],
      "metadata": {
        "id": "nF96puB8Aw9o"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "sns.regplot(\"x\",\"y\", data=rand_df)"
      ],
      "metadata": {
        "id": "UYj-A0K2A5Me",
        "outputId": "bbc5d85c-6048-4711-f4d4-63ce3fbda92a",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 353
        }
      },
      "execution_count": 17,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stderr",
          "text": [
            "/usr/local/lib/python3.7/dist-packages/seaborn/_decorators.py:43: FutureWarning: Pass the following variables as keyword args: x, y. From version 0.12, the only valid positional argument will be `data`, and passing other arguments without an explicit keyword will result in an error or misinterpretation.\n",
            "  FutureWarning\n"
          ]
        },
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "<matplotlib.axes._subplots.AxesSubplot at 0x7f7ff3ce5a10>"
            ]
          },
          "metadata": {},
          "execution_count": 17
        },
        {
          "output_type": "display_data",
          "data": {
            "text/plain": [
              "<Figure size 432x288 with 1 Axes>"
            ],
            "image/png": "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\n"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "To do a linear model plot use:\n",
        "```\n",
        "sns.lmplot(\"x\",\"y\", data=rand_df)\n",
        "```"
      ],
      "metadata": {
        "id": "1Jo1MuhxA_B2"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "sns.lmplot(\"x\",\"y\", data=rand_df)"
      ],
      "metadata": {
        "id": "OZyQuuAIBEsp",
        "outputId": "e3cae3af-8598-45af-dd1d-642a578bffdd",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 440
        }
      },
      "execution_count": 21,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stderr",
          "text": [
            "/usr/local/lib/python3.7/dist-packages/seaborn/_decorators.py:43: FutureWarning: Pass the following variables as keyword args: x, y. From version 0.12, the only valid positional argument will be `data`, and passing other arguments without an explicit keyword will result in an error or misinterpretation.\n",
            "  FutureWarning\n"
          ]
        },
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "<seaborn.axisgrid.FacetGrid at 0x7f7ff37609d0>"
            ]
          },
          "metadata": {},
          "execution_count": 21
        },
        {
          "output_type": "display_data",
          "data": {
            "text/plain": [
              "<Figure size 360x360 with 1 Axes>"
            ],
            "image/png": "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\n"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "sns.kdeplot(rand_df.x, rand_df.y)"
      ],
      "metadata": {
        "id": "P8lZafCLBKoe",
        "outputId": "bdebdaae-687d-47e6-9516-d353292a75d1",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 353
        }
      },
      "execution_count": 20,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stderr",
          "text": [
            "/usr/local/lib/python3.7/dist-packages/seaborn/_decorators.py:43: FutureWarning: Pass the following variable as a keyword arg: y. From version 0.12, the only valid positional argument will be `data`, and passing other arguments without an explicit keyword will result in an error or misinterpretation.\n",
            "  FutureWarning\n"
          ]
        },
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "<matplotlib.axes._subplots.AxesSubplot at 0x7f7ff3a939d0>"
            ]
          },
          "metadata": {},
          "execution_count": 20
        },
        {
          "output_type": "display_data",
          "data": {
            "text/plain": [
              "<Figure size 432x288 with 1 Axes>"
            ],
            "image/png": "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\n"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "Making a bar plot, use:\n",
        "```\n",
        "sns.barplot(\"x\", data=rand_df)\n",
        "```"
      ],
      "metadata": {
        "id": "ztoiO_0FBds-"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "sns.barplot(\"x\",data=rand_df)"
      ],
      "metadata": {
        "id": "neqTXiOkBuxM",
        "outputId": "60cfda23-edee-4c0e-ed40-ecc3d3099374",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 353
        }
      },
      "execution_count": 25,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stderr",
          "text": [
            "/usr/local/lib/python3.7/dist-packages/seaborn/_decorators.py:43: FutureWarning: Pass the following variable as a keyword arg: x. From version 0.12, the only valid positional argument will be `data`, and passing other arguments without an explicit keyword will result in an error or misinterpretation.\n",
            "  FutureWarning\n"
          ]
        },
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "<matplotlib.axes._subplots.AxesSubplot at 0x7f7fef1d7810>"
            ]
          },
          "metadata": {},
          "execution_count": 25
        },
        {
          "output_type": "display_data",
          "data": {
            "text/plain": [
              "<Figure size 432x288 with 1 Axes>"
            ],
            "image/png": "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\n"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "sns.barplot(\"x\",\"y\", data=rand_df)"
      ],
      "metadata": {
        "id": "WsomuWT6BdEV",
        "outputId": "d57b8c4a-d725-45fd-dd7f-31c64bc8ba0a",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 353
        }
      },
      "execution_count": 23,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stderr",
          "text": [
            "/usr/local/lib/python3.7/dist-packages/seaborn/_decorators.py:43: FutureWarning: Pass the following variables as keyword args: x, y. From version 0.12, the only valid positional argument will be `data`, and passing other arguments without an explicit keyword will result in an error or misinterpretation.\n",
            "  FutureWarning\n"
          ]
        },
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "<matplotlib.axes._subplots.AxesSubplot at 0x7f7fef594f50>"
            ]
          },
          "metadata": {},
          "execution_count": 23
        },
        {
          "output_type": "display_data",
          "data": {
            "text/plain": [
              "<Figure size 432x288 with 1 Axes>"
            ],
            "image/png": "iVBORw0KGgoAAAANSUhEUgAAAZYAAAEJCAYAAAC3yAEAAAAABHNCSVQICAgIfAhkiAAAAAlwSFlzAAALEgAACxIB0t1+/AAAADh0RVh0U29mdHdhcmUAbWF0cGxvdGxpYiB2ZXJzaW9uMy4yLjIsIGh0dHA6Ly9tYXRwbG90bGliLm9yZy+WH4yJAAAgAElEQVR4nO3deXQc9Zno/W9V9b5qXy15k7xb2AJv2MbsW0zABgJhJwkkZDKZwEyYJHOSyU1mcmeYzHBm3vvy5oasJCETCHjCFnAImzeWYIxtjDd5kS0vWiyppd67qt4/qtWWZVu2Rdkt2c/nHJ3z665fVT1dXV1P/ZZuKXpsj4kQQghhEzXfAQghhDi7SGIRQghhK0ksQgghbCWJRQghhK0ksQghhLCVI98BnG7dkUi+QxBCiBFHAUKh0JDWlRaLEEKIo6jq0NODJBYhhBC2ksQihBDCVpJYhBBC2EoSixBCCFtJYhFCCGGrMzLd+InnV7Jh+16Cfg/fuf8GAKLxJI8ve4OOrl6KCwLct+Ri/F43pmny1PJ32di0F5fTwd2LF1BbWQzAmvXbeWnlhwBcu+A85jXUnYnwhRBCnIIz0mKZd14df33rFUc89/LqDUwaU8n3v3wjk8ZU8sqaDQBsbGqh9VCE7z2wlNuvnceTL68BrET04op1fOPexXzj3sW8uGId0XjyTIQvhBDiFJyRxFJfW4HP6zriufVbm5k33WpxzJtex4dbmnPPz20Yj6IojKsuI55I0d0TY9OOFiaPrcLvdeP3upk8topNO1rORPhCCCFOQd6+eR+JxgkHfQCEAl4i0TgAXT0xCkP+XL2CkJ+unhidA58P+unsiR1z2yvWbmHFB1sBuGfxPKrKS07XyxBCiLNSb2/vkNcdFj/poigKiqLYtr2FjRNZ2DgRsH7SRX7WRQgxVPufLc6VK5d25DGSM0sbid+8D/m9dGdbHN09MYI+DwAFQR+dkWiuXlckSkHQR+HA53uiFGZbPEIIIYaPvCWWhgk1rNmwHYA1G7bTMKHWer6+hrfXN2GaJjtaWvG4XYSDPqaMq2bTjn1E40mi8SSbduxjyrjqfIUvhBDiOJQz8T/vf7LsTbbuPkBvPEHI7+W6i2Zw3oRaHl/2Joe6eykOB7hv6eHpxv/9yjt81NSCy6lx9+IFjK6yxkhWrdvGy6vXA3DN/AYuPK/+hPuWbjAhxCdxLneFBQKBIa17RhJLPkliEUJ8EpJYTp18814IIYStJLGIozz3x6/x3B+/lu8wxCd0z4pm7lnRnO8wxDlIEosQQghbSWIRIuv21S9w++oX8h2GECPesPiCpBAn8vC3HmHHrj0AjBtTwyM/eDjPEQkhjuecSyyZZ9/JlR1L5+QxEiGEODudc4nldOv53Xdz5eAt3z1uPSGEOFvJGIsQQghbSWIRQow4r60o47UVZfkOQxyHJBYhhBC2ksQihBDCVpJYhBBC2EpmhYnT7kevP5grf+mSR/MYiRDiTJAWixBCCFtJi0Uc9a32BQvzHJAQYkSTFosQJ+GOVa9yx6pX8x2GECOCtFiEEOe8phdLcuXxn2rPYyRnB2mxCCGEsJW0WEaYD57/eq4887p/y2MkQghxbNJiEUIIYStJLEIIIWwlXWFCCHEWSD91IFd2fqYij5FIi0UIIYTNJLGIU/L08gd5evmDJ64ohDhnSWIRQghhK0ksQgghbCWJRQghhK0ksQghhLCVJBYhhBC2ksQihBDCVvIFSTFs/f3qh/o9yu8XvoQQJ08Sy3Gknn0pV3YtvTaPkQghxMgiXWFCCCFslfcWy6vvfMSqddtQFKgqLeTu6+bT3RvnJ8veJBpPUltRzL3XL8ShaaQzOr94bgXNBzrwe918YckiSgqC+X4JQpw1Pr+yO1f+6YJwHiMRI1leWyydkSivv/cx3/zcYr5z/w0Ypsl7H+3k2dfe57LZU/j+l2/E53Gxat02AFat24bP4+L7X76Ry2ZPYdlr7+czfCGEEMeQ964wwzBIZ3R0wyCdzhAO+Niyaz+Nk8cAMK+hjg+3NgOwflsz8xrqAGicPIbNu/Zjmma+QhdCCHEMee0KKwz5uXzuNL71/zyN06kxeWw1oyuL8XlcaKqV8wpCfrp6YgB09cQoDPkB0FQVr9tFNJ4k4PMcsd0Va7ew4oOtANyzeB5V5Yf/n3VHv3rhUOi4sbWdZL2Beoa43lDYtX1NU49ZHmz7Q933UNcbGOPpPLan43Xn06nFfLgrbCS81tMR48Bt7j/N+7NLO4d/Nt+OOHt7e4e8bl4TSzSeZP3WZv7pr27C53Hx42df56Omlk+83YWNE1nYOBGA7kiE7kjkmPWO9/xQ69m13pnevq4bxywPtv2By5549fAvHt91+aMnvd7JGhjj6Ty2p/K6R4Lhev5+MtbNpH0xHr75PHqbxYMsG57siLPv5n4o8toVtnnXfooLggT9HjRNZebE0TTtbSWWSKEb1oWkKxKlIOgDoCDoozMSBUA3DOLJFH6vO2/xCyGEOFpeE0tRyM/OljZS6QymabJ5134qSwqYOLqCtR/vAmDN+u001NcC0FBfw5r12wFY+/EuJo6pRFGUfIUvhBDiGPLaFTa2upTGSaP5558+h6aq1JQXsWDmBKbVjeIny97kuTc/oKa8iPkz6gGYP6Oen/9hBd9+7Bl8Hmu6sRBCiOEl799juW7RTK5bNPOI50oLg3zzc4uPqut0OLj/xkvOVGhCCDGoyJNFuXLotkN5jGR4yXtiEeJ0un3NE7nyb+bdddr3d8fK1bnyrxdceNr3J8RwlPfvsQghhDi7SGIRQghhK0ksQogh+eJK60+IgWSMRYhh4M4V63LlXy2cMaRt3L1iZ678y4VjP3FMA923MpUrP77AZfv2xdlDWixCCCFsJYlF0B3Zk+8QxFnmoVUBHloVyHcYIk8ksQghhLCVJJZhavMfHmbzHx7OdxhCCHHKJLEIIYSw1Tk/KyyzzJov6ViyIK9xNP3P3+fK42/419O+vz+99BAAV1z7H6d9X0KIc4u0WIQY5u58axN3vrUp32EIcdIksQghhLCVJBYhhBC2OufHWMTxPfytR9ixy/qOy7gxNTzyA5mlJoQ4MWmxCCGEsJUkFiGEELaSrjAhzgH3rmjJlX++sDqPkZx+77xeBsCcS1rzHMm5S1osQgghbCUtln7Sy/6c7xCEEGLEk8SSR83PfgOA2qX/kudIhBh+/mdVSa58w/z2PEYiTpV0hQkhhLCVJBYhhBC2ksQihBDCVpJYhBBC2EoSixBCCFvJrDAhzpA7V76XK/9qwaw8RiLE6SUtFiGEELaSxCKEEMJWkliEEELYShKLEEIIW0liEUIIYau8zwqLJZL86sXV7GvrREHhrsXzKS8O8/iyN+jo6qW4IMB9Sy7G73VjmiZPLX+XjU17cTkd3L14AbWVxfl+CUKc8760ypUr/2h+Ko+RiOEg74nlqeXvMnVcNV+88RIyuk4qneGPqzYwaUwlV1/YwMur1/PKmg0svfQCNja10HoowvceWMrOfW08+fIavnHv4ny/BCHOWl9YGc2VFZx5jESMJHntCosnUmxrPsj8GfUAODQNn8fN+q3NzJteB8C86XV8uKUZgPVbm5nbMB5FURhXXUY8kaK7J5a3+IUQJ/ZPq0O5v4F+uroo9yfOHnltsbR39RDwefjlCytpOdhJbUUxn7lyNpFonHDQB0Ao4CUSjQPQ1ROjMOTPrV8Q8tPVE8vV7bNi7RZWfLAVgHsWz6Oq/PDPb3f0qxcOhXKPw6EQx/th7nDo6A/E8fQMYb2B9fo/HmwbpxLXyW5D09Tjlu2Ia6gxDxbLyRrq+zGUbXyS7Rxv2VD3bZVbjrnsaN0D6kWPWctaFulXTgxYZhxzX2fymAz1XBu43v5BlkVs2J9d2jmQK9sRS29v75DXzWtiMQyTPQc6uPWqOYytLuV3y9/hldUbjqijKAqKopzSdhc2TmRh40QAuiMRuiORY9br//zx6pxo2WBOdr2B9U53XINtQ9eN45btiGuoMQ8Wy8ka6vsxlG18ku2czPl6Kvse7Pw62W2cePuuAY8D/cqhY65nKRpkWckgyzyDxDjYsuMZbF/FRyxrf/rwYxfmIOvljx2xaOrQO7TymlgKQj4KQj7GVpcC0DhpDK+s3kDI76U72xLp7okR9FknSkHQR2fk8B1UVyRKwYDWSj7Env4/+Q7hhF5/6aFc+ZJr/yOPkQghznZ5HWMJB3wUhfwc6LCa35t37aOyNEzDhBrWbNgOwJoN22mYUAtAQ30Nb69vwjRNdrS04nG7juoGE0IIkV95nxV2y5Vz+Nn/vIVuGJQUBLhr8QJM0+TxZW+yat02isMB7lt6MQDT6kaxsamFbz/2LC6nxt2LF+Q3eCGEEEfJe2KpqSjmW5+/7qjnH7z9qqOeUxSFz14990yEdU654VOHT4NrrnmY5/74tTxGI4QY6fKeWMTZ6aevPXj4wanNvRBCjHDyky5CCCFsJYnlNOt4+pt0PP3NfIchhBBnjCQWIT6hO1au4I6VK/IdhhDDhiQWIYQQtpLBe3HG/debhwf2v7ro0TxGIoQ4HaTFIoQQwlaSWIQQQtjqpBPLU396lz0HOk5cUQghxDntpMdYTMPkv/77TwR9HuZMG8/saeOO+Al7IYQQAk4hsdxy1RxuvmIWG5taeHfjDl5a9SFjq0qZO308MyaNxuOS/y4nhBDiFGeFqapKQ30NDfU17Gvr5Kf/8xa/fH4lv335bS6YMpbFF82QVowQQpzjTimxxJMp1n68i3c27qCltZOZE0fz2avnUhQO8OrbG/k/v3uVb993/emKVQghxAhw0onl/z7zOpt2tFBfU8FFjRM5b0ItToeWW37TFbN58Ie/OS1BCiHE2ST568Pzptx3GIPUHJlOOrGMrS7l1qvmEA4c+x9rqYrCv33tVtsCE0IIMTKddGK5cu60E9ZxOeWL/EIIca6TL0gKIYSwlTQxhiDxzBO5sufGu/IYybnrtre/kys/Ofd7eYxECDGQtFiEEELYSlosI8DG575++IH8m18hxDAnLRYhhBC2ksQihBDCVpJYhBBC2EoSixBCCFtJYhFCCGErSSxCCCFsJYlFCCGEreR7LGfQ/me+kStX3vgveYxEiPz4r9UFufJXL+zKYyTidJIWixBCCFtJi0UIIQZofq4kV3Zi5jGSkUkSixCn6I5Vr+fKv55/SR4jEWJ4kq4wIYQQtpLEIoQQwlbDoivMMAz+989eoCDo469uuZz2rh5+suxNovEktRXF3Hv9QhyaRjqj84vnVtB8oAO/180XliyipCCY7/CFGNE+t7IjV1aGxyVBjHDDosXy2nsfU1ESzj1+9rX3uWz2FL7/5RvxeVysWrcNgFXrtuHzuPj+l2/kstlTWPba+/kKWQghRqT077fn/k6XvCeWzkiUDdv3Mn/GBABM02TLrv00Th4DwLyGOj7c2gzA+m3NzGuoA6Bx8hg279qPacqMjTOhK7In3yEIIUaIvLd7n/rTuyy99HwSqTQA0XgSn8eFplo5ryDkp6snBkBXT4zCkB8ATVXxul1E40kCPs8R21yxdgsrPtgKwD2L51FVfnjqYEe/euFQKPc4HArRfpwYw6HQEY8TA5bFBlmv//b3H2ebA7c/2LLB4jpZJ7tvTVOPu2yocQ22v8H0j2WwuAZjR71Tea/sOkYns85gda1yyyDb6eBYrHrRQZZF+pUTA5YZJ4zZjuN1uj8fx1p2steJwbTSe9z12n7UliuXfqn0pLfZzoGTiqV//IPV6+3tPe6yE8lrYlm/bQ9Bn4fRlSVs2b3/xCucpIWNE1nYOBGA7kiE7kjkmPX6P3+8OnYtG1hvqMtOdt+DOdl967phe1yD7W8w/WMZLK7B2FFvqO/jJ9nHyawzWN2hHvNTO7ddAx4H+pWPffGylhUNsr+SQZZ5BolxsGXHM3BfJcesZS0rHmTZyTp8c3S6P+NDrdd3cz8UeU0sTXtbWb9tDxub9pLJ6MSTaX63/F1iiRS6YaCpKl2RKAVBHwAFQR+dkSiFIT+6YRBPpvB73fl8CULk1d0rrH7yXy6sy3MkQhyW18Sy5JLzWXLJ+QBs2b2fV9/+iM/fcBE/fuZ11n68i1lTx7Fm/XYa6msBaKivYc367YwbVcbaj3cxcUwliiL/BF7Y745VL+fKv55/dR4jEWLkyfvg/bEsufQCXn1nE99+7Bmi8STzZ9QDMH9GPdF4km8/9gyvvrMpl5SEEEIMH3kfvO8zcXQlE0dXAlBaGOSbn1t8VB2nw8H9N8pPaAghxHA2LFssQgghRi5JLEIIIWwliUUIIYStJLEIIYSwlSQWIYQQtpLEIoQQwlaSWIQQQthKEosQQghbDZsvSApxtrlz5du58q8WzM1jJGK4S/5GB8B9u5bnSOwhLRYhhBC2khaLEGJY+O3qwz9H/9kLj/0/Yk7V2j8f/n8mjZe1DVJT2EkSixDnmHtXHsyVf76gPI+RiLOVdIWJYeV7Kx/ieysfyncYQohPQFosQgghAEg/szFX1m5uGPJ2pMUihBDCVpJYhBDiDEj+yk3yV+fGv1KXxCKEEMJWkliEEELYSgbvzyJrXvi7XHne4h/mMRIhxLlMEosQQgxTqd/25squzwbyGMmpkcQixDBz54oNufKvFk7PYyRipEo/tTdXdn5m1Bnfv4yxCCGEsJUkFiGEELaSrrAR7r1+A/ZCCDEcSItFCCGErSSxCCGEsJUkFiGEELaSxCKEEMJWkliEEELYSmaFiRHvtrcfzZWfnPtgHiMRYnhKP70LAOfNY87I/qTFIoQQwlaSWIQQQtgqr11hhyJRfvHcCiLROAoKC2ZO4LLZU4jGkzy+7A06unopLghw35KL8XvdmKbJU8vfZWPTXlxOB3cvXkBtZXE+X4IQQogB8ppYNEXhpstmUVtZTCKZ5gc/e57JY6tYs347k8ZUcvWFDby8ej2vrNnA0ksvYGNTC62HInzvgaXs3NfGky+v4Rv3Lj4jsSaf/f0Z2Y8QQox0ee0KCwd9uRaHx+2kojhMV0+M9VubmTe9DoB50+v4cEszAOu3NjO3YTyKojCuuox4IkV3Tyxv8QshhDjasJkV1t7Vw56DhxhbXUIkGicc9AEQCniJROMAdPXEKAz5c+sUhPx09cRydfusWLuFFR9sBeCexfOoKi/JLevoVy8cCuUeh0Mh2o8TWzgUonWQZcdLbQO3v3/AsmOVT7TsePWGumywfWuaetxldsV1vLoDn+8fy8C4TmXfi19+PPf4havvO+UY7XqvBqtr9/atcssg63UMsiw6yLJIv3JiwDLjlGMebNnJnidD2capbnOw68RgWknm6rVy+P+sWI87c+U22oa0/XYOnDDmgfEP3ObxXtupGhaJJZFK8+Nn3uAzV8zG63YdsUxRFBRFOaXtLWycyMLGiQB0RyJ0RyLHrNf/+ePVsWvZwHpDXXYm49J147THdTLvzcBYBsZ1uvd9Ot6rweravf0zcw65BjwO9Csf+4JoLSsaZFnJgMf9eQaJsf+y0kG20d/AfZUcs5a17Njjuid+T9396h2+ObLjvRrMyZ6/dsr7rDBdN/jxM68ze9o4Zk4aDUDI7811cXX3xAj6rBOlIOijM3L4DqorEqVgQGtFCCHyJf7LQuK/LMx3GHmX18RimiZPvLiKiuIwl8+Zmnu+YUINazZsB2DNhu00TKi1nq+v4e31TZimyY6WVjxu11HdYEIIIfIrr11hTXtbeWdDE9VlhfzT438A4PpLzueqedN5fNmbrFq3jeJwgPuWXgzAtLpRbGxq4duPPYvLqXH34gV5jF4IIcSx5DWx1NWU86N/uOeYyx68/aqjnlMUhc9ePfc0RyVGutvW/DhXVrL97WeLu1ZsyZWfWDgxj5EIcXx5H2MRQghxdpHEIoQQwlaSWIQQQthqWHyPRZweK17828MPTu2rQEIIMWTSYhFCCGErSSxCCCFsJYlFCCGErSSxiBHhkR88TPFXnRR/1ckjP3g43+EIIQYhiUUIIYStJLEIIYSwlSQWIYQQtpLvsQghxAiR+u+uXNl1a0EeIxmctFiEEELYSlos4rge+cHDLHv5a6d1H//21kO58tcv+o/Tui8hzqTEE4Fc2XNX7yA1zz7SYhFCnDM2LC9lw/LSE1cUn4i0WIQQYgRK/a49V3bdUpLHSI4miUUM2W//9ODhB/IjlyJPVr5ZlisvWNSax0hEH+kKE0IIYatzosWSeXYtAI6ljXmORAgxXGx++fBYixMzj5Gcfc6JxCLEsdy+elmu/JsLl+QxEiHOLtIVJoQQwlaSWIQQQthKEosQQghbSWIRQghhKxm8F0IMe39ceXgG1zUL2vIYiTgZ0mIRQohzWPr3m0n/frOt25TEIoQQwlaSWIQQQthKEosQQghbSWIRQghhK0ksQgghbCWJRQghhK0ksQghhLDViPyC5EdNe3lq+bsYpsn8GfVcfWFDvkMSQgiRNeJaLIZh8NuX3+Ert17BP37xBt77aCf72rryHZYQQoisEZdYdu1rp6woSGlhEIemMWvKWNZvbc53WEIIIbIUPbZnRP3rtPc/3sWmphbuXDwfgLc3NLGzpY3PXj03V2fF2i2s+GArAF9csgC3y0lPLEHQ58nV6f/4eOUzvSyf+5a4Rs6+h2tcckxGTlwnU88wDEKhEEMx4losJ2Nh40S+9fnr+Nbnr6O4qJBAIMDPn19DIBDI/fV/fLzymV6Wz31LXCNn38M1LjkmIyeuk6k31KQCIzCxFAZ9dPZEc4+7IlEKg748RiSEEKK/EZdYRleV0HooQntXDxld571NO2mYUJPvsIQQQmRp//gPD30330GcClVRKC0K8fM/rOD19zYzZ9o4GiePOal1R1eWHPfx8cpnelk+9y1xjZx9D9e45JiMnLhOZRunasQN3gshhBjeRlxXmBBCiOFNEosQQghbjcifdDmRJ55fyYbtewn6PXzl1iv4xXMraGntJJ5MoQBOhwO/100mkyGWTJPRDRRMUBQ8LiemafUOFoX87Gvrwul0oOsGumGgKODQNDK6gaoqqIqCbhg4NI2Az01XJIaRXd/jcqKqCrFECgBFUcA08bhdhAIeuiIxkulMbpmiWOvohkEyZT3v0FR0w8zFlN0EAE6HRkbXc4/7tm9m62mqSkY3cusBuBwOMrqObhzuAVUATVMxTBMj+7zf6yaeTGEYJgqgqEpuGYCmKkdsw6Gp6LrBsfpVFQUwyS1TFFBQMExr2wPX0VTVOtbZZUo2SNMEl8M69oZp5rajKORi0VQFEzBN8/BxAVRVxTCOjm/g/p0ODb/HTTqTIZpI5Y6306ExflQZTXtbMU3ziOPa91r63oOSsJ/27mguetM0cWgapmmgGyaFIT+xeBIUhWQqDUDA5yaeSKGoKg5VJZlKY2KNKRqmiaooKIqCYRq519VHVRUwORxD9v3si9HtcmAYZu5c6Tu+1n499MYSh7eVPQ9NOOL97ttu37LD5xx43S6SqUz2c2Bt29rP4XNEtQ5UbpuqouBwaKSy57/a7/zSVBWHQyOZSh9xvh/rXHH0e519x6pPYchHV0/sqON1rHO1b9tup4N0Rs8d8/7naP/9a5ra7/gcPtdcTo1UWs/V7X+s+/Q913+ZAjgcGn6vm55oAt0wUBUFM7vH/seg77MwcP2+aNwuB+m0DvQ7JxRwahoZw8AwTFxO63PUt1I46MM0DKKJVPazp1Ac9uNyOtjb2kl1aSEHD3Xz6YsbuXLuNE5kxA3enwyf18WF59Wzbmsz86bXMX5UGdPqqrnp8lm8v3k30+qqae+M4HI6+PySiygOB8lkMgR8XkoKgnhcDhRFYfK4KkoKgxQEfKQyGepGlXPN/Abuv/ESlq/ewKcXzeSOay/kg827uXLeNLbtPohuGFw5bxrNBw5hYnLbNRcydlQpXT0x7r/xYlrauuiMRPmXv/kMIb+XWCJJMp3h1qvmsLGpBUVRqCkvoiDoo7MnxuVzp3LDxY1sbz5IPJnmoTuuJpPJsL+9i//1wFL8Hjf7Wjtxu5zcctUcPmraBwosapxIRjdIJK0P51duuZwPNu8mldb5wpKLKSkIsGNvKxdMHkMyk2HC6Apqy4tYeun5vL9pJ8l0hhsvm8XBjm6WXHoBTXsOMnVcNcl0htryYnpjCZwOjaWXXsCW5v0A3PPpBVy3qJGNTXtxOx2MG1VKW2cPxWE/t1w5F82hEvC66Y0lmTy2iinjqojGk9x8xSzWb9vL+VPGoGIlYtM0KS4IcP+NFxOJxjEMK5moqsr0+hpcTo2q0kKi8SSzpo2jrbOHjG7w6N/extrNzagoJNMZSgoCLDp/IvvauqgoCRMO+FgwYwIHOrqpLAlTUhDkUCTKdQtn0BNLoCoK0UQC08x+QDM65UUhbr5iNq+/9zEFQV82cVsXnVFlRXzu+ovY0dJGcTiA3+siEk1QURymtqKYiy+YTPOBDkI+D6YJ6YyOqihUloSpLiuirTNCyO+1blx0k8ZJo3E6NLp6rQvi7OnjiSdTTK+rweNysrBxInsOHiKd0bl87lS6emJMHFNJWWGQ73zxBlas3YLT5WD21LG0tHZimCbTxlfzlVuv4I33NmOaJg/cdAlrt+xGUWDhzAns2tfOqPIi3C4HNeVFjK0upSsSo6aiiPraCgqDPlo7e7hs9hQKQ37aO3uYNXUcVWWFeNxOpoytxOnQSKQy6LpB0OdhwugKunsTfPHGiykM+pk0ror9bV34vC4yGZ3KkgLrxkxVKS0M0BNN8A9fuI4PPt6NbhgUhwOgQFVpIV09MbxuJ6OrSojGk1w5byqthyJMGVdFR1cvAA/cfDHvbdrF9Ytmsr+9i+svaWRTUwu6bqJqKgom5cVhkukMWna/iqIwt2E8PbE4Ib+PWDKJ06ER9HuIJ9NcdMEkrr5wOj3RBB3dvRSF/Xzn/ut5a+0WTNNk6WXno6oq3b0xvC4nJQVBuqNxVAX+4QufZv22ZkzTSniXz5nKrn3tFAS8ZAyDUMBDKp3B63FSX1PGoZ4YQZ+HWCKFbugUBLwk0ml8HjdetxvTNFgwcwL72rsZVVpEpDdGwO8h7PdRUhgk6PcQSyQJ+tykdcamXUMAABYiSURBVJ2KkjDpjE5h0MvU+lG0dkTwuBxMGVtFOpMhmcpQHPajqSrVZYVEonE0VeXe6y/ipstn88ZfPqasKMydi+ezcftePnfDRfg8bpxO6wbrRM7KrrD62gp8XhdgZeLaymKmjKsm4PNQVVJAYdBPOmPdPbqdTiqKQxSE/JimSWVpAYm0Tjqjs2NvG/NnTACsO4Ttew9y3sRa4skU6YzOzEmjAev3yxLZTO92OqgoDoNp4vd66OyJ0jhpNIpixVUQ8ALW3caCmROYPXUchmEwr6EOBdB1g7HVpZQVh1AU6IzEqK+tyN6qwLhRZXREoiiKgtft4toF5xGNJ3G7HMydPp6Mrlt3Mtn9m5goikJtRXHuDqtx0mimjq/GBHbv76C6tJAZE0ez+0AHU8ePwunQUIBF50+iuqyInliCyrJCnE7rwhPpjeP3uikI+skY1l1wWVGIgM/L+q3NLJwxgdqKYnbta8fp0CgM+QkGPOzY08rU7Puws6WNS2ZNobKkgJDfi2maVJcWZu+wrPs0r9uVfX/CODQNLdvq8HtcGIZJcThANJHi4x37CPmt42qYJl09URLZloBpwtTxo+iNJxk/qgzTtFoMxaEAhmGSzFh3zLVVxTg0lVi2leZxOUik0jgdGtFEkjFVJWR0A103CHjd2Ttpk3DAS1lRCI/LiaJYLap0RqeipACA1R9uxTBMK57sezi3oY7Wzh6und+AaZqkMxnrm86myYUNdRzo6MahaQB8asF5gHXHub+9i3nT6zBNE4/TwYatewCYXjcKl8uZu9PXMzobtrdYjzWVVDrDU8vfsVo2wBvvbybgdWOaJjv2tqFpKh6Pk954kosvmETTnlYSqTQuh4OmPa0sapwIwAVTxrK1+QCTx1XRtKeVpj2tXDZrCjta2phWN4pEKo1DU6kuLWRfaxdjqorxe62LkdOh5RJu0O+hqCBApDdOeVGIRDKD2+2k7VAPZcVh3C4HqUwG04Q508bn3sdbr5qLoioc6o5SUhiiuzeOrhuUFYVQFOt4RaIJSgpDBH0edMPE5XJkW3NQWhgArAt9KqMDCm6Xg8Kgn954Irsfk7nT6qxzoqKIhvqaXG9CKq1jZFuG1utJksno6LpBaWGQQ5FeFKxejMrSAgzDxMQkldGpLivAMAxKC0NoqoKhG6iqCia4XU4UIJXJkMlkUBSFVDqDpqpoqkJ5cQiv20XT3jbKi0Ic6OhCURTGVBbj9TiJxpN09cRwOR34vG6cmkZ5URjDMJnbUE9HZy8VxWGSaR0TCPqsz0oqreeujVaL1iCeTJFMp3G5HBQEfbz30Q5mTxvPmKoSNE056WvwWTsrrL2rh8ee+jPfuf+GI5774RN/JJ5MkdGt7iuvy0EklsChqVw0cyJvrt2CrltdXkXhAKPKi0ilM+ze145umJQWBqkuK+T9j3dSXhSmuzdOPJEio+u4nA6S6QxBn5ueWBKHpuJ2OWmYUMP6rXtwZS9SXreLf/2bWwB49Ncvc/BQhJuvmM2vX1hFKqPz73/7Wf77lbd5e30THpfTShaaSjKVyTXPXQ6N//r7O3nr/c08+fLblBQEmdswnuVrNhIOeInGk9kL4eFuL0WxuoTuW7IIr8fFo79+BbCayAtm1rN6/Xa+fd/1fPuxZ/C6XFSVFbCzpZ2JYyrY19ZFKp0hlkjhdjoIeN109sQIBbx09cQA8LgcOB0OZk0dy3sf7cTvdXPwUDcKChXFYXTDYP6Mep5/ax3lRSG+dPOl/PuvXmbW1LEsX7Mx9z71dX8EfR6Kw372tnai6wblxSEOdkRQVGt7HV29ua5EVbEuHpqmUltexM597QD4PC4Kgr6jfqjUoalcOnsKH25ppvVQBJMju1UKQ36isQSZbJfFpDGVbNi+F01V8XvdBHxu9rV14XY5cTs1rl04gz+t2UAkmsDtdHDtgvN4efUGItE4BQEfU8ZXsfrD7SjAqPJCDnREcDo04skUZYUhItE4Gd1gdGUJO1vacl1efV1ELqfDusN1u6wu3X7dIQ5NJeDzcPWF01n2+vskkunsuZhGUZRc14/er5sTIBpPHtXd4sx2NVrdh0rueFjvr5O0ruP3uIlE46iKgtOhoRsGhSE/bZ09AHg9LpKpNKqi4Pe6Cfm9VJcW8s5HTdTVlONyOlCAjU0tudfVUDeKgM9DTUUxz7/1AemMzuiqEibUlvPSyvU4HRoVxWH2t1vvY99FW1UUJo2pYs/BDiLRRLarSMHtdIDV+0Yilc61QMuKwuw50JE77zOGgdqvK7WvSyqd0VEU66I/va6GdVt29zsWVr+ux+3E53HT0W21mjRVJej30NUTI+Bz43Y5KQj42NHSdrgrG3C7nSRTVssp16VqbRVVVTBNcvVdTgdGtrvL73XnPtd9y9IZPdsCU0ildcqLgrR19eLQrG5Gv8fFZbOn8OKq9ei6wTXzG3jt3Y9Jpq0br4vPn8TqD7eRyuiEgz4ivXFM08TvdfOtz1/Ho79+hQduvpTqskKef+sD3C7nSXWFnZUtlmNJpNL8+Jk3qKspZ9KYKuZOH09R2M9ff/ZKPnf9RYyuKOHdTTuZObGWW66aQ8Dn4QtLFpFIpmnr7KGqtJA7F1/IV269nLWbd3FR40T+4Quf5qE7r0ZRFWZPG0tFcZiisB8te3ft97qZNWUs8UQKVVFY2DiRcMCX6xd9aeWHqKqK06Hxm5dW43I5CPo9eFxODrR3o2kqj/7dbXz97mvRM1Zy+c+H72D21HGkMjrf/dEyXn33I0J+D7qh8+rbHzF3+nhi8RSzpo5lyrgqfB4XDk3lka/dkh2DgTff38LTf3qXkN/6bSCvx8k7G3egqSr/7+9eBRMUFeLJNPd8egE7W9roicYpDPn5/A0X4XE76Y7GKQh6qSiyfvbB53HxuRsWkUileOMvmxlVXsgFU8bidbu4dPYUykvCdPfGeP0vm/F73Zw/eQw/fuYNLp8zhbfe30JtRTF3XzefMVUlBH1eHJpKZWkBSvYiUVoYoqM7yujsHVZHVy8VJWEArl80k9rsvPvqskJ6ogk8LgcOTWFUWRF3X7cAsG4UJoyu4NILJgOwqamFju5efB43xeEA3uyxKgpZH7BURqesMGi1XlvaAKsP3aGpFIR8KEBFcYjaihKWr9lAb9y6g71gyliqywtRVYXyohCGadLS2onTYd1Vtx7qpbI4zITRFVZy0FSrawaIxZNMHlvJ9Rc3AnDN/AZCfg8OTc2+Bj+fmt9AaVEIj9uJ06mhGyYP33Mtr6zZgKEbuF0O7vzUhajZMUNNVSkrClNVarWibr92Xu53oa6YM5XyojD1tRW4nFr2ImbidB5OspXZ41xXU4auG/RE41Zd0ySZzrD00vOprSwGrNcS9nsxDZOA32o1aKrCB1t2M2V8NTv2trF7fweRaByA//WlJYT8HrbvOci6rc109kRxZi/sPb1x3t+0E4DL50zh63dfi2EYaJrKD/76ZmZMHI1umOzc10Y42xNgAt97YAlgkkimWbxoJg5NY3RFMQrQcvAQPo/Vm+F2OWior0FVFVxODVVV0DSVMZUlKApcMWcaHqeDAx1dpDM6X7/rGh75m8+gKioet5MfPvhZvB4nLqeDgM/DhNpyYokUmqrwr1+9hYyus3t/O6PKCpk7vQ6HQ6NhQi1et5NwwIvX7aK8OERVSRhFUfB7XAS87uwNmkrIb/1elys7xhvpjR8xLjRryljqasrI6AbptI7f4+JQJIZhmMyaMta6OUqk+OPqDWjZ1urG7XsZXVVMQcD6tZI3399MwOfB63bR0xvnCzdcxPceWIoC/Oj3r+FyalSXFZ7q5fbcSCy6bvDjZ16nrChIR3cvn7/hIt7/eBfnTxrDRztaOH/yGHbua8PrdlJdXsShSJRkKsN/Prmc3fvbaeuM0NTSyvS6UVaLwTAJeK0PZktrJ2VFIYpCAZoPdnDdRTOZUFtBWVGI3liSipICGiePIZ5MsWH7Xm67Zi6JZJrVH25jw/a9XDVvGh1dvYQDPkJ+Lz3ROH/7H0+ya187hmHwxl82M7qyBLfLiWlYTfCFjRNQFIVrF5xHPJHGMAwivQlUVbESSzJJbUUxrYcixJNpdN0g5PdSmE1qf3PblXzz3uuIJ9OEA14e+dqtubvanmgie9FUmNdQZ925YQ20zmuoo3HSGKuJrql8/8s3oWrWHbPToTF1XLXVp60qNB/oYMvu/QR9HmZMqGFb8wFQrAttbyzBpp37mFY3ijf+shlVVTh4qJu50+usbp3swGJ9bTkHD0VIpNLWLy1kdPa1dbFgRj1XzpuWmxTx0qr1HOzoBmDPgQ46IlGSaZ2MbrK39RCbd1ljQGG/h4mjKygI+cjoBu3Z/nmvx8k/f+UmFjVOIqMbHIrEcsn/QEcEIDfIHE+mORSJsqlpHybkXmdnt3XOmMDq9dv56bI36eqJcfBQhJ5onN37O0hnrK6IZDpN88FDrNti/Sr3vrYuovEkqYzOvvYuNja18NLKDwFY8+F2FsycQCxhTTyZPKYSt8dFJp3BoWl4XE6cDpWDHRG6e+O4XA40TeVXL65GUazxqngyTWekl4OHrNfy+LNv0JX9WaTl73xEZ0+Upj2t2Za61cUKCj6Pi6DPQ8DnQVEUCkNWn7zP685106iKwgsrPmTzTusYG4ZBJJYg6PeSSes4VJWiggDJdIZde9tQVNB1nb0HD6Gq1jadDgdOlwOX08G25oO4nQ5UVSGt63RGrNbwy6s38o//37MYJqTTVmtiytgqAO5aPJ8r5k4HrFanx+VCU61L20sr1lnnTXsnqYzO+FFluYkhFSVh2joj1mtyW624wqAPh8O6MeyJJQiH/BzsiKAqCmVFIX778jt43A4M0ySetI6tYRgYhsHm3futrjHD5Lv/d1l2oozVvbSt+QAVxSHcLgeR3gThgBcTiMVTHDgUoaaiiEQqQySaIJ3RSWcMkukMHpcze6NSxMQxlfjcLipLC9A0FZdT4/zJY3G7nKiqyviacupryvF73dmxHoU508dz4Xl1eN0uvB4nD915NS6ng5LCIPW15RSF/cyeNo6Mbk1YqM9eu6pKC2hp7WTW1HFDuuae9YnFNE2eeHEVTodG84EO7r1uIS6ng7Dfy3ubdlAY9PHMq+8BVtO2sqSAhTPqGVVeyD3XLWDi6Ap8bheNE0fjdDh4d0MTLqdmdcscihDwujnY0U0kO5i9ev02yopCxBJJFAVmTR3LG+99jG6YfPnmy2ja04aiKCx/eyP3fnoBv3h+JSjw0B1X88WbLiEc9BH0e5k9dRw+j5tLZk2mrbOHeDKV66Nf+/FuwCSeSOF2OcnoJl6Pk+qyQkIBL5pqXWjcLieKYg1UJlNpYtlxB8Mw+M/fLscwTT69qJGmPQfpiSUxgduumUc6Y80cKSkI8srqDblZRwtnTuCXL6wknkxRWhDkiRdXoaDgdjrxup089vSfUVU1e4FSCQd8ZHQ9OxhvdV+UFgZRFIWKkjAfbm1men0NxQUBCoJ+3t+0k3VbdhOJxnG7HLy7sYnFC2cACkGfx5qUMaOe4oIgG7fvJaPrFAR9zJ42jpLCIAD3L70EVYEFM+oBKC8Kcai7Nzson2Rj014OZJOQy+mgpqKIeDLNll37WbN+O+VFIaaMraaupozSwiAup8bYqlJuv2YeDk1l9rRxTK8bRUlBgJDfw6iyIm6/Zh4mVlfF1HHV/OfXb+ey2VNwOjQe++ZdLDp/EqqqMGVcFU6HxuSxVUyvG8UPH7wVgAmjy6mpKMLl0HjwjquYOq6Kmy6bBcCls6bw3kc7cWgqLqeD9z/eRTqdsWYOZbtfFUXhJ8vewDAMrr/4fB752q04HVY/u9vpYOak0VQUF3DpBZOyx2gRBUE/qqrw4G1XUlkcZkx1CdVlRSiKlVAM3SCj6zgcKu1dvTgdKnuyd/vReBJFUQj4PQR9HpZccj4XXzApd0EOZsegkukMKHCgvRuv20ldbTm3XT2PS2ZNRtM0a4Aea7JNd0+cdEbn1qvm0NUb4zNXzOYHX7mZURVWS+if/+pG/ukrN6EAF55XRzjgY/nbG1GA5v0dRLIz21RVxetxYpjWBIvrFs3E7XbicbsoLgjQfKDDGhMpCtG8vwOPy0kyO4humlbMybR1M+bQVJr3tVNREsbEZOW6Lexv7ySTsWZTtXf20NkdxetxMWfaeCqKw2iaiqYofO+BpfTGEmiqSm88STyZoqOrl0xGx8SkJxonlc7QE0tQXhym9VCE8ybUWLM5NatLLRzw4XI68Lgc7G/rpK6mjN641W3vdjp576Od1NWUYRjWjNV9bZ2UFAYxTZOPd+zjM1fMZuvu/azftoe0bjBlXDXNBw7RvL+DcMBDwOtGVVTe2dCUG1fd395FpDfO3tZOwBpXG4qzcozlJ8veZOvuA/TGE/jcLnrjSTRNxTQMqx9eVXE4VJyaRjKdyfWnKoqCpljTbn0eF0G/h5Dfy6597fh9bjwuJ22dEaaMq6ats4eObutEUVUFBQWf101n5PAPZPZNTU5n9KNi7BsQHDil81iONc2yT/9pmn37HDi90m4Dp3X2p2kqZnbasqIcno492HoDX1/f1NT+U4ZzUz8V5Yip133Tjc3soKrX40LXDUoKAkeMq/RNAx34OhjwHlhdXRqqYvV/64ZBOqPj0DTmz6hj8879dPZEs9OHs4Py2anUfeMVLocjN3W7vDiE22m1IrxuF1t3H2Dq+Go+amoh6PfQ3tWLQ1MxTdANg6KQn954Mje9vU9fV5hhmEcdw2O95woQ9HuIxlM4HCqaag3iZ3RrTKFvAMKhaWSy02uPtx8lW9+6rzHpf8r2TYN2OqzXkNZ1TMPMTbU1TGuqvKaCbkBxQYB4IkkilaGmrJA9rZ1HTWM3TBO300Eo4KO9q8cq+70oqmJ1EWc/bxnDIOh1k9YNzGy3nNrvc3XzFbN5e0MTB9q7soP1h49l3/E+1vk30LGnxCsYpjW253Y5cy1KODxWYhhW693s+yyo1rHq/xWBge9jyO89Yhylb9+O7PRmE5NAthvTGtu1WpnWVHCrK8+63phH7GPg1w/6vzZNUykOBzCBzkg0N8bi97j5zhdvoLs3xv/+2Qu5GaZul5N//OIN2ZbtcY7Z2ZhYhBBC5M9Z3xUmhBDizJLEIoQQwlaSWIQQQthKEosQQghbSWIRQghhK0ksQgghbCWJRQghhK0ksQghhLCVJBYhzrC2zggP/fuTNO+3fmW3qyfG3z36W7bs3p/nyISwhyQWIc6w0sIQSy69gJ899xapdIYnXljJ3Ol1TBxdme/QhLCF/KSLEHny2FN/pr2rB0VR+Ma9i3M/qy/ESCctFiHyZMGMCexr6+LiCyZLUhFnFUksQuRBIpXmqT+9y/zz6nnhrXVE48l8hySEbSSxCJEHTy1/l9GVxdy5eD7T60bxmz+uyXdIQthGEosQZ9i6Lc181NTCbdfMA+CmK2ax50AH72xsynNkQthDBu+FEELYSlosQgghbCWJRQghhK0ksQghhLCVJBYhhBC2ksQihBDCVpJYhBBC2EoSixBCCFtJYhFCCGGr/x+iAYXrUGE0bwAAAABJRU5ErkJggg==\n"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "rand_df.describe()"
      ],
      "metadata": {
        "id": "NHzFE9S7Bz09",
        "outputId": "8dae59d0-9e19-4d49-af84-a44f8af1fe8c",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 297
        }
      },
      "execution_count": 26,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "                x           y\n",
              "count  100.000000  100.000000\n",
              "mean   476.480000  511.660000\n",
              "std    290.246725  286.269253\n",
              "min     12.000000    0.000000\n",
              "25%    229.000000  275.000000\n",
              "50%    438.500000  551.500000\n",
              "75%    758.000000  749.500000\n",
              "max    981.000000  998.000000"
            ],
            "text/html": [
              "\n",
              "  <div id=\"df-85106d52-b3a2-470c-8237-10fd856c7999\">\n",
              "    <div class=\"colab-df-container\">\n",
              "      <div>\n",
              "<style scoped>\n",
              "    .dataframe tbody tr th:only-of-type {\n",
              "        vertical-align: middle;\n",
              "    }\n",
              "\n",
              "    .dataframe tbody tr th {\n",
              "        vertical-align: top;\n",
              "    }\n",
              "\n",
              "    .dataframe thead th {\n",
              "        text-align: right;\n",
              "    }\n",
              "</style>\n",
              "<table border=\"1\" class=\"dataframe\">\n",
              "  <thead>\n",
              "    <tr style=\"text-align: right;\">\n",
              "      <th></th>\n",
              "      <th>x</th>\n",
              "      <th>y</th>\n",
              "    </tr>\n",
              "  </thead>\n",
              "  <tbody>\n",
              "    <tr>\n",
              "      <th>count</th>\n",
              "      <td>100.000000</td>\n",
              "      <td>100.000000</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>mean</th>\n",
              "      <td>476.480000</td>\n",
              "      <td>511.660000</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>std</th>\n",
              "      <td>290.246725</td>\n",
              "      <td>286.269253</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>min</th>\n",
              "      <td>12.000000</td>\n",
              "      <td>0.000000</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>25%</th>\n",
              "      <td>229.000000</td>\n",
              "      <td>275.000000</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>50%</th>\n",
              "      <td>438.500000</td>\n",
              "      <td>551.500000</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>75%</th>\n",
              "      <td>758.000000</td>\n",
              "      <td>749.500000</td>\n",
              "    </tr>\n",
              "    <tr>\n",
              "      <th>max</th>\n",
              "      <td>981.000000</td>\n",
              "      <td>998.000000</td>\n",
              "    </tr>\n",
              "  </tbody>\n",
              "</table>\n",
              "</div>\n",
              "      <button class=\"colab-df-convert\" onclick=\"convertToInteractive('df-85106d52-b3a2-470c-8237-10fd856c7999')\"\n",
              "              title=\"Convert this dataframe to an interactive table.\"\n",
              "              style=\"display:none;\">\n",
              "        \n",
              "  <svg xmlns=\"http://www.w3.org/2000/svg\" height=\"24px\"viewBox=\"0 0 24 24\"\n",
              "       width=\"24px\">\n",
              "    <path d=\"M0 0h24v24H0V0z\" fill=\"none\"/>\n",
              "    <path d=\"M18.56 5.44l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94zm-11 1L8.5 8.5l.94-2.06 2.06-.94-2.06-.94L8.5 2.5l-.94 2.06-2.06.94zm10 10l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94z\"/><path d=\"M17.41 7.96l-1.37-1.37c-.4-.4-.92-.59-1.43-.59-.52 0-1.04.2-1.43.59L10.3 9.45l-7.72 7.72c-.78.78-.78 2.05 0 2.83L4 21.41c.39.39.9.59 1.41.59.51 0 1.02-.2 1.41-.59l7.78-7.78 2.81-2.81c.8-.78.8-2.07 0-2.86zM5.41 20L4 18.59l7.72-7.72 1.47 1.35L5.41 20z\"/>\n",
              "  </svg>\n",
              "      </button>\n",
              "      \n",
              "  <style>\n",
              "    .colab-df-container {\n",
              "      display:flex;\n",
              "      flex-wrap:wrap;\n",
              "      gap: 12px;\n",
              "    }\n",
              "\n",
              "    .colab-df-convert {\n",
              "      background-color: #E8F0FE;\n",
              "      border: none;\n",
              "      border-radius: 50%;\n",
              "      cursor: pointer;\n",
              "      display: none;\n",
              "      fill: #1967D2;\n",
              "      height: 32px;\n",
              "      padding: 0 0 0 0;\n",
              "      width: 32px;\n",
              "    }\n",
              "\n",
              "    .colab-df-convert:hover {\n",
              "      background-color: #E2EBFA;\n",
              "      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);\n",
              "      fill: #174EA6;\n",
              "    }\n",
              "\n",
              "    [theme=dark] .colab-df-convert {\n",
              "      background-color: #3B4455;\n",
              "      fill: #D2E3FC;\n",
              "    }\n",
              "\n",
              "    [theme=dark] .colab-df-convert:hover {\n",
              "      background-color: #434B5C;\n",
              "      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);\n",
              "      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));\n",
              "      fill: #FFFFFF;\n",
              "    }\n",
              "  </style>\n",
              "\n",
              "      <script>\n",
              "        const buttonEl =\n",
              "          document.querySelector('#df-85106d52-b3a2-470c-8237-10fd856c7999 button.colab-df-convert');\n",
              "        buttonEl.style.display =\n",
              "          google.colab.kernel.accessAllowed ? 'block' : 'none';\n",
              "\n",
              "        async function convertToInteractive(key) {\n",
              "          const element = document.querySelector('#df-85106d52-b3a2-470c-8237-10fd856c7999');\n",
              "          const dataTable =\n",
              "            await google.colab.kernel.invokeFunction('convertToInteractive',\n",
              "                                                     [key], {});\n",
              "          if (!dataTable) return;\n",
              "\n",
              "          const docLinkHtml = 'Like what you see? Visit the ' +\n",
              "            '<a target=\"_blank\" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'\n",
              "            + ' to learn more about interactive tables.';\n",
              "          element.innerHTML = '';\n",
              "          dataTable['output_type'] = 'display_data';\n",
              "          await google.colab.output.renderOutput(dataTable, element);\n",
              "          const docLink = document.createElement('div');\n",
              "          docLink.innerHTML = docLinkHtml;\n",
              "          element.appendChild(docLink);\n",
              "        }\n",
              "      </script>\n",
              "    </div>\n",
              "  </div>\n",
              "  "
            ]
          },
          "metadata": {},
          "execution_count": 26
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "To make a box-n-whisker plot use:\n",
        "```\n",
        "sns.boxplot(rand_df.x)\n",
        "```\n",
        "or\n",
        "```\n",
        "sns.boxplot(rand_df.y)\n",
        "```\n",
        "However, it doesn't show you the distribution within the data itself"
      ],
      "metadata": {
        "id": "fNS5IXc-B_lo"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "sns.boxplot(rand_df.x)"
      ],
      "metadata": {
        "id": "Wtb73mZ0B3Ha",
        "outputId": "074a44e1-5c97-4632-be40-51d3c09c252c",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 353
        }
      },
      "execution_count": 27,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stderr",
          "text": [
            "/usr/local/lib/python3.7/dist-packages/seaborn/_decorators.py:43: FutureWarning: Pass the following variable as a keyword arg: x. From version 0.12, the only valid positional argument will be `data`, and passing other arguments without an explicit keyword will result in an error or misinterpretation.\n",
            "  FutureWarning\n"
          ]
        },
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "<matplotlib.axes._subplots.AxesSubplot at 0x7f7fef286b90>"
            ]
          },
          "metadata": {},
          "execution_count": 27
        },
        {
          "output_type": "display_data",
          "data": {
            "text/plain": [
              "<Figure size 432x288 with 1 Axes>"
            ],
            "image/png": "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\n"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "sns.boxplot(rand_df.y)"
      ],
      "metadata": {
        "id": "6NkoGi5jCc_E",
        "outputId": "c65dbd8f-b474-4205-9bca-829015e0fb10",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 353
        }
      },
      "execution_count": 29,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stderr",
          "text": [
            "/usr/local/lib/python3.7/dist-packages/seaborn/_decorators.py:43: FutureWarning: Pass the following variable as a keyword arg: x. From version 0.12, the only valid positional argument will be `data`, and passing other arguments without an explicit keyword will result in an error or misinterpretation.\n",
            "  FutureWarning\n"
          ]
        },
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "<matplotlib.axes._subplots.AxesSubplot at 0x7f7fef64f390>"
            ]
          },
          "metadata": {},
          "execution_count": 29
        },
        {
          "output_type": "display_data",
          "data": {
            "text/plain": [
              "<Figure size 432x288 with 1 Axes>"
            ],
            "image/png": "iVBORw0KGgoAAAANSUhEUgAAAWAAAAEJCAYAAACqmv3eAAAABHNCSVQICAgIfAhkiAAAAAlwSFlzAAALEgAACxIB0t1+/AAAADh0RVh0U29mdHdhcmUAbWF0cGxvdGxpYiB2ZXJzaW9uMy4yLjIsIGh0dHA6Ly9tYXRwbG90bGliLm9yZy+WH4yJAAANDklEQVR4nO3dW3CU5R3H8d/mnN3sJiEBklBIAiQcCoHAyClB1FJrFUQcq9MOIyMeemHHTp1hOtVO24tOD0PHi3pV7aRWsSNah8EDCtKRgxJJKWJCOAQCgSScBJJsSDan3e1FIA5qazaw+2d3v5+77GzyPs8+2e8+2Xc36/B3NwcFAIi4BOsBAEC8IsAAYIQAA4ARAgwARggwABhJCuXKHV7viA/kcDgUDMbXCy6Yc3xgzvHheubskOTxeL5yecR2wB63O1KHumkw5/jAnOPD9cw5IeHrU8tTEABghAADgBECDABGCDAAGCHAAGCEAAOAEQIMAEYIMAAYIcAAYIQAA4ARAgwARggwABghwABghAADgBECDABGCDAAGCHAAGCEAAOAEQIMAEZC+lBO3BxWrVlrPQTEgPVV66yHEPfYAQOAEXbAUcy7+GnrIcQEz67nJMXP7Xl1vrDHDhgAjBBgADBCgAHACAEGACMEGACMEGAAMEKAAcAIAQYAIwQYAIwQYAAwQoABwAgBBgAjBBgAjBBgADBCgAHACAEGACMEGACMEGAAMEKAAcAIAQYAIwQYAIwQYAAwQoABwAgBBgAjBBgAjBBgADBCgAHACAEGACMEGACMEGAAMEKAAcAIAQYAIwQYAIwQYAAwQoABwAgBBgAjBBgAjBBgADBCgAHACAEGACMEGACMEGAAMBKRAK9as1bLH/hxJA4FADfUqjVrtWrN2rD8bHbAAGCEAAOAEQIMAEYIMAAYIcAAYIQAA4ARAgwARggwABghwABghAADgBECDABGCDAAGCHAAGCEAAOAEQIMAEYIMAAYIcAAYIQAA4ARAgwARggwABghwABghAADgBECDABGCDAAGCHAAGCEAAOAEQIMAEYIMAAYIcAAYIQAA4ARAgwARggwABghwABghAADgBECDABGCDAAGCHAAGCEAAOAEQIMAEYIMAAYIcAAYCQpkgdbtWZtJA8H4P/g/mjvGwO8a98R7fq0QZK0etkCZaSnhn1QABAPvjHAi+dM0eI5UyRJHV7vdR1sfdW66/r+aJPp8Vz3bfZ12LngRrie+2O4frdvRuG8v/EcMAAYIcAAYIQAA4ARAgwARggwABghwABghAADgBECDABGCDAAGCHAAGCEAAOAEQIMAEYIMAAYIcAAYIQAA4ARAgwARggwABghwABghAADgBECDABGCDAAGCHAAGCEAAOAEQIMAEYIMAAYIcAAYIQAA4ARAgwARggwABghwABghAADgBECDABGCDAAGCHAAGCEAAOAEQIMAEYIMAAYIcAAYIQAA4ARAgwARggwABghwABgJCkSB1lftU6ZHo86vN5IHA4Abpj1VevC9rPZAQOAEQIMAEYIMAAYIcAAYIQAA4ARAgwARggwABghwABghAADgBECDABGCDAAGCHAAGCEAAOAEQIMAEYIMAAYIcAAYIQAA4ARAgwARggwABghwABghAADgBECDABGCDAAGCHAAGCEAAOAEQIMAEYIMAAYIcAAYIQAA4ARAgwARggwABghwABghAADgBECDABGCDAAGCHAAGCEAAOAEQIMAEYIMAAYIcAAYIQAA4CRJOsBYOQ8u56zHkJM4fZEpLEDBgAj7ICj0PqqddZD+J8yPR51eL3Ww4ioeJwzbgx2wABghAADgBECDABGCDAAGCHAAGCEAAOAEQIMAEYIMAAYIcAAYIQAA4ARAgwARggwABghwABghAADgBECDABGCDAAGCHAAGCEAAOAEQIMAEYIMAAYcfi7m4PDvbLX61VCwsia3dndI7czbUTfG62Yc3xgzvHheuYcCATk8Xi+cnlIn4r8dT9guP684UM98+jyEX9/NGLO8YE5x4dwzJmnIADACAEGACMRC/Di8tJIHeqmwZzjA3OOD+GYc0gn4QAANw5PQQCAEQIMAEZCehnaSNQ3tuj1rTUKBIOqmF2iuxaVhfuQEXHJ26WX3tolb5dPDjlUWV6q78ybri5fr17cuF0X2y8rJytDj6+8Ta70VAWDQb2+tUYHGluUkpyk1csqNSE/x3oaIxIIBPT7qneU5XbqyYeW6kJ7p/66cYe6fL2akJejR1YsVlJiovoH/HrprV06dfaiXOmpemzlEuVmua2HH7Lunl698u5unf68TQ459PCyCo3NyYzpdd62p14f7z8qh0MqGJ2t1csr1HHZF1Pr/PLbH6nuWIvcrjT96on7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\n"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "A violin plot shows the same as a box plot as well as the distribution:\n",
        "```\n",
        "sns.violinplot(rand_df.x)\n",
        "```\n",
        "or\n",
        "```\n",
        "sns.violinplot(rand_df.y)\n",
        "```"
      ],
      "metadata": {
        "id": "0zJXNII6CMDL"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "sns.violinplot(rand_df.x)"
      ],
      "metadata": {
        "id": "q5RoH4gcCS-V",
        "outputId": "8c4185b9-8bef-407d-bf58-4051a06e1fe8",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 353
        }
      },
      "execution_count": 28,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stderr",
          "text": [
            "/usr/local/lib/python3.7/dist-packages/seaborn/_decorators.py:43: FutureWarning: Pass the following variable as a keyword arg: x. From version 0.12, the only valid positional argument will be `data`, and passing other arguments without an explicit keyword will result in an error or misinterpretation.\n",
            "  FutureWarning\n"
          ]
        },
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "<matplotlib.axes._subplots.AxesSubplot at 0x7f7ff3ef0090>"
            ]
          },
          "metadata": {},
          "execution_count": 28
        },
        {
          "output_type": "display_data",
          "data": {
            "text/plain": [
              "<Figure size 432x288 with 1 Axes>"
            ],
            "image/png": "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\n"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "sns.violinplot(rand_df.y)"
      ],
      "metadata": {
        "id": "KJU3h4x_CgNa",
        "outputId": "29431ce2-8ffe-4e84-8efb-c87b40e654c0",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 299
        }
      },
      "execution_count": 32,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "<matplotlib.axes._subplots.AxesSubplot at 0x7f7fef006690>"
            ]
          },
          "metadata": {},
          "execution_count": 32
        },
        {
          "output_type": "display_data",
          "data": {
            "text/plain": [
              "<Figure size 432x288 with 1 Axes>"
            ],
            "image/png": "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\n"
          },
          "metadata": {}
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "**Bootstrapping**: Sampling with replacement; make a data set of the same size, but you have potential to get the same data point again. (I.e., pick ball out of bin, record it, place it back in same bin & try again)\n",
        "\n",
        "**Jacknifying**: Sampling without replacement; make smaller size data set & randomly choose which original data points are being included. (I.e., pick ball out of bin, record it, place it on the side & pick from remaining balls in bin)\n",
        "\n",
        "**_Note_**: Not identifying the outliars."
      ],
      "metadata": {
        "id": "i1uN5TEeDDT_"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "!pip install py3Dmol\n",
        "import py3Dmol\n",
        "\n",
        "view=py3Dmol.view(query=\"pdb:2D2M\")\n",
        "view.setStyle({\"cartoon\":{\"color\":\"spectrum\"}})\n",
        "view"
      ],
      "metadata": {
        "id": "DyoY0AWYEHiy",
        "outputId": "ca15f19b-5b93-4fec-b946-c4163122ce64",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 548
        }
      },
      "execution_count": 44,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Looking in indexes: https://pypi.org/simple, https://us-python.pkg.dev/colab-wheels/public/simple/\n",
            "Requirement already satisfied: py3Dmol in /usr/local/lib/python3.7/dist-packages (1.8.1)\n"
          ]
        },
        {
          "output_type": "display_data",
          "data": {
            "application/3dmoljs_load.v0": "<div id=\"3dmolviewer_16632782776696022\"  style=\"position: relative; width: 640px; height: 480px\">\n        <p id=\"3dmolwarning_16632782776696022\" style=\"background-color:#ffcccc;color:black\">You appear to be running in JupyterLab (or JavaScript failed to load for some other reason).  You need to install the 3dmol extension: <br>\n        <tt>jupyter labextension install jupyterlab_3dmol</tt></p>\n        </div>\n<script>\n\nvar loadScriptAsync = function(uri){\n  return new Promise((resolve, reject) => {\n    var tag = document.createElement('script');\n    tag.src = uri;\n    tag.async = true;\n    tag.onload = () => {\n      resolve();\n    };\n  var firstScriptTag = document.getElementsByTagName('script')[0];\n  firstScriptTag.parentNode.insertBefore(tag, firstScriptTag);\n});\n};\n\nif(typeof $3Dmolpromise === 'undefined') {\n$3Dmolpromise = null;\n  $3Dmolpromise = loadScriptAsync('https://cdn.jsdelivr.net/npm/3dmol@latest/build/3Dmol-min.min.js');\n}\n\nvar viewer_16632782776696022 = null;\nvar warn = document.getElementById(\"3dmolwarning_16632782776696022\");\nif(warn) {\n    warn.parentNode.removeChild(warn);\n}\n$3Dmolpromise.then(function() {\nviewer_16632782776696022 = $3Dmol.createViewer($(\"#3dmolviewer_16632782776696022\"),{backgroundColor:\"white\"});\n$3Dmol.download(\"pdb:2D2M\", viewer_16632782776696022, {}, function() {\nviewer_16632782776696022.zoomTo();\n\tviewer_16632782776696022.setStyle({\"cartoon\": {\"color\": \"spectrum\"}});\nviewer_16632782776696022.render();\n})\n});\n</script>",
            "text/html": [
              "<div id=\"3dmolviewer_16632782776696022\"  style=\"position: relative; width: 640px; height: 480px\">\n",
              "        <p id=\"3dmolwarning_16632782776696022\" style=\"background-color:#ffcccc;color:black\">You appear to be running in JupyterLab (or JavaScript failed to load for some other reason).  You need to install the 3dmol extension: <br>\n",
              "        <tt>jupyter labextension install jupyterlab_3dmol</tt></p>\n",
              "        </div>\n",
              "<script>\n",
              "\n",
              "var loadScriptAsync = function(uri){\n",
              "  return new Promise((resolve, reject) => {\n",
              "    var tag = document.createElement('script');\n",
              "    tag.src = uri;\n",
              "    tag.async = true;\n",
              "    tag.onload = () => {\n",
              "      resolve();\n",
              "    };\n",
              "  var firstScriptTag = document.getElementsByTagName('script')[0];\n",
              "  firstScriptTag.parentNode.insertBefore(tag, firstScriptTag);\n",
              "});\n",
              "};\n",
              "\n",
              "if(typeof $3Dmolpromise === 'undefined') {\n",
              "$3Dmolpromise = null;\n",
              "  $3Dmolpromise = loadScriptAsync('https://cdn.jsdelivr.net/npm/3dmol@latest/build/3Dmol-min.min.js');\n",
              "}\n",
              "\n",
              "var viewer_16632782776696022 = null;\n",
              "var warn = document.getElementById(\"3dmolwarning_16632782776696022\");\n",
              "if(warn) {\n",
              "    warn.parentNode.removeChild(warn);\n",
              "}\n",
              "$3Dmolpromise.then(function() {\n",
              "viewer_16632782776696022 = $3Dmol.createViewer($(\"#3dmolviewer_16632782776696022\"),{backgroundColor:\"white\"});\n",
              "$3Dmol.download(\"pdb:2D2M\", viewer_16632782776696022, {}, function() {\n",
              "viewer_16632782776696022.zoomTo();\n",
              "\tviewer_16632782776696022.setStyle({\"cartoon\": {\"color\": \"spectrum\"}});\n",
              "viewer_16632782776696022.render();\n",
              "})\n",
              "});\n",
              "</script>"
            ]
          },
          "metadata": {}
        },
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "<py3Dmol.view at 0x7f7fef280bd0>"
            ]
          },
          "metadata": {},
          "execution_count": 44
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [],
      "metadata": {
        "id": "4BCDVosiFH97"
      },
      "execution_count": null,
      "outputs": []
    }
  ]
}
