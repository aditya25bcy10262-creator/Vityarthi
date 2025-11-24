 Vityarthi
 # Basic Subscription Manager (List Version)

## Overview
This is a command-line interface (CLI) tool built in Python designed to help users track their monthly recurring expenses. It allows users to input subscription names and costs, validates the input, and provides a summary of total monthly spending.

## Features
* **Dynamic Data Entry:** Users can add as many subscriptions as needed.
* **Input Validation:**
    * Ensures cost inputs are valid numbers.
    * Prevents negative numbers from being entered.
    * Handles empty inputs gracefully.
* **Financial Summary:** Calculates and displays the total monthly cost.
* **Formatted Output:** Displays currency to two decimal places for readability.

## Technologies Used
* **Language:** Python 3.x
* **Libraries:** Standard Library (no external installations required)

## Steps to Install & Run

1.  **Prerequisites:** Ensure you have Python installed on your machine. You can check this by running:
    ```bash
    python --version
    ```
2.  **Download:** Download the `subscription_manager.py` file to your local machine.
3.  **Run the Application:** Open your terminal or command prompt, navigate to the folder containing the file, and run:
    ```bash
    python subscription_manager.py
    ```

## Instructions for Testing
To verify the program is working correctly, follow these test cases:

1.  **Standard Entry:**
    * Run the script.
    * Enter `Netflix` as the name.
    * Enter `15.99` as the cost.
    * *Result:* The item should be added to the list.

2.  **Error Handling (Non-Numeric):**
    * When asked for cost, type `ten dollars`.
    * *Result:* The program should display "Invalid input" and ask again.

3.  **Error Handling (Negative Cost):**
    * When asked for cost, type `-5`.
    * *Result:* The program should warn that costs cannot be negative and ask again.

4.  **Completion:**
    * Type `done` at the name prompt.
    * *Result:* The program prints a summary list and the total monthly cost.

## Screenshots
*(Place a screenshot of your terminal running the code here. For example:)*
![App Screenshot](path_to_your_screenshot.png)
