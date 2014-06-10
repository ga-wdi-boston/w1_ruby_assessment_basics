# Ruby Assessment - Day 2

Fork this repository, and clone the fork to your local computer. Edit this README.md file to contain the answers, and then make a pull request on Github to turn in the assessment.

## Question 1

```ruby
a = 5
b = 4
a = b
```

At the end of this program, what are the values of a and b? Try to explain, in plain English, how you got your answer for each one.

a=4, b=4. The most recent assignment of a is to the value of b, so by the end a=b=4.

## Question 2

```ruby
e = 3
f = 9
g = e + f
f == g
e = 3
```

e = 3, g = 12, f = 9. e = 3 since that was the last thing we did. f==g is not an assignment. g = e + f = 12. and f =9.

At the end of this program, what are the values of e, f, and g? Try to explain, in plain English, how you got your answer for each one.

## Question 3

```ruby
weather = "cloudy"
weather == "cloudy"
```

What is the difference between these two statements? Explain your answer.

The first one sets the variable weather to the string 'cloudy'. The second statement will evaluate to true since weather is indeed cloudy.

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

It would be 'sushi is delicious' since x is not 3 but it is greater than 0.

## Question 5

```ruby
food = "walnut"

if food == "walnut"
  puts "I'm allergic!"
end
```

Imagine that you take the code from this question, save it to a file called `snack.rb`, and run `ruby snack.rb` in your Terminal.

What would be the output? Explain your answer.

"I'm allergic" since food does equal 'walnut'
