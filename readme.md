## Recover a secret string from random triplets

There is a secret string which is unknown to you. Given a collection of random
triplets from the string, recover the original string.

A triplet here is defined as a sequence of three letters such that each letter
occurs somewhere before the next in the given string. "whi" is a triplet for
the string "whatisup".

As a simplification, you may assume that no letter occurs more than once in the
secret string.

You can assume nothing about the triplets given to you other than that they are
valid triplets and that they contain sufficient information to deduce the
original string. In particular, this means that the secret string will never
contain letters that do not occur in one of the triplets given to you.

### Language and test case support

Test cases (or pseudo-test cases) have been provided below for the following languages:

* [Clojure](./triplets_test.clj)
* [Ruby](./triplets_test.rb)
* [JavaScript](./triplets_test.js)
* [Python](./triplets_test.py)
* [Haskell](./triplets_test.hs)

### Solution submission

You are welcomed and encouraged to try to implement a solution in one or more languages. 
To submit a solution, please create a gist with your code and send the gist link to
me at [craig@mojotech.com](mailto:craig@mojotech.com?subject=April 2015 Code Challenge) with a subject line of `April 2015 Code Challenge`.
