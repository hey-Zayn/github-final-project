## Simple Interest Calculator

A lightweight, terminal-based Bash script designed to quickly compute simple interest based on user-provided inputs. This project is created for evaluation purposes to demonstrate proficiency in basic shell scripting, handling user input, and executing arithmetic operations within a Linux environment.

---

### Features
* **Interactive CLI:** Prompts the user step-by-step for inputs.
* **Input Validation:** Clear field prompts for all core financial variables.
* **Efficient Computation:** Instantly calculates the total simple interest accrued over a given timeframe.

---

### Input Fields
To compute the interest, the script requires the following inputs from the user:
1. **Principal:** The initial amount of money invested or borrowed.
2. **Rate of Interest:** The annual interest rate expressed as a percentage.
3. **Time Period:** The duration of the investment or loan expressed in years.

---

### Mathematical Formula
The script calculates simple interest using the standard financial formula:

$$A = \frac{P \times R \times T}{100}$$

Where:
* $A$ = Simple Interest Accrued
* $P$ = Principal Amount
* $R$ = Annual Interest Rate (%)
* $T$ = Time Period (Years)

---

### How to Run the Script
1. Clone the repository and navigate into the project directory.
2. Grant execution permissions to the script:
```bash
   chmod +x simple-interest.sh
