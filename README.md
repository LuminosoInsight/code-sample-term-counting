Term counting: a coding challenge
=================================

In order to get a quick overview of what a text document is about, we'd like
you to write a script that reads in a file of English text, and then shows a
list of the most common words in the file.

Details
-------

It should be possible to call the script at the command-line with the filename
to read as an argument. Something like:
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

In JSON format, the script should list counts for all the words.

We don't want you to spend more than two or three hours on this, so feel free
to make any simplifying assumptions necessary to get a basic version of the
script up and running; for example, you don't need to treat "script" and
"scripts" as the same word. If you get something working early, consider
exploring any ways you can see of improving the output format or making the
output more meaningful.

Document your design and your decisions (within the code and/or in a readme
file) including how to run your program and your tests. Explain any fixes or
enhancements you'd like to make to the script if you had more time.

If you want a file to test with, we recommend using a plain text formatted
e-book from [Project Gutenberg](https://www.gutenberg.org/).

Evaluation
----------

We'll be evaluating your code sample based on the quality of the documentation,
the correctness of the script's behavior, the clarity of the code, and the
maintainability of the design.

Submitting your code
--------------------

When your Python code is ready, package it up and send it to
`hiring@luminoso.com`, along with any necessary instructions on how to run it.
Please send it only to us, and don't make your code publicly available.

We review code samples anonymously, so please DO NOT PUT YOUR NAME in any of
your files or filenames.
