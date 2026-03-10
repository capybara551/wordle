{
  "nbformat": 4,
  "nbformat_minor": 0,
  "metadata": {
    "colab": {
      "provenance": [],
      "authorship_tag": "ABX9TyMoLcC4GowYFICgQa5luO4C",
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
        "<a href=\"https://colab.research.google.com/github/capybara551/wordle/blob/main/Day%202.md\" target=\"_parent\"><img src=\"https://colab.research.google.com/assets/colab-badge.svg\" alt=\"Open In Colab\"/></a>"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": 32,
      "metadata": {
        "id": "3hh9FRC1fU8F"
      },
      "outputs": [],
      "source": [
        "import random"
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "words = [\n",
        "\"abuse\",\"adapt\",\"admit\",\"adopt\",\"adult\",\"agent\",\"anger\",\"argue\",\"arise\",\"aside\",\n",
        "\"avoid\",\"award\",\"aware\",\"basic\",\"basis\",\"beach\",\"begin\",\"birth\",\"black\",\"blame\",\n",
        "\"blind\",\"brain\",\"brand\",\"bread\",\"break\",\"bring\",\"broad\",\"build\",\"carry\",\"catch\",\n",
        "\"cause\",\"chain\",\"chair\",\"chart\",\"check\",\"chief\",\"child\",\"claim\",\"class\",\"clean\",\n",
        "\"clear\",\"clerk\",\"close\",\"coach\",\"coast\",\"could\",\"count\",\"court\",\"cover\",\"craft\",\n",
        "\"crash\",\"cream\",\"crime\",\"cross\",\"crowd\",\"daily\",\"dance\",\"death\",\"delay\",\"depth\",\n",
        "\"doubt\",\"dozen\",\"draft\",\"drama\",\"dream\",\"dress\",\"drink\",\"drive\",\"earth\",\"empty\",\n",
        "\"enemy\",\"enjoy\",\"enter\",\"equal\",\"error\",\"event\",\"faith\",\"fault\",\"field\",\"final\",\n",
        "\"focus\",\"force\",\"frame\",\"fresh\",\"front\",\"fruit\",\"giant\",\"glass\",\"grant\",\"grass\",\n",
        "\"great\",\"group\",\"guard\",\"guess\",\"guest\",\"guide\",\"habit\",\"happy\",\"heart\",\"heavy\"\n",
        "]"
      ],
      "metadata": {
        "id": "fVh94K0MR5NO"
      },
      "execution_count": 33,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "answer = random.choice(words)"
      ],
      "metadata": {
        "id": "1tGQgnV0SLVm"
      },
      "execution_count": 34,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "guess = input()"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "o55XDOWIVunr",
        "outputId": "ec2c738d-35d0-4f81-8318-4f69254dd7aa"
      },
      "execution_count": 35,
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "event\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "if input == answer:\n",
        "    print (\"You are right.\")\n",
        "else:\n",
        "  print (\"You are false.\")"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "9BOnMHdPXOlu",
        "outputId": "1b629f33-2cd9-429f-914c-329655be48b0"
      },
      "execution_count": 36,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "You are false.\n"
          ]
        }
      ]
    }
  ]
}