# Ruby Assessment - Day 2

Fork this repository, and clone the fork to your local computer. Edit this README.md file to contain the answers, and then make a pull request on Github to turn in the assessment.

## Question 1

```ruby
a = 5
b = 4
a = b
```

At the end of this program, what are the values of a and b? Try to explain, in plain English, how you got your answer for each one.

b = 4 because the value of b is never reassigned
a = 4 because a is reassigned to the value of b, which is 4.

## Question 2

```ruby
e = 3
f = 9
g = e + f (12)
f == g
e = 3
```

At the end of this program, what are the values of e, f, and g? Try to explain, in plain English, how you got your answer for each one.

e = 3 because it is reassigned the value of 3 at the end of the program.
f = 9 because it is never reassigned. f == g returns the value false because 9 != 12, but it does not assigned this true value to any variable
g = 12 because 3 + 9 = 12, and this is the only value assignment for g.

## Question 3

```ruby
weather = "cloudy"
weather == "cloudy"
```

What is the difference between these two statements? Explain your answer.

The first instance assigned the string "cloudy" to the variable weather.
The second instance evaluates the expression is weather equal to the string "cloudy". This evaluates to true because the variable weather is assigned the value of the string "cloudy"

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

It would output "sushi is delicious" because x = 2, which is greater than 0, but not equal to 3. This means that the if statement evaluates to false and the elsif statement evaluates to true, so its content is run.

## Question 5

```ruby
food = "walnut"

if food == "walnut"
  puts "I'm allergic!"
end
```

Imagine that you take the code from this question, save it to a file called `snack.rb`, and run `ruby snack.rb` in your Terminal.

What would be the output? Explain your answer.
It would output "I'm allergic!" because food was originally assigned the value of the string "walnut", and therefore the boolean expression asking if food is equal to walnut would evaluate as true and execute the code inside the if statement.
