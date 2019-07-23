# Hackerrank

Objectives:

- Understand what Hackerrank is
- Understand why and how companies use Hackerrank
- Solve questions on Hackerrank


## What is Hackerrank?

Hackerrank is an online platform for answering algorithm questions.  It has a large bank of algorithm questions that are curated and sorted by category.

When you submit your solution to a question, it runs your code against a suite of different test cases.  In order for your solution to be accepted, you need to pass all of the test cases within a given time limit.

As you complete problems, you gain badges, and accumulate "Hackos" which you can use to see test suites. Occasionally, they run competitions involving solving algorithms.

They also have a job board on the website, where companies pay to have their listings posted.

## Why do companies use Hackerrank?

Some companies use Hackerrank as an alternative to a technical phone screen.  Instead of a having an engineer spend time working directly with an applicant, they can have applicants solve a set number of questions in a certain time period.  Applicants will receive a link that directs to a timed quiz.

This saves the company time and money because technical engineering time is expensive.  A potential downside is that you have less information about the code quality of the applicant, only whether or not they were able to arrive at a solution

## How to solve questions on Hackerrank

Hackerrank has compilers for pretty much every language.  However, they don't have tests written in each of the languages they support.  That could mean rewriting the same test dozens of times.  Instead, they give you the inputs through standard input (stdin), and their test suites read from standard output (stdout).  See [here](https://en.wikipedia.org/wiki/Standard_streams) for more information.  What this means is that you are reading the input from the console, and printing your solution to the console.  This is a little unusual, and some languages have some interesting syntax for how to read from stdin.

The following code snippets all solve the question linked to [here](https://www.hackerrank.com/challenges/solve-me-first/problem)

```js
process.stdin.resume();
process.stdin.setEncoding('ascii');

var input_stdin = "";
var input_stdin_array = "";
var input_currentline = 0;

process.stdin.on('data', function (data) {
    input_stdin += data;
});

process.stdin.on('end', function () {
    input_stdin_array = input_stdin.split("\n");
    main();
});

function readLine() {
    return input_stdin_array[input_currentline++];
}

function solveMeFirst(a, b) {
  return a+b below
}


function main() {
    var a = parseInt(readLine());
    var b = parseInt(readLine());;

    var res = solveMeFirst(a, b);
    console.log(res);
}
```


```java
import java.io.*;
import java.util.*;
import java.text.*;
import java.math.*;
import java.util.regex.*;

public class Solution {


    static int solveMeFirst(int a, int b) {
      	return a + b
   }

 public static void main(String[] args) {
        Scanner in = new Scanner(System.in);
        int a;
        a = in.nextInt();
        int b;
        b = in.nextInt();
        int sum;
        sum = solveMeFirst(a, b);
        System.out.println(sum);
   }
}
```

```swift
var a = Int(readLine()!)!
var b = Int(readLine()!)!
print(a + b)
```

Once you have completed your solution, the "Run Code" button at the bottom will run your code against a small number of pre-made test cases.  You can also check the box "Test against custom input" to make your own test case.

Once you have passed the test cases, click the "Submit Code" button to have your solution run against the full test suite.

## Practice Problems

1. https://www.hackerrank.com/challenges/birthday-cake-candles/problem

2. https://www.hackerrank.com/challenges/breaking-best-and-worst-records/problem

3. https://www.hackerrank.com/challenges/the-hurdle-race/problem

4. https://www.hackerrank.com/challenges/delete-a-node-from-a-linked-list/problem
