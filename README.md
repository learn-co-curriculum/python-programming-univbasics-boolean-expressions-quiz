# Booleans and Comparisons Quiz

Here's a quiz to test your grasp of compound conditional expressions.

???

# Let's Practice!

?: `false && true`

( )`true` (X)`false`

?: `true && true`

(X)`true` ( )`false`

?: `"test" == "test"`

(X)`true` ( )`false`

?: `10 == 10 || 20 != 10`

(X)`true` ( )`false`

?: `10 == 10 && 20 == 10`

( )`true` (X)`false`

?: `true && 10 == 10`

(X)`true` ( )`false`

?: `true || 10 == 10`

(X)`true` ( )`false`

?: `false && 10 != 10`

( )`true` (X)`false`

?: `"boolean" == "booleans"`

( )`true` (X)`false`

?: `"boolean" != "booleans"`

(X)`true` ( )`false`

?: `10 != 0 && 20 == 10`

( )`true` (X)`false`

?: `"boolean" == 1`

( )`true` (X)`false`

?: `!(true && false)`

(X)`true` ( )`false`

?: `!(1000 == 1 || 10000 == 10000)`

( )`true` (X)`false`

?: `!(10 == 10 && 20 != 10)`

( )`true` (X)`false`

?: `!(1 != 100 || 30 == 40)`

( )`true` (X)`false`

?: `!("boolean" == "booleans" && "Code" == "Fun")`

(X)`true` ( )`false`

?: `1 == 1 && (!("boolean" == 1 || 1 == 0))`

(X)`true` ( )`false`

?: `"strong" == "coffee" && (!(30 == 40 || 30 == 30))`

( )`true` (X)`false`

?: `30 == 30 && (!("boolean" == "booleans" || "Coding" == "Awesome"))`

(X)`true` ( )`false`

???

## More Comparison Operators

Ruby is good at comparing things. For instance, it knows that `14` is larger than `3`. Let's see that in action.

```rb
14 > 3 #=> true
```

Here, `14` is larger than `3`, so Ruby evaluates this to `true`. Comparisons in Ruby always evaluate to `true` or `false`.

The commonly used comparison operators are:

| Operator | Operation |
|:--------:|:----------|
| `==`     | If the values of the two operands are *equal*, then the evaluation is `true`. |
| `!=`     | If the values of the two operands are *not equal*, then the evaluation is `true`. |
| `>`      | If the value of the left operand is *greater than* the value of the right operand, then the evaluation is `true`. |
| `<`      | If the value of the left operand is less than the value of the right operand, then the evaluation is `true`. |
| `>=`     | If the value of the left operand is *greater than or equal to* the value of the right operand, then the evaluation is `true`. |
| `<=`     | If the left operand is *less than or equal to* the value of the right operand, then the evaluation is `true`. |

Ruby can compare a lot more than just numbers. It can also compare strings:

```rb
"yellow" == "yellow" #=>true
```

And variables with known values:

```rb
my_mood = "happy"

my_mood == "happy" #=> true
```

It can also compare variables against other variables:

```ruby
easter_eggs = 16
ducklings = 3

easter_eggs > ducklings #=> true

ducklings >= easter_eggs #=> false

ducklings == easter_eggs #=> false

# if you call class on a variable, you can see if it's a string, an integer, etc.

ducklings.class #=> Fixnum
easter_eggs.class #=> Fixnum
ducklings.class == easter_eggs.class #=> true
```

Comparison operators are essential to developing logical flow.

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/booleans-ruby-readme' title='Booleans and Comparisons'>Booleans and Comparisons</a> on Learn.co and start learning to code for free.</p>

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/booleans-ruby-readme'>Booleans</a> on Learn.co and start learning to code for free.</p>
