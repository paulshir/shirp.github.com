---
layout: post
title: "Code View Test"
category: 
tags: []
featured_image: /images/beach.jpg
published: true
---
{% include JB/setup %}

### Without Highlights
Some code will go in a box below here

    def foo
      puts 'foo'
    end



### With Highlights
Some code will go in here below
{% highlight ruby%}
def foo
  puts 'foo'
end
{% endhighlight %}

That is the end of this post
