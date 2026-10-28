# Banking Operations

A small Java console exercise that simulates a bank account menu: check the balance, transfer money out, receive money in. It is one of my first Java programs, and it is a single file, `src/Challenge.java`.

## What it does

The account is hardcoded (a checking account with a starting balance of 1,599.99). A `while` loop shows a menu until you choose to quit:

```
1 - Consultar saldo      check balance
2 - Transferir valor     transfer out, refused if it exceeds the balance
3 - Receber valor        receive money
4 - Sair                 exit
```

Menu text is in Portuguese. It was my first pass at variables, `Scanner` input, loops, conditionals and Java text blocks.

## Run it

Requires JDK 15 or newer (text blocks).

```bash
git clone https://github.com/victorhubarb/banking-operations.git
cd banking-operations
javac -d out src/Challenge.java
java -cp out Challenge
```

## Known gaps

It is a beginner exercise and it shows:

- Negative amounts are accepted, so "transfer -100" adds money.
- Typing something that is not a number crashes the program with an exception.
- Everything lives in `main`, with no classes, and nothing is saved between runs.

For the object-oriented version of the same idea, with classes, inheritance, exceptions and file persistence, see [digiwallet](https://github.com/victorhubarb/digiwallet).

---

Victor Hugo Barbosa · [GitHub](https://github.com/victorhubarb) · [LinkedIn](https://www.linkedin.com/in/victorhbarbosa/)
