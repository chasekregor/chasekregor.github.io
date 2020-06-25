---
layout: page
title: cycling 
---
<h4>Posts Related To Cycling:</h4>

<ul>
{% for post in site.categories.cycling %}
    <li>{{ post.date | date: '%b %d, %Y' }} - <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>

<br />

In my free time I really enjoy cycling. I suggest you follow me on [strava](https://www.strava.com/athletes/3623618) and on [zwiftpower.com](https://zwiftpower.com/profile.php?z=2650)

<iframe height='160' width='300' frameborder='0' allowtransparency='true' scrolling='no' src='https://www.strava.com/athletes/3623618/activity-summary/02e43e83aaa3e8989fa8ed4d921c4db8396bfa42'></iframe>

