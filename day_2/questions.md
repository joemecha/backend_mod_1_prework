## Day 2 Questions

1. Create an array containing the following strings: `"zebra", "giraffe", "elephant"`.
```ruby
["zebra", "giraffe", "elephant"]
```
1. Save the array you created above to a variable `animals`.
```ruby
animals = ["zebra", "giraffe", "elephant"]
```
1. Using the array `animals`, how would you access `"giraffe"`?
```ruby
animals[1]
```
1. How would you add `"lion"` to the `animals` array?
```ruby
animals << "lion"
```
or
```ruby
animals.push("lion")
```
1. Name and describe two additional array methods:
  * .unshift   adds element to start of array
  * .uniq      removes duplicate elements from array
  * .length .count .size   number of elements in array
1. What are the boolean values in Ruby?
  * true, false
  * There are many terms for making boolean arguments: && and, || or, ! not, != not equal, == equal, >= greater-than-equal, <= less-than-equal
1. In Ruby, how would you evaluate if `2` is equal to `25`? What is the result of this evaluation?
```ruby
2 == 25
```
false
1. In Ruby, how would you evaluate if `25` is greater than `2`? What is the result of this evaluation?
```ruby
25 > 2
```
true
