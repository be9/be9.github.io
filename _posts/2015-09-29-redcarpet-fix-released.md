---
layout: post
title:  "Вышел fix для Redcarpet"
date:   2015-09-29 00:00:00
---
Наконец-то вышла версия [Redcarpet 3.3.3](https://rubygems.org/gems/redcarpet/versions/3.3.3),
в которую включён [мой фикс]({% post_url 2015-09-12-memory-leak %}).
Если вы используете Redcarpet, поставьте в Gemfile:

{% highlight ruby %}
gem 'redcarpet', '~> 3.3.3'
{% endhighlight %}
…и забудьте об утечках!
