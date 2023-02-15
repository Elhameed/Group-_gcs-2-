# Project Solutions

This repository contains solutions to the following GCS -2 Problems for Negpod-1:

## Problem 1

Write a shell script that will print the strings `one`,` two`,` three`,` four`, and `five` on the screen with each appearing on a separate line. Also, create a text file that has each of these on a separate line and the file name starts with today's date `yyyy-mm-dd-file.txt`. Note: Don’t add today’s date manually.

## Solution

The solution to this problem can be found in the `print_strings` file of this repository. It can be run from the command line as follows:

```sh
$ ./print_strings
```
The text file with the strings is also created by this script, and its name starts with the current date in the format `yyyy-mm-dd-file.txt`. For example, if today is `February 15, 2023`, the file name would be `2023-02-15-file.txt`.

## Problem 2

Write a script that generates two random numbers, and print each of these numbers and their square roots. Then finally print the sum of their square roots on the screen. The expected output is as below

The first random number generated is `20243`   
The square root is `142`   
The second random number generated is `9759`  
The square root is `98`   
The sum of their square roots is `240`


## Solution

The shell script that generates the random numbers and calculates their square roots is called `calculate_square_roots`. It can be run from the command line as follows:

```sh
$ ./calculate_square_roots
```
The script will output the two random numbers, their square roots, and the sum of their square roots, as shown in the example in the problem statement.

## Problem 3

Write a shell script that asks the user to type a phrase, then tells the user the number of words in the phrase and the number of white spaces. The expected output is:

The number of words is `4`    
The number of white spaces is `3`

## Solution

The shell script that asks the user for input and counts the number of words and white spaces is called `count_words_and_spaces`. It can be run from the command line as follows:

```sh
$ ./count_words_and_spaces
```
The script will prompt the user to enter a phrase, and then output the number of words and white spaces in the phrase, as shown in the example in the problem statement.

