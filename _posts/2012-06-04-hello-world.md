---
layout: post
title: "Hello World"
tagline: ""
description: ""
category: 
tags: [first]
who: World
---
{% include JB/setup %}
Hello {{ page.who }}!

{% highlight ruby linenos %}
def foo
  puts 'foo'
end
{% endhighlight %}