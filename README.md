# Ruby Assessment - Day 2

Fork this repository, and clone the fork to your local computer. Edit this README.md file to contain the answers, and then make a pull request on Github to turn in the assessment. 

## Question 1

```ruby
a = 5
b = 4
a = b
```

At the end of this program, what are the values of a and b? Try to explain, in plain English, how you got your answer for each one. 

ANSWER: a equals 4 because b is 4 and that line overeides the right line.

## Question 2

```ruby
e = 3
f = 9
g = e + f
f == g
e = 3
```

 At the end of this program, what are the values of e, f, and g? Try to explain, in plain English, how you got your answer for each one. 

ANSWER: e = 3, f = 12 and g = 12  because f == g ---> 3 + 9 = g there for f = 12 as well.  e = 3 because evident in the last part of the code. 

## Question 3

```ruby
weather = "cloudy"
weather == "cloudy" 
```

What is the difference between these two statements? Explain your answer. 

ANSWER: weather = cloudy is assigning weather as cloudy.  weather == cloudy is asking for eequality.

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

ANSWER: sushi is delicious would be the output because x does not equal 3 therfore we got to the next time and it IS greater than 0 so it puts that output


## Question 5

```ruby
food = "walnut"

if food == "walnut"
  puts "I'm allergic!"
end
```

Imagine that you take the code from this question, save it to a file called `snack.rb`, and run `ruby snack.rb` in your Terminal. 

What would be the output? Explain your answer.

ANSWER: I'm allergic would be the output because food is assigned walnut is true. 

