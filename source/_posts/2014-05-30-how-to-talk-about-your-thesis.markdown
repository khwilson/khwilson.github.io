---
layout: post
title: "How to talk about your thesis"
date: 2014-05-23 14:23:07 -0400
comments: true
categories: academia math interviews
---

I got my PhD in math from Princeton in January of 2013. By that time, I had
already been working at [Knewton](http://www.knewton.com) as a data scientist.
Nowadays I am bombarded with requests for coffee and advice from mathematicians,
sociologists, and many others all wanting to leave academia. Personally, I
think this points to a massive failing on the part of the academy to help its
students succeed in the outside world, but I am not going to concentrate on that
in this post. Instead, I want to give some advice on how to actually get a job
outside of the university system, especially in fields that involve technology
and quantitative skills. I will be writing several of these, but this is just
the first.

In this post, I will be writing about how to talk about your thesis. I am going
to focus on math theses because that is the field I come from, but probably
the advice applies to other fields as well, especially if they are quantitative.
But I will make the strong assumption that you are interviewing for a relatively
technical position, i.e., a position that, if it doesn't directly use the
content of your dissertation, does use the quantitative and qualitative research
skills that you picked up during that time.

## They are not asking about the content

Look, I know that already on page one of your thesis you were using words that
you didn't learn until you started grad school; I did too! But what people are
asking when they ask you to describe your thesis has absolutely nothing to do
with the __content__ of your thesis, but rather your ability to explain a
complicated subject to somebody who is unfamiliar with all the background
material.

Keep in mind that this is going to be something you do all the time in industry!
And there are going to varying levels of background knowledge. Your immediate
boss might also have a PhD in topology (though they probably haven't used that
knowledge in a few years), but his boss at best has a PhD in particle physics
and probably actually has an MBA. Your CEO almost certainly is unaware of the
cutting edge techniques in algebraic geometry, and there's a high chance you're
going to have to justify your work to him eventually.

So the first step to being good at explaining your thesis is to understand that
they are judging your talent in the following areas:

1. Ability to judge the background of your audience;
2. Ability to explain to a diverse audience the essence of technical material;
3. Ability to take a complex problem and explain how you approached it;
4. Ability to sell your thesis's contribution as meaningful to the world.

Let's address each of these in turn, especially number 4 which tends to make
academic math people recoil.

## Judging the background of your audience

If you're interviewing for a job with a PhD, it's very likely that your
interviewer is naturally curious. That means that they _actually want to learn
something during your interview_. If you can teach them something new, you're
going to be remembered. But, as we talk about a lot at work, in order to most
effectively teach somebody, you need to engage them in the so-called [Zone of
Proximal Development](http://en.wikipedia.org/wiki/Zone_of_proximal_development). That is, you have to figure out what they know
and challenge them just beyond that point.

Since you're interviewing for a relatively technical position, it is safe to
say that _most_ of your interviewers will have some overlap with your technical
background. For instance, if you're interviewing for position as a data
scientist at Knewton, you're going to be interviewed by people with graduate
degrees or years of experience in fields such as neuroscience, number theory,
social network analysis, psychometrics, and computer vision among others. Each
and every one of these fields has a different language and framework for
discussing similar concepts, but each of these people can do calculus,
understand diagrams, and compute a p-value. That is, there is some level of
common ground, though it might take some conversation to find it.

## Explaining to a diverse audience

Your task is
to turn whatever it is you worked on into _something_ that you can explain
in 20 or so minutes to another person. A couple of those minutes are probably
going to be spend judging the background of your audience, so it's probably
better to bank on 10-15 minutes you get to actually explain _your entire
thesis_.

This is the point at which I get incredulous stares, but this is where you
should draw upon your teaching experience. They're not expecting to get a deep
understanding of what you did in this time; they just want you to teach them
something.

As such, it is quite likely that if you wrote a dissertation on knot theory that
you should dedicate 1 minute to something resembling your main theorem, and
9-14 minutes explaining
* what knot theory is,
* how knot theory fits into the grand scheme of mathematics,
* the big, open questions of knot theory, and
* how it relates to the world.
And it is best to employ those tried and true teaching techniques to do it,
especially
* example,
* metaphor, and
* asking for feedback.

Remember, in the end your interviewer couldn't care less about that amazing
theorem you proved on page 87 of your thesis; they care about learning
something. So approaching this whole part of the interview as a teacher is, I
think, your best bet.

## Dissecting a complex problem

In those 9-14 minutes you spend explaining the field, you should definitely
spend a good deal of time explaining how you even arrived at the problem that
you were solving in your thesis. If you're doing math, it is not at all likely
that you are actually solving directly the problem that you set out to solve,
but rather an example case, or a generalization, or something orthogonal that
you hope will give you enough analogies and leads to solve the original.

Because there's a lot of background material for you to get through, I tend
to favor breaking the problem down for the other person, and, if there's time,
to give at least one example of an insight you made in your thesis. Remember
that you almost certainly will have to do this via analogy as your audience
isn't going to understand the technical details!

## Selling your thesis's contributions

This is the hardest part for a number theorist or an algebraic geometer. They
tend to resort to cryptography, which they often know absolutely nothing about.
My advice to sell your thesis's contributions is to first _work on a real-world
application of your thesis_. So, for instance, if you are a number theorist
planning to sell its connections to cryptography, do some cryptography!

But I also like to turn this piece of advice on its head. Instead of selling the
real-world contributions of your thesis, sell how other fields have affected
your work. If you are applying to tech jobs, by far the easiest way to do this
is to actually use a computer to compute something rather difficult.

Thankfully, a lot of projects have already given a long head start to doing
this. Most famously, there is the [SAGE](http://www.sagemath.org). There are
also [Macaulay](http://www.math.uiuc.edu/Macaulay2/) in commutative algebra and [SnapPea](http://en.wikipedia.org/wiki/SnapPea) in
low-dimensional topology.

If you do not know how your thesis relates to the real world, or do not care
to find out, then try using these tools to do an exploration of something to
do with your thesis. This is infinitely easier if you are in a field like
arithmetic or algebraic statistics. But even in crazy fields like ergodic
theory, there are ways to use computers. Be creative.

# Putting it all together

Now let us do an example of how you might explain your work getting better
approximations to the distribution of imaginary parts of zeros of the zeta
function.

So, you remember what a prime number is I'm guessing. Tons and tons of people
study these things, since they form the basic building blocks of multiplication
and the basic building blocks of much of the internet's security.

Some people approach prime numbers _algebraically_: They look at the definition
of a prime number (a number that has only 1 and itself as divisors) and look
for analogies in other, more esoteric number systems. They then hope that those
analogies will tell us more about the prime numbers themselves. For instance,
this line of inquiry really drove Andrew Wiles' work on Fermat's Last Theorem.

I approached it _analytically_. You see, it turns out that while we completely
understand prime numbers _multiplicatively_, we don't really understand them
_additively_. For instance, we don't know if there are infinitely many primes
whose _difference_ is 2. But we do know that the number of primes less than x
grows like x / log(x).

This is typically proven by looking at the so-called zeta function, which is
defined as
```
zeta(s) = sum 1/n^s
```
Do you remember the p-test from calculus? Well, that says that this sum
converges for $s > 1$, but that it goes to infinity if ``s==1``. So it turns out
we write it down a different way that is defined for every complex number ``s != 1``
agrees with the above definition for $s > 1$.

But now it turns out that we can write this sum a different way:
```
zeta(s) = sum 1/n^s = prod 1/(1 - p^(-s))
```
where the product is over all _prime_ numbers. (Here you might want to let them work out
the first few terms, but otherwise leave as an exercise.)

A couple observations: We now have a direct, functional link between addition
and multiplication. Thus, this function should (and does) serve as the basis of
most explorations into the distribution of prime numbers. And as an example of
its power, note that if there were a _finite_ number of primes, that product
would converge at $s = 1$. But we know it does not by the p-test. So that means
that this equality alone has proven that there are an infinite number of primes.

Now it turns out that the conjecture that
```
\pi(x) ~ x / log(x) + O(x^(1/2 + eps)
```
is **equivalent** to the statement that, in that alternative way of writing it,
``zeta(s)`` is finite everywhere but ``s == 1`` and ``zeta(s) === 0`` only if the
real part of ``s`` is ``1/2``. This is the Riemann Hypothesis.

But we can go much farther, and we can ask, for instance, if the Riemann
Hypothesis is true, then how many zeros are there with _imaginary_ part less
than some ``T``. That is, how does the function
```#{ t > 0 : zeta(1/2 + it) == 0 }```
grow?

From here, you have to explain some small part of your bounds on the number of
zeros with imaginary part less than ``T``. The point here is that you have quickly
taught them something with a big **WOW** factor (how the multiplicative and additive
aspects of number prime numbers are related by the zeta function) and you have quickly
gotten to a tangible problem you can explain.
