---
layout: post
title: New Stuff Keeps Happening
---

So far documenting all the changes I make to my computer has gone well, by which I mean I have written it all down and it is in no way readable by anyone but me. I hope to have a copy of my mac dotfiles up on github soon, but I really do need to at least try to write some useable step by step documentation for the next time I have to set up a computer, because dotfiles is not quite enough. 

I like my job. I like writting functions to do basic math. I screw up all the time with silly things like not realizing that if your variables are really just pointers then you can not really use them in any sort of recursive function the way you would with other variables. Instead of saying y=x and then manipulating x based on y, I have to say set the value of y to the same value as x and now manipulate x. Otherwise y (and consquently x) is not really changing in each iteration of the loop.

Another silly mistake I have made is trying to build a nonexistent tool by trying to use that tool as if it already exists, which really feels a lot like the early days of learning to write proofs. The difference being that instead of trying to prove something is true by assuming it is true, I am now trying to build a hammer with a hammer but I do not have a hammer. Also, I spend hours wondering why my hammer does not work until I ask my boss for help and he miraculously does not tell me I am an idiot. 

Nonetheless, I am making progress. 

I am learning more about how to write tests. Some stuff is difficult like how do you test a function that is supposed to work on any number? You can not test all possible pairs of numbers; thats absurd. So far people have said test the "edge cases" which I think means guess what numbers would make it fail, but obviously the numbers I think might make it fail are the ones I have specifically written the function to deal with because I am not intentionally negligent. Anyway, I will just pick pairs that hit what I would consider a minimal set of representatives of all numbers like negative, positive, greater than one, less than one, zero, and any possible combinations of them. This definitely wont be enough but this test model inherently only tells us that the sets we have test work and all else is unproven. 

On an unrelated note, it is October and my hunt for a not terrible pumpkin flavored beer has begun. So far 0/1
