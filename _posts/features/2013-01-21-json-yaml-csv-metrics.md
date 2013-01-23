---
layout: post
title: 'New Feature: Metric Data available in Json/Yaml/CSV'
who: delano
bio: https://twitter.com/solutious
---

You can now find raw metrics data for the past hour, past 4 hours, and past 12 hours available for your sites under that "Data" tab.

![Site settings](/images/assets/2013/stella-metrics-data1.png)

### Format example (json)

{% highlight json %}
{
  "at":"2013-01-23 19:03:21 UTC",
  "redirect_count":1,
  "asset_count":18,
  "error_count":1,
  "first_request_fb":215,
  "first_request_rt":216,
  "first_request_size":81935,
  "initial_offset":0,
  "on_content_ready":2692,
  "on_load":3804,
  "duration":3803,
  "total_size":362862
}
{% endhighlight %}

### Format example (yaml)
{% highlight yaml %}
---
at: '2013-01-23 19:03:21 UTC'
redirect_count: 1
asset_count: 18
error_count: 1
first_request_fb: 215
first_request_rt: 216
first_request_size: 81935
initial_offset: 0
on_content_ready: 2692
on_load: 3804
duration: 3803
total_size: 362862
{% endhighlight %}

### Format example (csv)

<div class="highlight">
<pre>
  <code class="csv">
    at,redirect_count,asset_count,error_count,first_request_fb,first_request_rt, \
    first_request_size,initial_offset,on_content_ready,on_load,duration,total_size
    2013-01-23 19:11:35 UTC,1,24,0,1199,1208,9590,1203,2732,3854,3837,388314
    2013-01-23 19:13:25 UTC,1,18,1,146,146,81935,0,2364,3496,3480,339289
    2013-01-23 19:16:33 UTC,1,24,0,1833,1843,9590,1836,3656,4772,4755,428544
  </code>
</pre>
</div>
<br/>

[Get in touch](https://www.blamestella.com/#feedback) if you have any questions or problems.
