---
layout: post
title:  "Examples of unlearning"
date:   2018-05-21
---

I was being interviewed for our college's software research lab during my masters, and I claimed that my strength is: "... the ability to learn, unlearn, and relearn."

I knew back then too, that this was an important ability and I try to work on improving it.

It'll be nice to have a list of what I had to unlearn and replace with a new learning.

### Unlearned the behaviour of equals operator (`=`) (2018-05-21)

Learning Elixir made me do it. In Elixir, `=` doesn't do assignment but does _pattern matching_, hence it is called a _match_ operator.

As Dave Thomas identified, Joe Armstrong, Erlang's creator compares the equals in Erlang to that used in algebra.

`x = a + 1` is not meant to assign the value of `a + 1` to `x`, but it asserts that `x` and `a + 1` are equal.

So, if you know the value of `x` or `a`, you can find out the value of the other.

> His point is that you had to unlearn the algebraic meaning of = when you first came across assignment in imperative programming languages. Now’s the time to un-unlearn it.
>
> – Dave Thomas, in Programming Elixir
