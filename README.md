# Ruby Assessment - Day 2

Fork this repository, and clone the fork to your local computer. Edit this README.md file to contain the answers, and then make a pull request on Github to turn in the assessment.

## Question 1

```ruby
a = 5
b = 4
a = b
```

At the end of this program, what are the values of a and b? Try to explain, in plain English, how you got your answer for each one.

ANSWER: A is equal to 4 and b is equal to 4, as the value or a is assinged in line 1, the value of b in line 2 and a is reassigned to 4 in line 3.

## Question 2

```ruby
e = 3
f = 9
g = e + f
f == g
e = 3
```

At the end of this program, what are the values of e, f, and g? Try to explain, in plain English, how you got your answer for each one.

ANSWER: e is 3, f is 9 and g is 12. e is assigned hte value of 3 in line 1 and reiteratein in line 5, f is assigned the value of nine in line 2. The value is not overwritten in line 4 as line 4 compare f to g. And g is assigned hte value or 12 in line 3.



## Question 3

```ruby
weather = "cloudy"
weather == "cloudy"
```

What is the difference between these two statements? Explain your answer.

ASNWER: the first line signed weather the value of cloudy. The second line compare weather to cloudy.


## Question 4

```ruby
x = 2

if x == 3
  puts "sushi is tasty"
elsif x > 0
  puts "sushi is delicious"
end
```

Imagine that you take the code from this question, save it to a file called `sushi.rb`, and run `ruby sushi.rb` in your Terminal.

What would be the output? Explain your answer.


ANSWER: The output is sushi is delicios. Line two only compare 2 to 3 not resulting in a true statement so it is ignored. However x is greater than 2 which is true and put "sushi is delicios" is printed.

## Question 5

```ruby
food = "walnut"

if food == "walnut"
  puts "I'm allergic!"
end
```

Imagine that you take the code from this question, save it to a file called `snack.rb`, and run `ruby snack.rb` in your Terminal.

What would be the output? Explain your answer.

ANSWER: There is no output as line 2 compare food to walnut which does not result in a true statement. If the line said food = "walnut" then it would put "I'm allergic".
