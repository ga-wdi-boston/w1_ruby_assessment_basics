# Ruby Assessment - Day 2

Fork this repository, and clone the fork to your local computer. Edit this README.md file to contain the answers, and then make a pull request on Github to turn in the assessment.

## Question 1

```ruby
a = 5
b = 4
a = b
```

At the end of this program, what are the values of a and b? Try to explain, in plain English, how you got your answer for each one.

a = 4 # a is set to b on line 10
b = 4 # b never changes

## Question 2

```ruby
e = 3
f = 9
g = e + f
f == g
e = 3
```

At the end of this program, what are the values of e, f, and g? Try to explain, in plain English, how you got your answer for each one.

e = 3 # set to 3 on line 25
f = 12 # set to g on line 24
g = 12 # set to 3 + 9 on line 23

## Question 3

```ruby
weather = "cloudy"
weather == "cloudy"
```

What is the difference between these two statements? Explain your answer.

The first is assigns the string "cloudy" to the variable weather; the second is a boolean statement that tests if the variable weather
is equal to the string "cloudy"

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

"sushi is delicious"
The variable x is set to 2.  The first condition fails because x is not equal to 3.  The second condition is executed because x
is greater than 0.

## Question 5

```ruby
food = "walnut"

if food == "walnut"
  puts "I'm allergic!"
end
```

Imagine that you take the code from this question, save it to a file called `snack.rb`, and run `ruby snack.rb` in your Terminal.

What would be the output? Explain your answer.
"I'm allergic"
The variable food is set to the string walnut.  The condition is executed because food is equal to walnut.
