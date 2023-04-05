# Project Solutions 📃

This repository contains solutions to the following GCS-2 Problems for Negpod-1:

## Test :file_folder:

The [test](./test/) directory is a directory that contains automated tests for the shell scripts of each problem in this repository.

## Problem 1 🔍

Write a shell script that will print the strings `one`, `two`, `three`, `four`, and `five` on the screen with each appearing on a separate line. Also, create a text file that has each of these on a separate line and the file name starts with today's date `yyyy-mm-dd-file.txt`. Note: Don’t add today’s date manually.

## Solution ✅

The solution to this problem can be found in the [print_strings](./print_strings) file of this repository. It can be run from the command line as follows:

```sh
user@User:~$ ./print_strings
```
The text file with the strings is also created by this script, and its name starts with the current date in the format `yyyy-mm-dd-file.txt`. For example, if today is `February 15, 2023`, the file name would be `2023-02-15-file.txt`.

## Problem 2 🔍

Write a script that generates two random numbers, and print each of these numbers and their square roots. Then finally print the sum of their square roots on the screen. The expected output is as below

- The first random number generated is `20243`   
- The square root is `142`   
- The second random number generated is `9759`  
- The square root is `98`   
- The sum of their square roots is `240`


## Solution ✅

The shell script that generates the random numbers and calculates their square roots is called [calculate_square_roots](./calculate_square_roots). It can be run from the command line as follows:

```sh
user@User:~$ ./calculate_square_roots
```
The script will output the two random numbers, their square roots, and the sum of their square roots, as shown in the example in the problem statement.

## Problem 3 🔍

Write a shell script that asks the user to type a phrase, then tells the user the number of words in the phrase and the number of white spaces. The expected output is:

- The number of words is `4`    
- The number of white spaces is `3`

## Solution ✅

The shell script that asks the user for input and counts the number of words and white spaces is called [count_words_and_spaces](./count_words_and_spaces). It can be run from the command line as follows:

```sh
user@User:~$ ./count_words_and_spaces
```
The script will prompt the user to enter a phrase, and then output the number of words and white spaces in the phrase, as shown in the example in the problem statement.

## Problem 4 🔍

a) Write a shell script that asks the user for two numbers and outputs their products. The expected output should be a statement as such 

```sh
The product of 3 and 3 is 9.
```
b) Suppose you want to create 4 folders. Create a text file with at least 4 words(folder name on each line). Write a shell script that reads each line of the text file. Then creates a corresponding folder for each folder name.

## Solution ✅

a) The shell script that asks the user for two numbers and ouputs their product is called [product-of_2_numbers](./product-of_2_numbers). It can be run from the command line as follows:

```sh
user@User:~$ ./product-of_2_numbers
```
The script will prompt the user to enter 2 numbers, and then output the product of the 2 numbers, as shown in the example in the problem statement.

b) The shell script that reads each line of a text file [folders.txt](./folders.txt), then creates a corresponding folder for each folder name is called [create-folders](./create-folders). It can be run from the command line as follows:

```sh
user@User:~$ ./create-folders
```
The script will reads each line of the text file [folders.txt](./folders.txt), then creates a corresponding folder for each folder name.

## Problem 5 🔍

Write a shell script that takes a path, and confirms if it is a directory or not. If it is a directory list all files in that directory, if not ask the user to give the file path of a directory.  
- Expected output: List of files in the directory path that was provided

## Solution ✅

The shell script that checks the path and lists the files is [check-and_list_directory](./check-and_list_directory). It can be run from the command line as follows:

```sh
user@User:~$ ./check-and_list_directory
```
The script will prompt the user to enter a path, and then output a list of files in the directory if it is a directory, or ask the user to enter the path of a directory if it is not a directory, as shown below: 
```sh
teniola@Teniola:~/Group-_gcs-2-$ pwd
/home/teniola/Group-_gcs-2-
teniola@Teniola:~/Group-_gcs-2-$ ./check-and_list_directory
Enter a path: /home/teniola/Group-_gcs-2-
The path you entered is a directory
Listing all files in the directory:
total 64
drwxr-xr-x 4 teniola teniola 4096 Feb 17 16:39 .
drwxr-xr-x 6 teniola teniola 4096 Feb 17 16:31 ..
drwxr-xr-x 8 teniola teniola 4096 Feb 17 16:41 .git
-rwxr-xr-x 1 teniola teniola  204 Feb 15 16:15 Problem_1_paterne
-rw-r--r-- 1 teniola teniola 2431 Feb 17 15:49 README.md
-rwxr--r-- 1 teniola teniola  467 Feb 17 14:38 calculate_square_roots
-rwxr-xr-x 1 teniola teniola  585 Feb 17 15:45 check-and_list_directory
-rwxr--r-- 1 teniola teniola  210 Feb 17 14:54 count_words_and_spaces
-rwxr-xr-x 1 teniola teniola  136 Feb 17 15:22 create-folders
-rw-r--r-- 1 teniola teniola   32 Feb 17 15:05 folders.txt
-rw-r--r-- 1 teniola teniola   99 Feb 17 15:54 message_template.txt
-rw-r--r-- 1 teniola teniola   61 Feb 17 15:53 names.txt
-rwxr-xr-x 1 teniola teniola  578 Feb 17 16:28 new-year_message
-rwxr--r-- 1 teniola teniola  204 Feb 17 14:23 print_strings
-rwxr-xr-x 1 teniola teniola  214 Feb 17 15:03 product-of_2_numbers
drwxr-xr-x 6 teniola teniola 4096 Feb 17 16:39 test
teniola@Teniola:~/Group-_gcs-2-$
```

## Problem 6 🔍

Suppose that you want to write the same message to many people except that you want each message personalized with the recipients’ names. This can be achieved using a shell script.

## Solution ✅

The shell script that creates personalized messages for each recipient is [new-year_message](./new-year_message). It can be run from the command line as follows:

```sh
user@User:~$ ./new-year_message
```
The script will read the text file [names.txt](./names.txt), which is in the same directory as the script, and the message template in [message_template.txt](./message_template.txt). It will then create a personalized message for each recipient in a file named after the recipient. For example, if the recipient's name is `Noella`, the file name would be [Noella.txt](./test/Noella.txt). The message in the file will be personalized with the recipient's name, as shown below:

```sh
user@User:~/Group-_gcs-2-/test$ cat Noella.txt
Happy New Year Noella!
May the coming year be full of grand adventures and opportunities.
```

## Collaborators 🤝

- [Sadick Achuli](https://github.com/Sadickachuli)
- [Abdulhameed Teniola Ajani](https://github.com/Elhameed)
- [Noella Uwayo](https://github.com/n-uwayo)
- [Iraduhaye Paterne](https://github.com/IraduhayeBukuruPaterne1)
- [Innocent Manzi](https://github.com/innocentmanzi)
- [Iranzi Prince](https://github.com/iranziprince01)
- [Mohammed Yasin](https://github.com/MohamedAYasin)
- [Sabir Walid](https://github.com/SabirWalid)
