# Ruby Assessment - Day 2

Fork this repository, and clone the fork to your local computer. Edit this README.md file to contain the answers, and then make a pull request on Github to turn in the assessment.

## Question 1

```ruby
a = 5
b = 4
a = b
```

At the end of this program, what are the values of a and b? Try to explain, in plain English, how you got your answer for each one.
 a and b are 4 because in the final line, the value of a is set to b, which already carries the value of 4.

## Question 2

```ruby
e = 3
f = 9
g = e + f
f == g
e = 3
```

At the end of this program, what are the values of e, f, and g? Try to explain, in plain English, how you got your answer for each one.
e = 3, f = false, g = 12. e is set to 3 in the last line of code, in addition to its initial value. f is false because its value of 9 not equal that of g, whose value had been set to the sum of e and f, which is 12.

## Question 3

```ruby
weather = "cloudy"
weather == "cloudy"
```

What is the difference between these two statements? Explain your answer.
Whereas the first statement is setting the value of weather to the string "cloudy", the latter line of code is checking to see if the value of weather is equal to the string "cloudy" and will render a True or False boolean.

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
Because the value of x is set at 2, ruby will puts "sushi is delicious".

## Question 5

```ruby
food = "walnut"

if food == "walnut"
  puts "I'm allergic!"
end
```

Imagine that you take the code from this question, save it to a file called `snack.rb`, and run `ruby snack.rb` in your Terminal.

What would be the output? Explain your answer.
The output of this would be that ruby puts the string "I'm allergic", as it has judged that the value of "walnut" set to the variable food was true.
