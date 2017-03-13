# Miniflow Backpropagation (Udacity SDCND T1L7C14)
[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)

## Synopsis

This repository contains code used in Lesson 7 - Chapter 14 of Udacity's Self Driving Car Nanodegree (Term 1).

## Goal

The goal of the quiz is to define the sgd_update method in Miniflow (a very basic version of TensorFlow). This will be used against an actual dataset ([Boston Housing](https://archive.ics.uci.edu/ml/datasets/Housing)).

## Expected Results

The expected output is a downwards trend in *loss* towards 0.

## Additional resources (must-read)
These resources are recommended by the quiz, and are highly recommended to understand what we're trying to accomplish. Andrej does a good job in illustrating leaky abstraction, which renders no training loss at all and thus impedes learning.

* [Yes you should understand backprop (Andrej Karpathy)](https://medium.com/@karpathy/yes-you-should-understand-backprop-e2f06eab496b#.f5mlbjzdz)
* [Vector, Matrix, and Tensor Derivatives](http://cs231n.stanford.edu/vecDerivs.pdf)