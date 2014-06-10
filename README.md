# Ruby Assessment - Day 2

Fork this repository, and clone the fork to your local computer. Edit this README.md file to contain the answers, and then make a pull request on Github to turn in the assessment.

## Question 1

```ruby
a = 5
b = 4
a = b
```

At the end of this program, what are the values of a and b? Try to explain, in plain English, how you got your answer for each one.

>Answer: Both a and b = 4 because b was assigned the value 4 and was never changed and a = b so the value of a is changed to 4 even though it was first declared to be 5.

## Question 2

```ruby
e = 3
f = 9
g = e + f
f == g
e = 3
```

At the end of this program, what are the values of e, f, and g? Try to explain, in plain English, how you got your answer for each one.

>Answer: E = 3 since there is a clear assignment on the last line g = 12 and the assignment is never changed. even though it says that f == g  f is not assigned g's value so f = 9.


## Question 3

```ruby
weather = "cloudy"
weather == "cloudy"
```

What is the difference between these two statements? Explain your answer.

>Answer: The first line assigns "cloudy" to the variable weather and it will stay that way until it is assigned a different value. The second line states that weather is EQUAL to "cloudy" but if it were previously assigned a different value it would revert to that value if the variable were used again - in that case "cloudy" would not stick.

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

>Answer: The terminal would print "sushi is delicious" because x is greater than 0 (it's true)
but x does NOT equal 3 so "sushi is tasty" will not print.

## Question 5

```ruby
food = "walnut"

if food == "walnut"
  puts "I'm allergic!"
end
```

Imagine that you take the code from this question, save it to a file called `snack.rb`, and run `ruby snack.rb` in your Terminal.

What would be the output? Explain your answer.

Since food is equal to walnut and the program tells the terminal to print I'm allergic when food is equal to walnut "I'm allergic" will print and then the program would end.
