---
layout: default
title: "Dataset Selection Matters"
date: 2025-04-03
---

# Why Dataset Selection Matters: A Non-Technical Introduction

Your time is valuable. When deciding which Netflix show to watch next, you want it to be worth your while. Maybe you're looking for something fresh and exciting, or perhaps you prefer more of what you already know you like.

We all have this intuitive ability to predict if a new show will be worthwhile. We consider the genre, aesthetic, actors, trailer tone, production quality, and sometimes even the creators behind the scenes. And of course, we don't silo these signals, we combine them intelligently. A new actor in a genre that thrives on worldbuilding? The risk seems manageable. A massive budget production? Perhaps they've polished away all the interesting edges to maximize mass appeal. These evaluations happen almost automatically, and they save us countless hours of watching disappointing content.

This intuitive evaluation process is essentially what "taste" is, the ability to know what we want and to reliably predict if something new will satisfy those preferences by pulling in all available streams of information available to us.

Now while most ML training still brute forces through all available data, what if we could teach models to be as selective and so as time-efficient as we are with our netflix choices? Help them develop this same kind of "taste”? Why not ensure that each evaluation sample provides maximum information about model performance? 

Just as there are signals that help predict our enjoyment of media, there are rich signals that indicate how informative a data sample will be. If samples 3, 6, and 13 have consistently shown similar performance in your past N evaluations, would you really be on the edge of your seat waiting for sample 13's results when you already have data from samples 3 and 6? Probably not. You'd have a pretty good idea how it would turn out.

There are of course, various questions regarding just how we might go about incorporating all the pre-existing data we have to inform our understanding of which samples tell us what, how much of such information we need, how well this would work in practice, and indeed, if this will actually save us a lot of time. These questions will be answered in the next post, soon™.

