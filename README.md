# Ruby Assessment - Day 2

Fork this repository, and clone the fork to your local computer. Edit this README.md file to contain the answers, and then make a pull request on Github to turn in the assessment.

## Question 1

```ruby
a = 5
b = 4
a = b
```

At the end of this program, what are the values of a and b? Try to explain, in plain English, how you got your answer for each one.

a = 4
b = 4

The last ruby statement in the question overwrites the a = 5 to a = 4.

## Question 2

```ruby
e = 3
f = 9
g = e + f
f == g
e = 3
```

At the end of this program, what are the values of e, f, and g? Try to explain, in plain English, how you got your answer for each one.

e = 3 since it's in the end of the ruby program.
f = 9 since it's pointed to 9. f == 9 is boolean, it doesn't change the value inside the f.
g = 12 it's point to a value e(=3) + f(=9).




## Question 3

```ruby
weather = "cloudy"
weather == "cloudy"
```

What is the difference between these two statements? Explain your answer.

First statement assigns word cloudy to variable weather.
Second statement is a boolean. It checks if the variable weather equals "cloudy". Returns true if the weather equals "cloudy"

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

output: sushi is delicious.

Since the x doesn't equals 3 it goes to the elsif statement. Since the x is greater than 0 it execute the code inside the elseif.

## Question 5

```ruby
food = "walnut"

if food == "walnut"
  puts "I'm allergic!"
end
```

Imagine that you take the code from this question, save it to a file called `snack.rb`, and run `ruby snack.rb` in your Terminal.

What would be the output? Explain your answer.

output: I'm allergic!

The statement checks if the variable food equals walnut. Since the food = "walnut" the if statement returns true then puts "I'm allergic!".
