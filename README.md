Download Link: https://assignmentchef.com/product/solved-crows-nest
<br>
<a href="https://www.youtube.com/playlist?list=PLhOuww6rJJNPBqIwfD-0RedqsitBliLhT" rel="nofollow">https://www.youtube.com/playlist?list=PLhOuww6rJJNPBqIwfD-0RedqsitBliLhT</a>

Write a program that will announce the appearance of something “off the larboard bow” to the captain of the ship. Note that you need to “a” before a word starting with a consonant:

<pre><code>$ ./crowsnest.py narwhalAhoy, Captain, a narwhal off the larboard bow!</code></pre>

Or “an” before a word starting with a vowel:

<pre><code>$ ./crowsnest.py octopusAhoy, Captain, an octopus off the larboard bow!</code></pre>

Given no arguments, the program should print a brief usage:

<pre><code>$ ./crowsnest.pyusage: crowsnest.py [-h] strcrowsnest.py: error: the following arguments are required: str</code></pre>

It should print a longer usage for <code>-h</code> and <code>--help</code>:

<pre><code>$ ./crowsnest.py -husage: crowsnest.py [-h] strCrow's Nest -- choose the correct articlepositional arguments:  str         A wordoptional arguments:  -h, --help  show this help message and exit</code></pre>

A passing test suite looks like this:

<pre><code>$ make testpytest -xv test.py============================= test session starts ==============================...collected 6 itemstest.py::test_exists PASSED                                              [ 16%]test.py::test_usage PASSED                                               [ 33%]test.py::test_consonant PASSED                                           [ 50%]test.py::test_consonant_upper PASSED                                     [ 66%]test.py::test_vowel PASSED                                               [ 83%]test.py::test_vowel_upper PASSED                                         [100%]============================== 6 passed in 2.89s ===============================</code></pre>