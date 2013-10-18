Ruby revision
-------------

### Makers Academy Week 9 Test

This test was set by Alex Peattie
[@alexpeattie](https://twitter.com/alexpeattie)
whilst learning to code at [Makers Academy](http://www.makersacademy.com).
The aim was to revise my knowledge of Ruby.

Alex provided an RSpec file and I wrote the code to satisfy the tests. 

At the end there were two extra challenges:
  - writing FizzBuzz without using the modulo method, and
  - generating the lyrics of '99 bottles of beer on the wall'.

For `fizzbuzz_without_modulo` I wrote tests in RSpec and monkey patched
`Fixnum` with a recursive `multiple_of?(n)` method.
