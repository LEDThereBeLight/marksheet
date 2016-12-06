---
layout: post
title: "Cookies"
subtitle: "How to <strong>ask</strong> a computer for something"
section: elm
---

### Functions

One of the most common types of words we use in coding is called a **function**.

We use functions to ask the computer to *give us something*.

Imagine your oven can talk. You want some cookies, so you say to it, "Bake."

But your oven has a few questions for you before it knows exactly what you want. It asks you, "Bake what? For how long? At what temperature?" We have to answer all its questions before it can do its job.

<!-- //- The oven can't do its job until all its questions are answered, but you don't have to answer all the questions at once. You can answer some, and the oven will remember what you told it. It's like saving your settings.
//-
//- Maybe you always bake for 10 minutes at 350 degrees. So you change the settings on your oven to always bake at that temperature for that amount of time. Now you can bake different things without mentioning the temperature or time again. You bake cookies today, and cake tomorrow - the oven already knows how long and what temperature to bake at.
//-
//- If you need to, you can always reset the settings and start over with a new "bake" request. But the oven will only *run* when it has all its questions answered - in this case, it has a temperature, time, and something raw to bake. -->

Functions work the same way. We ask the computer to give us something, and we answer the questions it needs to know to get what we want.

### I/O

We call the information that the function needs to run the **inputs** to the function, and what it gives us back is the **output**.

So how do we use a function? It's easy. All we have to do is get its attention. And we get a function's attention the same way we get our friend's attention: by calling its name.

<!-- We can answer its questions all at once, and it will run, or we can answer some of them now and keep the function around to run later. -->

Remember the code we just wrote? Well, here it is again in case you forgot.

{% highlight haskell %}
import Html

main = Html.text "Sucking at something is the first step towards being sorta good at something."
{% endhighlight %}

`Html.text` is a function that takes one input: a string of text to show on the screen. It gives us back code for a webpage, which the Elm language uses to display on the page.

What's important to know is that *functions give us something*, and *we call a function by saying its name*.