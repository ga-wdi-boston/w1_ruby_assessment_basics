# Ruby Assessment - Day 2

Fork this repository, and clone the fork to your local computer. Edit this README.md file to contain the answers, and then make a pull request on Github to turn in the assessment.

## Question 1

```ruby
a = 5
b = 4
a = b
```

At the end of this program, what are the values of a and b? Try to explain, in plain English, how you got your answer for each one.
a = 4; b = 4. 'a' is initially assigned to 5, but is reassigned to the value of 'b', which is 4. 'b' is assigned to 4.

## Question 2

```ruby
e = 3
f = 9
g = e + f
f == g
e = 3
```

At the end of this program, what are the values of e, f, and g? Try to explain, in plain English, how you got your answer for each one.
e = 3 # e is intially assigned to 3, and then reassigned to 3.
f = 9 # f is assigned to 9. It is later compared to 'g', but not assigned to the value of 'g'
g = 12 # 'g' is assigned to the evaluation of 'e' (3) plus 'f' (9), totaling 12.


## Question 3

```ruby
weather = "cloudy"
weather == "cloudy"
```

What is the difference between these two statements? Explain your answer.
1. the variable weather is assigned to the string 'cloudy'
2. the variable weather is compared to the string 'cloudy'. Resulting in true.

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
The terminal will put the string (puts) "sushi is delicious."
This is because x is assigned to the variable 2.
Therefore it does not equal 3, bypassing the if statement to the elsif statement.
x is greater than 0, so it enters the elsif statement and puts "sushi is delicious"

## Question 5

```ruby
food = "walnut"

if food == "walnut"
  puts "I'm allergic!"
end
```

Imagine that you take the code from this question, save it to a file called `snack.rb`, and run `ruby snack.rb` in your Terminal.

What would be the output? Explain your answer.
The terminal will put the string "I'm allergic!"
This is because food is assigned to the string "walnut"
Therefore the if statement is true, the variable food does equal the string "walnut" and the terminal puts "I'm allergic!"
