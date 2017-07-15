# python-bytecode-interpreter
A bytecode interpreter for v 2.7.10

This interpreter supports basic arithmetic operations addition, substraction, division, multiplication and modulo operation.
It also supports basic looping with while and simple functions with no recursive calls.

Usage:

```
     make

```
A pyvm executable is created which takes .pyc files as command line input.

```
    ./pyvm *.pyc
	
```

Running Testcodes:

```
    ./pyvm testcodes/fac.pyc
    ./pyvm testcodes/loop.pyc
	
```

