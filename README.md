# Ruby Assessment - Day 2

Fork this repository, and clone the fork to your local computer. Edit this README.md file to contain the answers, and then make a pull request on Github to turn in the assessment.

## Question 1

```ruby
a = 5
b = 4
a = b
```

At the end of this program, what are the values of a and b? Try to explain, in plain English, how you got your answer for each one.

### Answer 1

a and b are both 4.

First, b is set to 4, and then a gets reassigned to whatever b's value is at the time of assignment, which is 4.

## Question 2

```ruby
e = 3
f = 9
g = e + f
f == g
e = 3
```

At the end of this program, what are the values of e, f, and g? Try to explain, in plain English, how you got your answer for each one.


### Answer 2

e = 3
f = 9
g = (3 + 9) = 12

The only one that doesn't assign variables is f == g, which evaluates f and g to see if they're equal.

## Question 3

```ruby
weather = "cloudy"
weather == "cloudy"
```

What is the difference between these two statements? Explain your answer.

### Answer 3

In the first instance, the variable weather is being assigned the string "cloudy". In the 2nd instance, the value of the variable weather is being evaluated against the string "cloudy", to see if they match.

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

### Answer 4

The output would be "sushi is delicious", because the 2nd conditional is the only one that evaluates to true (because x is greater than 0, but not equal to 3)

## Question 5

```ruby
food = "walnut"

if food == "walnut"
  puts "I'm allergic!"
end
```

Imagine that you take the code from this question, save it to a file called `snack.rb`, and run `ruby snack.rb` in your Terminal.

What would be the output? Explain your answer.

### Answer 5

The statement food == "walnut" evaluates to true, so the output would say "I'm allergic!"

