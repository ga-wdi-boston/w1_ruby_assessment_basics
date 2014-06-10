# Ruby Assessment - Day 2

Fork this repository, and clone the fork to your local computer. Edit this README.md file to contain the answers, and then make a pull request on Github to turn in the assessment.

## Question 1

```ruby
a = 5
b = 4
a = b
```

At the end of this program, what are the values of a and b? Try to explain, in plain English, how you got your answer for each one.

a and b both equal 4. a is originally assigned 5, but on line 10 is assigned b (which was previously assigned 4)

## Question 2

```ruby
e = 3
f = 9
g = e + f
f == g
e = 3
```

At the end of this program, what are the values of e, f, and g? Try to explain, in plain English, how you got your answer for each one.

e is 3, f is 9, g is 12. The comparison 'f==g' does not mutate either value, so the assignments of the first 3 lines hold. e is redundantly reassigned 3 at the end.

## Question 3

```ruby
weather = "cloudy"
weather == "cloudy"
```

What is the difference between these two statements? Explain your answer.

The first statement assigned the variable weather to the string "cloudy," whereas the second statement tests if the variable weather is equivalent to the string "cloudy" (which it is, so the statement will return true)

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

x is assigned 2, so the elsif branch of the conditional will be executed and "Sushi is delicious" would appear in the terminal.

## Question 5

```ruby
food = "walnut"

if food == "walnut"
  puts "I'm allergic!"
end
```

Imagine that you take the code from this question, save it to a file called `snack.rb`, and run `ruby snack.rb` in your Terminal.

What would be the output? Explain your answer.

the variable food is set to "walnut", so the if statement will evaluate to true, and "I'm allergic!" will appear in the terminal.
