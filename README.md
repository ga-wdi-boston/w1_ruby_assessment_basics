# Ruby Assessment - Day 2

Fork this repository, and clone the fork to your local computer. Edit this README.md file to contain the answers, and then make a pull request on Github to turn in the assessment.

## Question 1

```ruby
a = 5
b = 4
a = b
```

At the end of this program, what are the values of a and b? Try to explain, in plain English, how you got your answer for each one.

At the end of the program, both a and b are equal to 4. Even though a's value is set to 5 by the first line in the block, it's value is modified in the third line, specifically it is being set equal to the value of b. B's value is set to 4 in the second line of the block, which is why its value is 4 and the value of a is set to 4.

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

f = 9

g = 12

The first line sets e's value to 3, and the second line sets f's value to 9. The third line sets g's value to the sum of e and f, which results in a value of 12. The forth line is a boolean comparision, which asks if f's value is equal to g's value. As they are different, this would return false. E's value is modified again one the second line, where its value is set to 3 again.

## Question 3

```ruby
weather = "cloudy"
weather == "cloudy"
```

What is the difference between these two statements? Explain your answer.

The first statement is setting the weather variable to the string "cloudy". The second statement is running a boolean comparision to see if the weather variable is equal to the string "cloudy", and would return a value of true. This is because the weather variable is set to the string "cloudy" on the first line, and when the boolean comparision is run on the second line it will keep the value from the first line in the block. This produces the true result.

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

The output of this program would be "sushi is delicious". Not only because sushi is, in fact, delicious, but because the if loop is asking if x's value is equal to 3. As x's value is set to 2 on the first line of the code block, the first part of the if loop fails and moves on to the next section. Since the second section asks if x is greater than 0, it will return the puts value specified as x is equal to 2 (and thus greater than 0).

## Question 5

```ruby
food = "walnut"

if food == "walnut"
  puts "I'm allergic!"
end
```

Imagine that you take the code from this question, save it to a file called `snack.rb`, and run `ruby snack.rb` in your Terminal.

What would be the output? Explain your answer.

The output of this program would be "I'm allergic!". The food variable is set to the string "walnut" on the first line of this block, and the if loop is first asking if the value of the food variable is equal to the string "walnut". As this conditional passes, the puts value after the if statement gets run, providing the result "I'm allergic!"
