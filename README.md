# Store Management and Billing GUI

This Java program, "Store Management and Billing GUI," provides a graphical user interface (GUI) for managing a store's inventory and performing billing operations. It allows users to select products, specify quantities, and calculates the total cost of their purchases, considering discounts.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [How to Use](#how-to-use)
- [Requirements](#requirements)
- [Installation](#installation)
## Introduction

This program offers a user-friendly way to manage a store's inventory and perform billing tasks. It includes features such as displaying available products, purchasing items, calculating total costs, and applying discounts based on the total price. If a product's quantity is low, it provides a notification to the user.

## Features

- Display a list of available products and their prices.
- Allow users to select a product and specify the quantity they want to purchase.
- Calculate the total cost of the selected items.
- Apply discounts based on the total price:
  - 10% discount for a total price of $1,700 or more.
  - 5% discount for a total price of $1,000 or more.
  - No discount for prices below $1,000.
- Display a notification if the product's quantity is insufficient.
- Provide an option to exit the program.

## How to Use

1. Launch the program by running the `main` method in the `StoreManagementAndBillingGUI` class.
2. The GUI window will appear, displaying available products and input fields for product name and quantity.
3. Enter the name of the product you want to purchase in the "Enter product name" field.
4. Enter the quantity of the product you wish to purchase in the "Enter quantity" field.
5. Click the "Purchase" button to calculate the total cost and view details.
6. If the product's quantity is insufficient, you'll be notified.
7. To exit the program, click the "Exit" button.

## Requirements

- Java Development Kit (JDK) 8 or later.
- A Java IDE or compiler to run the program.

## Installation

1. Ensure you have Java and a development environment set up.
2. Copy and paste the provided code into your Java IDE or save it as a `.java` file.
3. Compile and run the program.

