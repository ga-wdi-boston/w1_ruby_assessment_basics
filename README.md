# Ruby Assessment - Day 2

Fork this repository, and clone the fork to your local computer. Edit this README.md file to contain the answers, and then make a pull request on Github to turn in the assessment.

## Question 1

```ruby
a = 5
b = 4
a = b
```
b is never acted on, so it remains 4
a, going from right to left with our assignment operator, would make a = 4

## Question 2

```ruby
e = 3
f = 9
g = e + f
f == g
e = 3
```
e is 3 as it is defined on the last line
f still equals 9 as it was just evaluated against g
g is 10 as it is never assigned a new value


## Question 3

```ruby
weather = "cloudy"
weather == "cloudy"
```

for the =, cloudy is assigned to weather
for the ==, we are looking to see if weather = cloudy is true or false.
weather would equal "cloudy" after this ran, and thus weather == "cloudy" would return true.

## Question 4

```ruby
x = 2

if x == 3
  puts "sushi is tasty"
elsif x > 0
  puts "sushi is delicious"
end
```
since x == 3 is false, we would move on to the next else conditional.  as x is greater than 0, the elsif condition is true, and we would puts a line that says "sushi is delicious"


## Question 5

```ruby
food = "walnut"

if food == "walnut"
  puts "I'm allergic!"
end
```

food is devined to equal "walnut", so food == "walnut" evaluates true.  since the if condition is met, you would have an output line of "I'm allergic!"
