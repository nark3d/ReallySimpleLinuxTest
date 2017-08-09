# Really Simple Linux Test

A simple Linux test for DevOps candidates.  There are a number of ways to complete the following tasks and there are no right, or perfect, answers.  The test is to gauge the knowledge and experience of a potential DevOps candidate.

## The test

Edit the file `script.sh` so that when executed, the output matches this:

```shell
$ ./script.sh
Find all .doc file types:
./files/ffc.doc ./files/ffc_6.doc ./files/ffc_95.doc ./files/ffc_97_2000_xp.doc

Change all chmodme files to 0777:
-rwxrwxrwx  1 adam.lewis  BTM\Domain Users  8195 Aug  9 10:00 ./files/chmodme.jpg
-rwxrwxrwx  1 adam.lewis  BTM\Domain Users  5500 Aug  9 10:00 ./files/chmodme.gif

Change bad for good:
The good fox jumps over the good dog.
Good, Good, GOOD, good, GOOD, good, good, goodie bag.

Count to ten:
1 2 3 4 5 6 7 8 9 10

Reverse characters in file:
This text should be forwards and on the first line!
And this text should be the same, but on the second line...
```
## Tasks

### Find
Find and list all .doc file types from the files folder in the output of your `script.sh`.

### Change permissions
Find and change all 'chmodme.*' files and change the permissions to 777.  List the files in the output of your `script.sh`.

### String replacement
In the file: `files/goodbad.txt`, find all instances of 'bad', 'Bad' and 'BAD', replace with 'good', 'good' and 'GOOD', then show the text in the output of your `script.sh`.

### Count to ten
Write a mechanism of print 1 to 10 with spaces and output it from your `script.sh`.

### Manipulate text
Using: `files/backwards.txt`, reverse the characters in the text and reverse the order of the lines in the file.  Output the result from your `script.sh`.

## Submitting answers
Clone or fork this repo, create a new branch and push it once you have completed the task.

## License
MIT