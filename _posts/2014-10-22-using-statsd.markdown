---
layout: post
title:  "Using StatsD to Monitor Service Performance"
date:   2014-10-22 12:19:17
categories: statsd latency graphite
---

On [code.hootsuite.com](http://code.hootsuite.com/using-statsd-to-monitor-service-performance/) you can find an article I've written about measuring a service latency with statsd.

<a href="http://code.hootsuite.com" target="_blank">
    <img src="https://dl.dropboxusercontent.com/s/lbveexxejgdk45o/Screenshot%202014-10-13%2011.41.06.png?dl=0" width="700px"/>
</a>

### What are the key takeaways when monitoring service performance?

- Measuring average response times is a bad way of assessing service performance
- Maximum response time data offers up much more useful information
- StatsD + Graphite is a match made in heaven (with some tweaking)
