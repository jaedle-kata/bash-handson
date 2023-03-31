# Bash hands-on

## Goals

Make yourself familiar with shell, common commands and basic scripting.

## Questions you should be able to answer after this hands-on

- What is shell?
- What is standard input, standard output and standard error?
- How to redirect standard output + standard error to a file
- How to read standard input from a file
- What is a pipe?
- What is an exit value?
- What is the difference between a non zero and a zero exit value?

## Commands you should know

- `awk`
- `cat`
- `cd`
- `chmod`
- `cp`
- `curl`
- `cut`
- `echo`
- `find`
- `grep`
- `head`
- `ls`
- `mkdir`
- `mv`
- `pwd`
- `rm`
- `sed`
- `sort`
- `tail`
- `tee`
- `tr`
- `uniq`
- `wc`
- `wget`
- `xargs`

## References

### Videos

- [60 Linux Commands you NEED to know (in 10 minutes)](https://www.youtube.com/watch?v=gd7BXuUQ91w)
 
### References

- [Pure bash bible](https://github.com/dylanaraps/pure-bash-bible)

### Tools

- [tldr](https://tldr.sh/): shows information about commands, may be installed by using `brew install tldr`

## Tasks

- You will find the input files required for that hands-on in the `inputs/` director prefixed with the task number.
- Please document your solutions in a file named `SOLUTION.md`.

### Getting started

1. Use `echo` to print "Hello, world!" to the console.
2. Use `grep` to search for the word "banana" in a file called `fruits.txt`.
3. Use `cat` to concatenate two files, `file1.txt` and `file2.txt`, and save the result in a new file called `combined.txt`.
4. Use `sed` to replace all occurrences of "apple" with "orange" in a file called `fruits.txt`.
5. Use `cut` to extract the first column from a comma-separated file called `data.csv`.
6. Use `wc` to count the number of lines in a file called `myfile.txt`.
7. Use `head` to display the first 3 lines of a file called `logfile.txt`.
8. Use `tail` to display the last 2 lines of a file called `access.log`.
9. Use `sort` to sort the lines of a file called `numbers.txt` in ascending order.
10. Use `uniq` to remove duplicate lines from a file called `cities.txt`.
11. Use `tee` to write the output of a command to both a file called output.txt and the console.
12. Use `find` to locate all files with a `.txt` extension in the inputs directory and its subdirectories.
13. Use `awk` to extract the second field of a tab-separated file called data.tsv.
14. Use `diff` to compare two files, `fruits.txt` and `fruits_updated.txt`.
15. Use `curl` to download `https://raw.githubusercontent.com/jaedle-kata/java11-junit5-template/main/README.md`.
16. Use `wget` to download `https://raw.githubusercontent.com/jaedle-kata/java11-junit5-template/main/README.md`.
17. Use `tr` to remove all spaces and tabs from a file called `sentence.txt`.
18. Use `sort` and `uniq` to count the number of visits to each city in `cities.txt`.
19. Use `head` to display the first line of each file with a `.txt` extension in the directory `19`.
20. Use `find` to locate all files that are larger than 1 MB in the directory `20`. Please do not rely on the filename.

## Videos

- [Shell Scripting Crash Course - Beginner Level](https://www.youtube.com/watch?v=v-F3YLd6oMw)
- [Shell Scripting Tutorial for Beginners](https://www.youtube.com/watch?v=hwrnmQumtPw)
