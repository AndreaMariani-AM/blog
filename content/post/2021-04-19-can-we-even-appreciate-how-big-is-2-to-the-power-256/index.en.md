---
title: Can We Even Appreciate How Big is 2 to the Power 256?
author: Andrea Mariani
date: '2021-04-19'
slug: can-we-even-appreciate-how-big-is-2-to-the-power-256
categories: 
 - Test
tags: 
 - Blog
 - 3Blue1Brown
description: An adventure to figure out how weird numbers are
image: pexels-dids-3530102.jpg
math: true
license: ~
hidden: no
comments: yes
---

## My Guilty Pleasure

This post's gonna be a little bit different. I wanted to share one of my biggest **guilty pleasures**, and that is watching videos from [3Blue1Brown](https://www.youtube.com/channel/UCYO_jab_esuFRV4b17AJtAw), specifically nerdy videos about numbers and maths.  

I have never been a huge fan of these topics, to be honest, but I've found out that watching his videos is kinda intriguing, and ofc very informative. 

For those of you that ignore who [3Blue1Brown](https://www.youtube.com/channel/UCYO_jab_esuFRV4b17AJtAw) is, his names’ Grant Sanderson, and has a youtube channel where it combines math and entertainment.
He makes a wide range of videos covering lots and lots of topics always trying to make abstract ideas more graspable.   

The video I want to focus on today is a particular one, and actually, it's an appendix video of a longer one that tried to explain what cryptocurrencies are and how they work.  

What I want to do with this post is to summarize and report the examples used in the video to explain a single number.  

This is the video I'm talking [about](https://www.youtube.com/watch?v=S9JGmA5_unY), and tries to answer the question "Yo ok, cryptos are cool, but how secure they are? 

#### And the answer to that is $2^{256}$ .  

## [The Video](https://www.youtube.com/watch?v=S9JGmA5_unY)

Let's give a bit of context before we dive into the analysis of that video, what's $2^{256}$ ? To make this as straightforward as possible, when doing transactions with cryptocurrencies, be them done virtually, a digital signature is required to authorize transactions.  

This digital signature changes every time and makes whatever we're doing legit. But, given that digital signatures are composed of 256 bits characters that are combinations of 0s and 1s, shouldn't we be able to somehow forge a signature?

And this question introduces the whole post, which is, **How Stupidly Bad We Are at Understanding Big Numbers**.  

Since digital signatures are generated at random, a potential *crazy-cyber-son-of-a-gun* thief has no better alternative than randomly generate combinations of 0s and 1s 256 bits long, to forge our signature.  

The guessed combination should be run through a [hash function](https://en.wikipedia.org/wiki/Hash_function) that'll yield a TRUE or FALSE statement.  

This is the process in a nutshell, you generate a combination of 0s and 1s, you test it with a hash function, the result will tell you if you've found the correct digital signature associated with that transaction.

"Yeah ok, but how many combinations are there?" 

Well, on average, it'd require to generate and test $2^{256}$ combinations, and we can't even try to understand how big of a number that is.  

It's insane how our brains can't even process or imagine something that big that we immediately lose grip on reality. It's so far away from what we deal daily that's hard to appreciate how stupid that number is.

## The Number Itself

"Yeah cool ok, big big number, ok. Now, give me something to work with so I can understand it a bit better".

We'll exploit Grant's video to put this in perspective and use numbers that we're more familiar with.  

Now, I know I've just said "more familiar" but even with numbers like Billions, it's still incredibly hard to grasp them and the orders of magnitude are blurry.  

Just for reference, 4 million seconds correspond to 46 days, 4 billion, on the other hand, are **127 years**.   

First time I've heard this, I couldn't understand how my deductions were so far off from the truth, I couldn't understand why the gap between 4 million and 4 billion was that huge.

So, how secure is $2^{256}$?

Let's start by breaking it down to a bit, $2^{256}$ is $2^{32}$ multiplied by itself 8 times. $2^{32}$ is slightly easier to imagine since it's somewhere around 4 billion, so now we just need to appreciate what multiplying 4 billion by itself 8 times means.  

Let's work with that and do a little thought experiment to give meaning to those numbers.

1. Imagine you're the best hacker in the world, your super-specialized hash function is in place, your GPU is firing up and ready to parallelize the hash function.  
A really good PC can probably run around 1 billion hash functions per second. But you the best one,  and you stuff your PC somehow with more GPUs, and boom, you're up to 4 billion hashes per second (aka, 4 billion guesses per second). Let's call it Big Ass Computer.

2. Now pretend you're a millionaire and you just bought Google. There are no public numbers regarding how many servers does Google have but rumors have it in the millions ballpark.  
Since you're a millionaire, you replace all of the existing crappy Google's computers that are nowhere near your Big Ass Computer in terms of GPUs power, with a copy of your guessing beast.  
And while you are at it, why not creating a thousand copies of this Google on steroid? Now, you up to 4 billion Big Ass Computers.

3. Being so generous, you just gave to a bit more than half of the population on heart, 4 billion people, their personal super performing Google.

4. What if our galaxy had 4 billion copies of planet earth where 4 billion people have their own Google with 4 billion Big Ass Computers that can each generate and test 4 billion signatures every second?

5. And what if, there were 4 billion copies of our galaxy? I know you're losing it, hang in there.

6. 4 billion seconds? that's about 127 years

7. And 4 billion times 127 is **507 billion years**, which is roughly 37 times the age of our universe.

8. So where I'm going with this? Even if you had 4 billion galaxies, each containing 4 billion copies of planet earth where each planet has 4 billion people equipped with their own personal Google comprising of 4 billion Big Ass Computers, running each 4 billion guesses every second, and you'd go on and on guessing for 37 times the age of the whole universe, you'd still only have a **1 in a 4 billion chance** of finding the right guess and successfully forge a digital signature. That's how big that number is.

## Conclusion

"Ok, cool. That's a big number, but who cares?" 

I don't know, I think I do. First of all, I'm kinda sad for our imaginary hacker. I mean, all of the odds are against this poor guy.
But mostly, I've found out that these weird numbers and probabilities, fascinate me. How two numbers that we're familiar with, 2 and 256, can really make us wander through imaginary galaxies and computers, is incredible. 
With that being said, I'm waiting for the next [3Blue1Brown](https://www.youtube.com/channel/UCYO_jab_esuFRV4b17AJtAw) video, to blow my mind.