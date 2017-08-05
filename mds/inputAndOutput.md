
## Input and Output (与输入输出有关的操作)

- `echo` : like print
        * `echo 'Hello World'` : output will be 'Hello World'
- `stdin` : STanDard INput
- `stdout` : STanDard OUTput
- `stderr` : an error message outputted by a failed process
- `cat` : outputs the contents of a file to the terminal
- `>` :  takes the standard output of the command on the left and redirects it to the file on the right
    * `echo 'Hello' > hello.txt` the stdout 'Hello' is redirected by > to the file hello.txt
    * `cat a.txt > b.txt` a's contents overwrite b's contents
- `>>` :  takes the standard output of the command on the left and appends it to the file on the right
    * `cat c.txt >> b.txt` appends c's contents to b
- `<` :  takes the standard input from the file on the right and inputs it into the program on the left
- `|` :  takes the standard output of the command on the left and pipes it as standard input to the command on the right
    * `cat a.txt | b`
- `uniq` : filters out adjacent, duplicate lines in a file
- `grep` : 'Global Regular Expression Print', it searches files for lines that match a pattern and returns the results. Case sensitive
    * `grep -i` case insensitive
    * `grep -r` searches all files in a directory and outputs filenames and lines containing matched results.
    * `grep -ri` searches all files in a directory and outputs only filenames with matched results
- `sed` : Steam Editor, accepts standard input and modifies it based on an expression (find and replace)
    * `sed: 's/snow/rain'` s: substitution, find snow and replace snow to rain
    * `g`: global, all instances of 'snow' will be returned to 'rain' 

