# Microsoft Q# Coding Contest - Summer 2020 - Warmup



## A1. Distinguish I from X
You are given an operation that implements a single-qubit unitary transformation: either the identity (I gate) or the X gate. The operation will have Adjoint and Controlled variants defined.

Your task is to perform necessary operations and measurements to figure out which unitary it was and to return 0 if it was the I gate or 1 if it was the X gate.

You are allowed to apply the given operation and its adjoint/controlled variants exactly once.

You have to implement an operation which takes a single-qubit operation as an input and returns an integer. Your code should have the following signature:

```php
namespace Solution {
    open Microsoft.Quantum.Intrinsic;

    operation Solve (unitary : (Qubit => Unit is Adj+Ctl)) : Int {
        // your code here
    }
}
```



## A2. Distinguish I from Z
You are given an operation that implements a single-qubit unitary transformation: either the identity (I gate) or the Z gate. The operation will have Adjoint and Controlled variants defined.

Your task is to perform necessary operations and measurements to figure out which unitary it was and to return 0 if it was the I gate or 1 if it was the Z gate.

You are allowed to apply the given operation and its adjoint/controlled variants exactly once.

You have to implement an operation which takes a single-qubit operation as an input and returns an integer. Your code should have the following signature:

```php
namespace Solution {
    open Microsoft.Quantum.Intrinsic;

    operation Solve (unitary : (Qubit => Unit is Adj+Ctl)) : Int {
        // your code here
    }
}
```



## A3. Distinguish Z from S
You are given an operation that implements a single-qubit unitary transformation: either the Z gate or the S gate. The operation will have Adjoint and Controlled variants defined.

Your task is to perform necessary operations and measurements to figure out which unitary it was and to return 0 if it was the Z gate or 1 if it was the S gate.

You are allowed to apply the given operation and its adjoint/controlled variants exactly twice.

You have to implement an operation which takes a single-qubit operation as an input and returns an integer. Your code should have the following signature:

```php
namespace Solution {
    open Microsoft.Quantum.Intrinsic;

    operation Solve (unitary : (Qubit => Unit is Adj+Ctl)) : Int {
        // your code here
    }
}
```


