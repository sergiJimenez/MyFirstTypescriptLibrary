# calculator

### Install
     npm install myfirsttypescriptlibrary

### Use

This calculator has a few options that you can use to simplify operations inside your Typescript projects.

#### addNumbers
    <!-- var f = func('f(x) = x*10 - 20')
    f(3) //returns 10

    f = func('f(x, t) = Math.pow(x, 2) + t + 1')
    f(2, 4) // returns 9 -->

#### substractNumbers
<!-- params `([string|function], point to evaluate function)`
    `derive('f(x) = x*x', 2) //evaluate derivative @ x = 2;  returns 4` -->

#### multiplyNumbers
<!-- params `([string|function], lower limit, upper limit)`
`derive('f(x) = x*x', 0, 1) //evaluate definite integral from x = 0 to x = 1;  returns .333 = 1/3` -->

#### divideNumbers
<!-- Set this property to determine how accurate the definite integral will be. Essentialy the "dx" in f(x)dx.
Default is `1/1000000` -->