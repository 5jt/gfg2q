---
title: Girlfriend’s Guide to q
description: A girlfriend’s guide to he q programming language, inspired by Saturday Night Live
author: Stephen Taylor
date: June 2020
---
# A girlfriend’s guide to the q programming language



[![Girlfriends Talk Show](img/girlfriends-talk-show.png)](https://www.youtube.com/watch?v=9nDa9pKhbA8 "Girlfriends Talk Show: Kyra's New Best Friend - SNL")

Today we have a late change to our topic. It’s not boyfriends today, but _the q programming language!_ OMG. That’s even hotter.

We start off in the command shell, and to use the q programming language we just type `q`, which is the name of the q programming language, so there is nothing else to remember. You don’t even need to press the Shift key, because Arthur Whitney was careful to not use it. (This is because of a hot secret about Arthur, which I may tell you later.) Awesome!

```bash
❯ q
KDB+ 4.0 2020.06.01 Copyright (C) 1993-2020 Kx Systems
m64/ 12()core 65536MB sjt mackenzie.local 127.0.0.1 EXPIRE 2021.05.27 …

q)
```

It even prints a little `q)` before it stops. I thought that was to remind me what language to use, but my BF told me it is txtng talk. It says it’s my cue, with a tiny smile. It’s my turn! Cute or what?

Now what to do? Well, if you have coded before, like Minecraft, you know you’re supposed to make stuff. Out of bricks or whatever. Well, q is very, very, very basic. So we make stuff out of atoms. 


## Atoms

Here are some atoms for you. 

```q
"a"
2002.07.05      / i have an atomic birthday!
42              / the favorite number in q, no one knows why
12:30           / lunch time!
`morgan         / obviously a word, but somehow called a symbol -- wtf?
+               / go large!
```

There are some other types of atom in q but these are all the non-nerdy types. You can use the nerdy types too if you have to.

Atoms are great but they fall on the floor and get lost. 
To make anything good we’re going to have to join them together into lists.


## Lists

Every girlfriend loves lists. If we didn’t have lists, how would we get anything done? Lists are awesome! 

Here are some lists for you.

```q
"you are my best friend ever"   / a list of characters
`morgan`kyra`tara               / some other characters, sorry -- symbols people, symbols
42 2.71828 -5 3.14159           / 42 and some other numbers not so good
11:00 12:30 18:00               / brunch, lunch, and cocktails
```

These are great lists but also slightly boring. In each list all the items are the same type. Mix it up, people! Life is more interesting! 

```q
(2019.08.03; 13:30; `arthur`stevan; `baobao)  / my nyc lunch date
(2020.01.14; 12:15; `morgan; `burgerking)     / my hoboken lunch date
```

So there we have it. You can make a list out of things – even other lists! – just by putting parens round them and separating them with semicolons. 
Lists and items. So cool. 

Still nothing happening, though. Just lists and atoms. There’s only so much you can build by typing it all out. Ask Jack Kerouac! 

Fortunately there are special lists for making things happen. They are called _parse trees_, which makes no sense to me, because they don’t look like trees, and surely _parse_ is a typo for something (_pause_? _purse_? _persian_?) but my BF says not, so parse trees is what it is. 

As my mom says: Put on your big-girl panties and deal with it. 


## Into the trees

A parse tree is a list of sh*t you want done. 

On my lunch date with Morgan I chose a meal deal for $4.99 and at the counter they asked me if I wanted to Go Large, which of course I shouldn’t, because Go Large means Get Large, but I somehow did, which means I had to pay an extra 99¢. Now imagine if a terrorist attack had taken down all the power in New Jersey! The clerk would not have been able to tell me how much to pay!

Here is where you can use q. Make a list of the go-large operator, the meal deal price, and the 99¢ for the extra fries – and just evaluate it!

```q
q)eval(+;4.99;.99)
5.98
```

So you see, a programming language can actually be useful in the real world.
I think we all learned something here. 

Now because of his hot little secret that I haven’t told you yet, Arthur made some shorter ways to do that. The go-large operator – which we might as well get nerdy and call Add – adds two things together. The nerds call them the operator’s _arguments_ and do not ask me why, because I don’t want one. In fact, from now I’m just going to tell you the nerdy names for things and not try to explain why they call them this. Really. Who knows why these people do what they do anyway? 

