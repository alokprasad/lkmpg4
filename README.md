Linux Kernel Mode Programming Guide for Linux Kernel 4.x


Here's a sample of our test suite.

In the Org-mode file:

#+TBLNAME: org-babel-tests
| functionality    | block        | arg |    expected |     results | pass |
|------------------+--------------+-----+-------------+-------------+------|
| basic evaluation |              |     |             |             | pass |
|------------------+--------------+-----+-------------+-------------+------|
| emacs lisp       | basic-elisp  |   2 |           4 |           4 | pass |
| shell            | basic-shell  |     |           6 |           6 | pass |
| ruby             | basic-ruby   |     |   org-babel |   org-babel | pass |
| python           | basic-python |     | hello world | hello world | pass |
| R                | basic-R      |     |          13 |          13 | pass |
#+TBLFM: $5='(if (= (length $3) 1) (sbe $2 (n $3)) (sbe $2)) :: $6='(if (string= $4 $5) "pass" (format "expected %S but was %S" $4 $5))
