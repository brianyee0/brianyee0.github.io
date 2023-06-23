---
id: 341
title: 'Tracing Jersey&#8217;s Matchers'
date: '2012-02-09T15:42:00-05:00'
author: admin
layout: post
guid: 'http://blog.brianyee.org/tracing-jerseys-matchers'
permalink: /2012/02/tracing-jerseys-matchers/
categories:
    - Uncategorized
---

Finally found the answer to what I looking for: How to figure out what the heck [Jersey](http://jersey.java.net/) was doing when matching resources. This answers it nicely:

*Jersey now supports the same feature implemented in 1.1.5-ea-SNAPSHOT. Adding the following servlet/filter initialization parameter enables tracing:*

> <div class="CodeRay"><div class="code">```
> <init-param>
> Â Â Â  <param-name>com.sun.jersey.config.feature.Trace</param-name>
> Â Â Â  <param-value>true</param-value>
> </init-param>
> ```
> 
> </div></div>

Easy Peasy: [http://blogs.oracle.com/sandoz/entry/tracing\_in\_jersey](http://blogs.oracle.com/sandoz/entry/tracing_in_jersey)

[Permalink](http://blog.brianyee.org/tracing-jerseys-matchers)

 | [Leave a comment »](http://blog.brianyee.org/tracing-jerseys-matchers#comment)

![](http://feeds.feedburner.com/~r/brianyee/LmTz/~4/xUfwoyfTMr8)