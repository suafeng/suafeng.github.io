---
layout: post
title: "Generator"
description: ""
category:
tags: [Life|Noes]
---
{% include JB/setup %}


### Generator in Python

{% highlight python %}
position = [(i,j) for i in range(5) for j in range(4)]
{% endhighlight %}

Type of position is list.

{% highlight python %}
position = ((i,j) for i in range(5) for j in range(4))
{% endhighlight %}

Type of position is generator.


