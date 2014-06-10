# Ruby Assessment - Day 2

Fork this repository, and clone the fork to your local computer. Edit this README.md file to contain the answers, and then make a pull request on Github to turn in the assessment.

## Question 1

```ruby
a = 5
b = 4
a = b
```

At the end of this program, what are the values of a and b? Try to explain, in plain English, how you got your answer for each one.

a = 4 and b = 4. a is initialized to 5 but then changed to point to the same object as b which is the int 4

## Question 2

```ruby
e = 3
f = 9
g = e + f
f == g
e = 3
```

At the end of this program, what are the values of e, f, and g? Try to explain, in plain English, how you got your answer for each one.

e = 3, f = 12, g =12. e is set to 3 at the first and last command, f is set to nine, g = e( which is 3) +f(which is 9) = 12 (sorry for the poor notation) and f compared to g just returns true.

## Question 3

```ruby
weather = "cloudy"
weather == "cloudy"
```

What is the difference between these two statements? Explain your answer.
The first one points weather at "cloudy" the second compares the weather variable to the separate "cloudy" string

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
sushi is delicious
 x is equal to 2 and not 3 but 2 is greater than 0 so the elsif puts "sushi is delicious"

## Question 5

```ruby
food = "walnut"

if food == "walnut"
  puts "I'm allergic!"
end
```

Imagine that you take the code from this question, save it to a file called `snack.rb`, and run `ruby snack.rb` in your Terminal.

What would be the output? Explain your answer.
I'm allergic!
This points the food variable at a string object, "walnut" which when compared to "walnut" returns true and puts the allergic declaration.
