# Week 1 - Day 2

#### Coding Session 1

**The Linux Command Line (Part 2)**

**NOTE:** Follow the instructions carefully and follow coding discipline


### FSD.W1.2.1_1

Go to your home directory `cd ~` and create a folder called `practise`   

Create a folder called `week1` inside `practise` folder  

Create a folder called `day2` inside `week1` folder  

Create a folder called `session1` inside `day2` folder  

Navigate to the folder `practise/week1/day2/session1`



test@LAPTOP-LLCMMN9C:~/practise/week1/day2/session1$




### FSD.W1.2.1_2

Save the current date to a file called `date.txt`



test@LAPTOP-LLCMMN9C:~/practise/week1/day2/session1$ echo "date" >>date.txt
test@LAPTOP-LLCMMN9C:~/practise/week1/day2/session1$ ls
date.txt
test@LAPTOP-LLCMMN9C:~/practise/week1/day2/session1$ date
Sun Nov 24 18:46:09 CST 2024





### FSD.W1.2.1_3

Create a calendar file for the year you were born with the following name `cal_yyyy.txt`



test@LAPTOP-LLCMMN9C:~/practise/week1/day2/session1$  echo "calendar" >>cal_1992.txt
test@LAPTOP-LLCMMN9C:~/practise/week1/day2/session1$ cal_1992.txt
cal_1992.txt: command not found
test@LAPTOP-LLCMMN9C:~/practise/week1/day2/session1$ cal 1992
                            1992
      January               February               March
Su Mo Tu We Th Fr Sa  Su Mo Tu We Th Fr Sa  Su Mo Tu We Th Fr Sa
          1  2  3  4                     1   1  2  3  4  5  6  7
 5  6  7  8  9 10 11   2  3  4  5  6  7  8   8  9 10 11 12 13 14
12 13 14 15 16 17 18   9 10 11 12 13 14 15  15 16 17 18 19 20 21
19 20 21 22 23 24 25  16 17 18 19 20 21 22  22 23 24 25 26 27 28
26 27 28 29 30 31     23 24 25 26 27 28 29  29 30 31


       April                  May                   June
Su Mo Tu We Th Fr Sa  Su Mo Tu We Th Fr Sa  Su Mo Tu We Th Fr Sa
          1  2  3  4                  1  2      1  2  3  4  5  6
 5  6  7  8  9 10 11   3  4  5  6  7  8  9   7  8  9 10 11 12 13
12 13 14 15 16 17 18  10 11 12 13 14 15 16  14 15 16 17 18 19 20
19 20 21 22 23 24 25  17 18 19 20 21 22 23  21 22 23 24 25 26 27
26 27 28 29 30        24 25 26 27 28 29 30  28 29 30
                      31

        July                 August              September
Su Mo Tu We Th Fr Sa  Su Mo Tu We Th Fr Sa  Su Mo Tu We Th Fr Sa
          1  2  3  4                     1         1  2  3  4  5
 5  6  7  8  9 10 11   2  3  4  5  6  7  8   6  7  8  9 10 11 12
12 13 14 15 16 17 18   9 10 11 12 13 14 15  13 14 15 16 17 18 19
19 20 21 22 23 24 25  16 17 18 19 20 21 22  20 21 22 23 24 25 26
26 27 28 29 30 31     23 24 25 26 27 28 29  27 28 29 30
                      30 31

      October               November              December
Su Mo Tu We Th Fr Sa  Su Mo Tu We Th Fr Sa  Su Mo Tu We Th Fr Sa
             1  2  3   1  2  3  4  5  6  7         1  2  3  4  5
 4  5  6  7  8  9 10   8  9 10 11 12 13 14   6  7  8  9 10 11 12
11 12 13 14 15 16 17  15 16 17 18 19 20 21  13 14 15 16 17 18 19
18 19 20 21 22 23 24  22 23 24 25 26 27 28  20 21 22 23 24 25 26
25 26 27 28 29 30 31  29 30                 27 28 29 30 31






### FSD.W1.2.1_4

Append the current date to previously created file called `date.txt` in **FSD.W1.2.1_2**  


test@LAPTOP-LLCMMN9C:~/practise/week1/day2/session1$ date >>date.txt
test@LAPTOP-LLCMMN9C:~/practise/week1/day2/session1$ cat date.txt
date
Sun Nov 24 19:17:15 CST 2024



### FSD.W1.2.1_5

See the file `date.txt` using `less` command and calculate see how much time you spend between solving **FSD.W1.2.1_2** and **FSD.W1.2.1_4**


test@LAPTOP-LLCMMN9C:~/practise/week1/day2/session1$  less date.txt
test@LAPTOP-LLCMMN9C:~/practise/week1/day2/session1$ date -d "Sun Nov 24 18:46:09 CST 2024"
Sun Nov 24 18:46:09 CST 2024
test@LAPTOP-LLCMMN9C:~/practise/week1/day2/session1$ date -d "Sun Nov 24 18:46:09 CST 2024" +%s
1732445169
test@LAPTOP-LLCMMN9C:~/practise/week1/day2/session1$ date -d "Sun Nov 24 19:17:15 CST 2024" +%s
1732447035
test@LAPTOP-LLCMMN9C:~/practise/week1/day2/session1$ echo $((1732447035 - 1732445169))
1866

31 minute 1 second

### FSD.W1.2.1_6

Download the file https://github.com/masai-school/assignments-data/raw/master/downloads/numbers.zip unzip and you will find a folder called `numbers` navigate to that folder and do the following operations

- Join all the files with the name `all.txt`
- Join the files `even_2.txt` `odd_2.txt` `odd_5.txt` `odd_7.txt` to a file called `primes.txt`
- Join all the files which start with the name `even` to a file called `even.txt`
- Join all the files which start with the name `odd` to a file called `odd.txt`

### FSD.W1.2.1_7

Navigate to the folder `practise/week1/day2/session1`  

Download the file <https://raw.githubusercontent.com/masai-school/assignments-data/master/data/junk/names_100.txt> 

- Sort the names in the file `names_100.txt` in ascending order and write to a file called `names_asc.txt`
- Sort the names in the file `names_100.txt` in descending order and write to a file called `names_desc.txt`

### FSD.W1.2.1_8

Download the file https://raw.githubusercontent.com/masai-school/assignments-data/master/data/lists/countries.csv

- Find all the countries with the name "South" in `countries.csv` and write it to a file called `coun_south.csv`
- Find all the countries with the name "United" in `countries.csv` and write it to a file called `coun_united.csv`

### FSD.W1.2.1_9

- Write the number of lines in the file `countries.txt` to a file `countries_count.txt`
- Write the number of words in the file `names_100.txt` to a file `names_wc.txt`
- Write the number of characters in the file `names_100.txt` to a file `names_char.txt`

### FSD.W1.2.1_10

- Write the first 50 names in the file `names_100.txt` to a file called `names_top50.txt`
- Write the last 20 lines in the file `countries.txt` to a file called `countries_bot20.txt`