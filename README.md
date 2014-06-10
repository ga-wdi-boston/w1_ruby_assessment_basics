# Ruby Assessment - Day 2

Fork this repository, and clone the fork to your local computer. Edit this README.md file to contain the answers, and then make a pull request on Github to turn in the assessment.

## Question 1

```ruby
a = 5
b = 4
a = b
```

At the end of this program, what are the values of a and b? Try to explain, in plain English, how you got your answer for each one.

*** At the end of the program, both a and b are equal to 4. variables can be reassigned, so though a is initially set to 5, it is reset in line 10 to the value of b at line 10, so a is reset to 4.

## Question 2

```ruby
e = 3
f = 9
g = e + f
f == g
e = 3
```

At the end of this program, what are the values of e, f, and g? Try to explain, in plain English, how you got your answer for each one.

*** At the end of the program, e is 3 (set most recently at line 24), g is 12 (because it was set as e + f with their values at line 22) and f was set again at line 23 to the boolean evaluation of the expression f is equivalent to g, which is false.

## Question 3

```ruby
weather = "cloudy"
weather == "cloudy"
```

What is the difference between these two statements? Explain your answer.

Line 34 sets the weather variable to the string 'cloudy', whereas line 35 is asking for the boolean evaluation of whether weather is currently equal to 'cloudy', which in this case is true.

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

Since x is set to the value 2 (without a way to change it), the if statement would be false, and therefore not puts. The elsif statement would be true (2 > 0) and the sole output would be a puts of "sushi is delicious".

## Question 5

```ruby
food = "walnut"

if food == "walnut"
  puts "I'm allergic!"
end
```

Imagine that you take the code from this question, save it to a file called `snack.rb`, and run `ruby snack.rb` in your Terminal.

What would be the output? Explain your answer.

The output here would be "I'm allergic!" because the variable food is set to the string 'walnut', and then there is a conditional statement that asks if food is currently equivalent to 'walnut'. This evaluates as true, so the code runs and then the program ends.
