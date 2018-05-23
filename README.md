# qcfoptions
Option Calculator and Simulator

Git Repository : [https://github.com/austingriffith94/qcfoptions](https://github.com/austingriffith94/qcfoptions)

An option calculator born from the need to calculate the prices of various options in the QCF program at Georgia Tech. This package provides:

* Black Scholes pricing of traditional, barrier and exotic options
* Greeks of European style options
* Simulations of underlying asset using stochastic processes
* Pricing of options utilizing the simulated motion of the underlying

I hope this helps those looking to avoid rewriting a general Black Scholes calculator each time they need to, those looking for a general code/framework to create their own option calculator, or those hoping to play around with a simple option pricing simulation. Each function and class has a complete walkthrough on what it does, should the user be interested. For example, if you want to know how to work the European option function, simply type :

    >>> from qcfoptions import bsoptions
    >>> help(bsoptions.Euro)

into the command console, and it should return a relatively complete description of the function.

You can install this package from PyPI by using the command :

    pip install qcfoptions
