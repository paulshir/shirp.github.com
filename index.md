---
layout: page
title: "This is a work in progress"
published: true
---
{% include JB/setup %}

[github]: http://github.com/shirp/shirp.github.com
[home]: http://shirp.github.com

## Welcome ##

Welcome to my blog. This is a work in progress as I am trying to develop a theme for this blog. I plan to use it maybe to post updates but mainly just to have a little site about me with my cv and resume etc etc.

## Backend ##

I'm running this blog on github pages and using jekyll to run as static blog. I'll post more about this in the future.  
You can view my code [here][github]

## Theme ##

I don't know what I'm going for yet but sure we'll see

***
## Test Code ##
This next area is going to be areas to see how the theme works with different elements  
The first part will be a list
* Item 1:
* Item 2:
* Item 3:
 * Item 3a: Nested 1 deep
  * Item 3ai: Nested 2 deep

This *sentence* is looking at **different** formatting ***options***  
It is using __bold__, _italics_, and a ___combination of both___

This sentance `contains some inline code` and the following segment is going to be a code block.

    for (int i=0; i<10; i++){
       printf("%d\n", i);
    }

The next sentence is going to repeat the same code with syntax highlighting

{% highlight c %}
for (int i=0; i<10; i++){
  printf("%d\n", i);
}
{% endhighlight %}

Next I am going to place a link back to this website [page][home] to view what links look like.

>The final part for now is a block quote  
>Which is spread accross
>Multiple Lines

That's all Folks
