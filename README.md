Term counting: a coding challenge
=================================

In order to get a quick overview of what a text document is about, we'd like
you to write a small application that reads in a file of English text, and
then shows a list of the most common words in the file.

What are we looking for?
------------------------

This exercise is our chance to get a look at your coding style -- to make
sure that you can produce code that the rest of the team will be happy
working with and maintaining. With this in mind, please approach the
exercise as if you're demonstrating how you'd contribute to a larger
system, not just writing a one-off script to get the job done.

When we evaluate your code sample, we'll consider questions like:

* Does the output match what we asked for?
* Is the code simple, readable, and well documented?
* Will the design be easy to update and maintain?
* Are there automated tests that verify correct behavior?

Details
-------

It should be possible to call the application at the command-line with the
filename to read as an argument. Something like:
```
$ python word_count.py my-doc.txt
```

By default, it should output the list in a simple human-readable format like
this:
```
hello - 327
hi - 42
howdy - 17
...
```

In the default format, it should list only the most common words.

It should _also_ be possible to get the list in JSON format, like this:
```
{"howdy": 17, "hello": 327, "hi": 42, ...}
```

In JSON format, the application should list counts for all the words.

We don't want you to spend more than two or three hours on this, so feel free
to make any simplifying assumptions necessary to get a basic version of the
application up and running; for example, you don't need to treat "thing" and
"things" as the same word. If you get something working early, consider
exploring any ways you can see of improving the output format or making the
output more meaningful.

Document your design and your decisions (within the code and/or in a readme
file) including how to run your program and your tests. Explain any fixes or
enhancements you'd like to make to the application if you had more time.

If you want a file to test with, we recommend using a plain text formatted
e-book from [Project Gutenberg](https://www.gutenberg.org/).

Submitting your code
--------------------

When your Python code is ready, package it up and send it to
`hiring@luminoso.com`. What you send us should include:

* A README with any necessary instructions on how to run your code
* The code itself, along with any other files required for it to run
* Automated tests
* The version of Python you used when working on it (the output of
  `python --version` -- e.g., "Python 3.4")

Please send it only to us, and don't make your code publicly available.

We review code samples anonymously, so please DO NOT PUT YOUR NAME in any of
your files or filenames.
