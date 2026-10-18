# Mortgage Calculator

A simple Java console app that calculates the monthly payment for a fixed-rate mortgage.

## Requirements

- JDK 22 (the project is configured for JDK 22 in IntelliJ IDEA)

## Run in IntelliJ IDEA

1. Clone this repository.
2. Open the `mortgage-calculator` folder in IntelliJ IDEA.
3. If prompted, select an installed JDK 22.
4. Open `src/com/salikhussain/Main.java` and run `Main`.

## Run from a terminal

From the project root, compile and run:

```bash
javac -d out src/com/salikhussain/Main.java
java -cp out com.salikhussain.Main
```

## Inputs

Enter the loan principal, annual interest rate as a percentage (for example, enter `5` for 5%), and loan term in years. The program displays the monthly mortgage payment. The currency symbol and number formatting follow your system's locale.
