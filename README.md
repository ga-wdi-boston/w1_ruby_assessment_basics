# Ruby Assessment - Day 2

Fork this repository, and clone the fork to your local computer. Edit this README.md file to contain the answers, and then make a pull request on Github to turn in the assessment.

## Question 1

```ruby
a = 5
b = 4
a = b
```

At the end of this program, what are the values of a and b? Try to explain, in plain English, how you got your answer for each one.
# a = 4 and b = 4. 4 is assigned to b, and then a is (re)assigned to equal # b, so therefore a is equal to 4 as well.

## Question 2

```ruby
e = 3
f = 9
g = e + f
f == g
e = 3
```

At the end of this program, what are the values of e, f, and g? Try to explain, in plain English, how you got your answer for each one.

# g is assigned the value of e + f, which is 12, so g = 12.
# e = 3 and f = 3 because they were assigned those values.

## Question 3

```ruby
weather = "cloudy"
weather == "cloudy"
```

What is the difference between these two statements? Explain your answer.
# In the first statement, the string "cloudy" is assigned to the variable # weather.
# In the second statement, the variable weather is being compared to the
# string "cloudy" to see whether they are equal.

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

# "sushi is delicious" because the first condition is evaluated to false
# but the second one is true.

## Question 5

```ruby
food = "walnut"

if food == "walnut"
  puts "I'm allergic!"
end
```

Imagine that you take the code from this question, save it to a file called `snack.rb`, and run `ruby snack.rb` in your Terminal.

What would be the output? Explain your answer.

# "I'm allergic". Since food does equal "walnut", the if statement is true,
# and therefore, the program puts "I'm allergic".
