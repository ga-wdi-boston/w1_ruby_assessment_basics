# Ruby Assessment - Day 2

Fork this repository, and clone the fork to your local computer. Edit this README.md file to contain the answers, and then make a pull request on Github to turn in the assessment.

## Question 1

```ruby
a = 5
b = 4
a = b
```

At the end of this program, what are the values of a and b? Try to explain, in plain English, how you got your answer for each one.

a = 4
b = 4
In line 10, 'a' is reassigned to b's assignment, which is 4.  'b' is not affected and remains 4.

## Question 2

```ruby
e = 3
f = 9
g = e + f
f == g
e = 3
```

e = 3   # 'e' is assigned to 3 in the last line of the program, so final answer!
f = 9   # 'f' is assigned to 9 in line 23.  Line 25 is evaluating if f is equal to g (false)
g = 12  # 'g' is assigned to the sum of e + f which are 3 and 9 prior to it, respectively.

At the end of this program, what are the values of e, f, and g? Try to explain, in plain English, how you got your answer for each one.

## Question 3

```ruby
weather = "cloudy"
weather == "cloudy"
```

What is the difference between these two statements? Explain your answer.

In line 38, weather is assigned the string "cloudy"
In line 39, this is a boolean statement asking if weather is equal to cloudy (and it is)

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

=> "sushi is delicious"
# x (which is assigned to 2) is not equal to 3, so it moves to the elsif where it evaluates to greater than 0, so sushi is delicious is printed.

## Question 5

```ruby
food = "walnut"

if food == "walnut"
  puts "I'm allergic!"
end
```

Imagine that you take the code from this question, save it to a file called `snack.rb`, and run `ruby snack.rb` in your Terminal.

What would be the output? Explain your answer.

=> "I'm allergic" would be printed.
# Food is assigned to the string 'walnut'; In the 'IF' statement, food is equal to wanut evaluates to true, so the program prints "I'm allergic"
