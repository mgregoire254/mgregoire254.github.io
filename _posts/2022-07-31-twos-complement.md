---
title: Two's Complement
date: 2022-07-31 12:00:00 +0100
categories: [programming, computer science, math]
tags: [code, math]
---

# Two's Complement

Recently in one of my current courses we went over the concept of two's complement.  I had always wondered how negative numbers are handled at the low level in computers since representing them in binary is an issue.  Overall I understood the concepts but for some reason doing conversions into two's complement just wasnt clicking.  I think it was just the way it was being explained.  I decided to make this quick post just in case anyone else is having trouble.

## The steps  

1. Invert the bits
2. Add 1  

Yes its really that easy. I felt really stupid after I figured it out.

### Examples   

Lets take a number, say 011101 and apply these steps to it.  The first step is to invert the bits.  So 011101 becomes 100010.  Next we add 1. So 100010 becomes 100011. And thats it!  Just make any 0 a 1 and any 1 a zero then add one.