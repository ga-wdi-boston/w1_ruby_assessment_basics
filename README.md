# Ruby Assessment - Day 2

Fork this repository, and clone the fork to your local computer. Edit this README.md file to contain the answers, and then make a pull request on Github to turn in the assessment.

## Question 1

```ruby
a = 5
b = 4
a = b
```

At the end of this program, what are the values of a and b? Try to explain, in plain English, how you got your answer for each one.

b is 4, because you set b to 4 and you never modified it. a is also 4. At first you set a to 5, but then you set a to be equal to b, so it is 4.

## Question 2

```ruby
e = 3
f = 9
g = e + f
f == g
e = 3
```

At the end of this program, what are the values of e, f, and g? Try to explain, in plain English, how you got your answer for each one.

e is 3, because you assigned it a value of 3 and never changed it.
f is 9, because you assigned it a value of 9. You did not assign it to have the same value as g. In line 23, you compared the two to see if they were the same, resulting in a boolean.
g is 12, because you assigned it the value of e + f.

## Question 3

```ruby
weather = "cloudy"
weather == "cloudy"
```

What is the difference between these two statements? Explain your answer.

Line 36 sets the variable weather to the string "cloudy". Line 37 asks whether the variable weather is equal to the string "cloudy", and returns a boolean.

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

Output: "sushi is delicious"
x is set to 2. Then, the program enters the if statement. x is not equal to 3, so it does not print "sushi is tasty" and it continues. x IS greater than zero, so the program does print "sushi is delicious"

## Question 5

```ruby
food = "walnut"

if food == "walnut"
  puts "I'm allergic!"
end
```

Imagine that you take the code from this question, save it to a file called `snack.rb`, and run `ruby snack.rb` in your Terminal.

What would be the output? Explain your answer.

Output: "I'm allergic!"
The first line sets the variable food to the string "walnut". Then, the if statement asks if food is equal to the "walnut" string. It is, so the line of code within the statement executes. This prints "I'm allergic" to the terminal.
