[session_7.ipynb](https://github.com/user-attachments/files/31996712/session_7.ipynb)
{
  "nbformat": 4,
  "nbformat_minor": 0,
  "metadata": {
    "colab": {
      "provenance": []
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
      "cell_type": "code",
      "source": [
        "age = int(input(\"Enter your age: \"))\n",
        "if age >= 18:\n",
        "    print(\"Eligible for IPL ticket booking\")\n",
        "else:\n",
        "    print(\"Not eligible\")"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "Ue-sTr-AKbMd",
        "outputId": "ed6436a4-39d5-43d3-b22f-9aed90c6de19"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Enter your age: 18\n",
            "Eligible for IPL ticket booking\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "number_of_followers = int(input(\"enter the number of followers: \"))\n",
        "if number_of_followers < 10000:\n",
        "    print(\"Micro Influencer\")\n",
        "elif number_of_followers >= 10000 and number_of_followers <= 100000:\n",
        "    print(\"Rising Star\")\n",
        "else:\n",
        "    print(\"Celebrity\")"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "dZhkJEwqKbQf",
        "outputId": "bef6a7f9-87de-4dee-888b-6ecb0a5c1d99"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "enter the number of followers: 100000\n",
            "Rising Star\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "total_amount = int(input(\"Enter the total amount: \"))\n",
        "if total_amount > 299:\n",
        "    print(\"Apply Free Delivery\")\n",
        "elif total_amount >= 200 and total_amount <= 299:\n",
        "    print(\"Add more items for free delivery\")\n",
        "else:\n",
        "    print(\"Delivery charges apply\")"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "Mb6R9ApjKbUS",
        "outputId": "b51985e3-6797-4b7e-8392-04261f5ff0f4"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Enter the total amount: 300\n",
            "Apply Free Delivery\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "# Write a Python program using nested if statements: take a user's entered Flipkart cart value and payment method ('UPI', 'Card', 'Cash').\n",
        "# If the cart value is above 1000 and payment method is 'UPI', print 'Eligible for 10% cashback';\n",
        "# if above 1000 and payment is not 'UPI', print 'Eligible for 5% cashback'; else print 'No cashback'"
      ],
      "metadata": {
        "id": "AT87-jSCKbWT"
      },
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [
        "Flipcart_cart_value = int(input(\"Enter the Flipkart cart value: \"))\n",
        "payment_method = input(\"Enter the payment method: \")\n",
        "if Flipcart_cart_value > 1000:\n",
        "    if payment_method == \"UPI\":\n",
        "        print(\"Eligible for 10% cashback\")\n",
        "    else:\n",
        "        print(\"Eligible for 5% cashback\")\n",
        "else:\n",
        "    print(\"No cashback\")"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "JhcLBxcHNk_N",
        "outputId": "3f8cb798-17d5-4b89-f61b-1c451a0579e8"
      },
      "execution_count": null,
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "Enter the Flipkart cart value: 890\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [],
      "metadata": {
        "id": "NoIA44pBNk74"
      },
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [],
      "metadata": {
        "id": "dSrEdfVsNk5k"
      },
      "execution_count": null,
      "outputs": []
    },
    {
      "cell_type": "code",
      "source": [],
      "metadata": {
        "id": "5RG-59wNNkv0"
      },
      "execution_count": null,
      "outputs": []
    }
  ]
}
