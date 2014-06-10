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

value of 'a' is reassigned to the value of 'b' which is 4

## Question 2

```ruby
e = 3
f = 9
g = e + f
f == g
e = 3
```

At the end of this program, what are the values of e, f, and g? Try to explain, in plain English, how you got your answer for each one.

e = 3
f = false
g = 12

'e' is 3 as assigned at the end of the code
'f' is false because it does not equal the value of 'g'
'g' is 12 as e + f is assigned 3 + 9, which is 12

## Question 3

```ruby
weather = "cloudy"
weather == "cloudy"
```

What is the difference between these two statements? Explain your answer.

weather = "cloudy" sets the variable 'weather' as the string "cloudy"
weather == "cloudy" asks weather or not the variable 'weather' is equal to "cloudy"
this should return "true"

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

this code would return "sushi is delicious". This is because x is 2 and does not equal 3 so the 'if' statement fails so the 'elsif' statement goes through

## Question 5

```ruby
food = "walnut"

if food == "walnut"
  puts "I'm allergic!"
end
```

Imagine that you take the code from this question, save it to a file called `snack.rb`, and run `ruby snack.rb` in your Terminal.

What would be the output? Explain your answer.

the output would be "I'm allergic!" because the variable "food" is set to the string "walnut". The 'if' statement declares that if the variable "food" is equal to the string "walnut", then it will output, "I'm allergic!"
