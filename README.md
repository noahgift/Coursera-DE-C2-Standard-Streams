# Coursera-DE-C2-Standard-Streams
Standard Streams Lab for Coursera

## Goal:   Learn to work with streams

Let's practice working with Bash Streams

### Part 1: Create a new file and write to it via stdout

1.  Run the following command in your Bash terminal:  `echo "fruit" > meal.txt`
2.  Read the output of the file using the cat command:  `cat meal.txt`
3.  Explain what happened?

### Part 2: Append new data to the file by using stdout

1.  Run the following command in your Bash terminal: `echo "chocolate" >> meal.txt`
2.  Read the output of the file using the cat command:  `cat meal.txt`
3.  Explain what happened?
4.  How could you write more data to the file?

### Part 3:  Redirect standard input

1.  Use the `tr` command to substitute characters by reading standard input:  `tr fruit steak < meal.txt `
2.  What output do you see?  
3.  Could you improve this result?  How?

### Part 4:  Throwaway stdout to /dev/null

1.  Send the output of standard out to /dev/null via `cat meal.txt > /dev/null`
2.  Explain what happened?
3.  Why would you want to send the output of a command to `/dev/null`?
