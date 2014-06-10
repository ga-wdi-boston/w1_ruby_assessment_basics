# Ruby Assessment - Day 2

Fork this repository, and clone the fork to your local computer. Edit this README.md file to contain the answers, and then make a pull request on Github to turn in the assessment.

## Question 1

```ruby
a = 5
b = 4
a = b
```

At the end of this program, what are the values of a and b? Try to explain, in plain English, how you got your answer for each o

At the end of the program the value of a and b are both 4. The variable a is initially set to 5 but later the value of a is set to the value of b, which is 4.

## Question 2

```ruby
e = 3
f = 9
g = e + f
f == g
e = 3
```

At the end of this program, what are the values of e, f, and g? Try to explain, in plain English, how you got your answer for each one.

At the end of the program the variables have the following values:
g = 12
e = 3
f = 9
f retains 9, as 'f == g' only tests  if their values are the same and would return false, rather than assigning g's value to f (f = g)
g is assigned the value of e + f which is 12, and even though the value of e does not change after it is initialized to 3 on the first line, it is re-assigned the value of 3 at the end, so it's value remains 3.

## Question 3

```ruby
weather = "cloudy"
weather == "cloudy"
```

What is the difference between these two statements? Explain your answer.

The first line creates a variable called weather and assigns it the string "cloudy"
the second line is a comparison asking if the variable weather is the same as the string "cloudy".

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

The output would be "sushu is delicious"
The variable x is initialized to 2, and then checked to see if it is equal to 3. It is not, so puts "sushi is tasty" does not execute. The elsif statement checks if x is greater than 0, which it is, and so puts "sushi is delicious" is executed.

## Question 5

```ruby
food = "walnut"

if food == "walnut"
  puts "I'm allergic!"
end
```

Imagine that you take the code from this question, save it to a file called `snack.rb`, and run `ruby snack.rb` in your Terminal.

What would be the output? Explain your answer.

The output would be "I'm allergic!"
The variable food is initialized to "walnut" and then the if statement checks to see if the variable food is the same as the strong "walnit", which it is. As a result puts "I'm allergic!" executes.
