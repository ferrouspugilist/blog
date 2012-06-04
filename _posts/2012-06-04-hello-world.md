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

<pre>
Console.WriteLine("Testing2");
</pre>

<br/>

{% highlight python %}
    song_info = []
    for song in songs:
        song_info.append(song.name)                                                                                                                                   
{% endhighlight %}

{% highlight ruby %}
def foo
  puts 'foo'
end
{% endhighlight %}

{% highlight csharp %}

public class TestClass {
  public static void Main(string[] args) 
  {
	var i = 50;
  }
}


{% endhighlight %}


{% highlight javascript %}

function() {  

   ready: function(element, options) { alert('Test'); }

}();


{% endhighlight %}

<table>
<tr>
<td>Col1</td>
<td>Col2</td>
<td>Col3</td>
</tr>
</table>


| Left align | Right align | Center align |
|:-----------|------------:|:------------:|
| This       |        This |     This     |
| column     |      column |    column    |
| will       |        will |     will     |
| be         |          be |      be      |
| left       |       right |    center    |
| aligned    |     aligned |   aligned    |







