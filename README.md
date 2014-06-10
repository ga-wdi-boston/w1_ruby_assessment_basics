# Ruby Assessment - Day 2

Fork this repository, and clone the fork to your local computer. Edit this README.md file to contain the answers, and then make a pull request on Github to turn in the assessment.

## Question 1

```ruby
a = 5
b = 4
a = b
```

At the end of this program, what are the values of a and b? Try to explain, in plain English, how you got your answer for each one.

a = 4 and b = 4. b = 4 because that is the value that is assigned to it. a = 4 because b is the last statement that is evaluated in this program, so the return value is a = 4.

## Question 2

```ruby
e = 3
f = 9
g = e + f
f == g
e = 3
```

At the end of this program, what are the values of e, f, and g? Try to explain, in plain English, how you got your answer for each one.

e = 3, f = false, g = 12.

e = 3 because that is the value that is assigned to it.
f = false because the last statement for f is a boolean expression saying that f is equal to g. It evaluates as false because 9 does not equal 12.
g = 12 because 3 + 9 equals 12.

## Question 3

```ruby
weather = "cloudy"
weather == "cloudy"
```

What is the difference between these two statements? Explain your answer.
The first statement is setting the variable weather to "cloudy." The second statement is a boolean expression stating that weather is equal to cloudy.

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

The output would be "sushi is delicious" because 2 is not equal to 3, but it is greater than zero, so it fulfills the second statement, thus puts-ing "sushi is delicious".

## Question 5

```ruby
food = "walnut"

if food == "walnut"
  puts "I'm allergic!"
end
```

Imagine that you take the code from this question, save it to a file called `snack.rb`, and run `ruby snack.rb` in your Terminal.

What would be the output? Explain your answer.

I think the output would error out because you need an escape sequence (\\) for the apostrophe in "I'm", otherwise the program will think that the string is complete after 'I'.
