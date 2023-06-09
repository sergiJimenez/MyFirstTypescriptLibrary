
# Typescript Simple Calculator

Hello there! My name is Sergi and I present you this library called Simple Calculator. It is a library that contains four functions. You can add, subtract, multiply and divide in your Typescript project.

Below you will find different sections that will guide you to start using it.
## Installation

To install the Simple Calculator library you should to execute the following command in the terminal of your project:

```bash
  cd <your project>
  npm i myfirsttypescriptlibrary
```
## How to Import

In order to use the library in your Typescript project you have to import the library in the file that you want to use it in the following way:

```bash
  import { Calculator } from 'myfirsttypescriptlibrary/lib/calculator';
```
## Functions Explanation

The functions found within the library are the following:

#### addNumbers()
In the addNumbers() function you will add two numbers passed by parameter:
```bash
  public addNumbers(firstNumber: number, secondNumber: number) {
    return firstNumber + secondNumber;
  }
```
#### substractNumbers()
In the substractNumbers() function you subtract two numbers passed by parameter:
```bash
  public substractNumbers(firstNumber: number, secondNumber: number) {
    return firstNumber - secondNumber;
  }
```
#### multiplyNumbers()
In the multiplyNumbers() function you multiply two numbers passed by parameter:
```bash
  public multiplyNumbers(firstNumber: number, secondNumber: number) {
    return firstNumber * secondNumber;
  }
```
#### divideNumbers()
In the divideNumbers() function you will divide two numbers passed by parameter. If the second number is 0 the function cannot be executed because it cannot be divided by 0:
```bash
  public divideNumbers(firstNumber: number, secondNumber: number) {
    if (secondNumber !== 0) {
      return firstNumber / secondNumber;
    } else {
      return 'You can not divide with 0... Try to type another one.';
    }
  }
```
## Example

An example of how this library could be used:

```bash
  import { Calculator } from 'myfirsttypescriptlibrary/lib/calculator';

  const calculator = new Calculator();

  console.log(calculator.addNumbers(2,2));
  console.log(calculator.substractNumbers(2,2));
  console.log(calculator.multiplyNumbers(2,2));
  console.log(calculator.divideNumbers(2,2));
```
## Run

To execute the application is exactly the same as when you want to execute a Typescript file:

```bash
  tsc <your Typescript file name>.ts
  node <your Javascript file name>.js
```