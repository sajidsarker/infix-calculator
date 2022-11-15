# infix-calculator

**Description:** CLI calculator which evaluates infix expressions.

**Author:** Sajid Al Sanai

**License:** MIT License

When writing mathematical expressions, we generally utilise what is known as infix notation. In infix form, an operator is written in between the two operands on which the operation is to be evaluated.

Evaluation of these operators is then in the order of **PEMDAS**:

1. Parentheses
2. Exponents
3. Multiplication
4. Division
5. Addition
6. Subtraction

Given that the computer is naive, we must resort to alogithmically evaluating a mathematical infix expression by converting it first into either postfix or prefix notation which is easier for a computer to process systematically.

My code for a CLI infix calculator `calculator.py` takes an infix expression as a string at runtime in the terminal from where it is called, performs validation checks to ensure that it is a valid infix expression, algorithmically converts it into a postfix expression, then evaluates the postfix expression to yield the correct answer.

## Usage

To clone this repository, open terminal and issue the following commands:

```bash
git clone https://github.com/sajidsarker/infix-calculator.git
cd infix-calculator
```

To run the `calculator.py` file as an executable program, you would need to change its permissions as follows:

```bash
chmod +x calculator.py
./calculator.py "23*16+5/10+2"
```

To run the `calculator.py` file using Python, you would need to reference Python as the executing program as follows:

```bash
python calculator.py "23*16+5/10+2"
```
