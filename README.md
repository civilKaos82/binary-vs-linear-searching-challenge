# Binary Vs Linear Searching

##Learning Competencies

* Working with algorithms
* Use tools to evaluate basic performance considerations, benchmarking, and tradeoffs between memory and speed.

##Summary

What is the difference between binary search and linear search? Is one always faster than the other? What are the advantages to one over the other?

In this challenge, we'll be pitting the two search types against each other and profiling their performance to see how they match up.

##Releases

###Release 0 : A little bit of background

Before you start, do some research on the two types of searches. You can start with [this Stack Overflow answer](http://stackoverflow.com/questions/700241/what-is-the-difference-between-linear-search-and-binary-search).

###Release 1 : The ultimate test

How do your search algorithms match up against Ruby's built in `Array#index` method?

Add `Array#index` to your benchmarking code and see how your methods compare.

###Release 2 : Profile with Benchmark

Use the [Benchmark](http://ruby-doc.org/stdlib-1.9.3/libdoc/benchmark/rdoc/Benchmark.html) module in Ruby to profile your `linear_search` and `binary_search` methods.

Benchmark all three search algorithms against arrays of 1,000, 10,000, and 1,000,000 pre-sorted integers.


<!-- ##Optimize Your Learning -->

##Resources
