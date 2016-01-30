---
layout: page
title: How to create an event using Evento
navigation_title: Create Event
permalink: /create/
button: true

---

Adding an event to your site is easy. 

#Getting started
Create a new .md file or copy an existing post in the  `_posts` directory to get started. The post file name must be in this format:

{% highlight markdown%}
YYYY-MM-DD-title.md
#Example 2016-01-01-Back-At-Work-After-New-Year.md
{% endhighlight %}

#Config for posts

{% highlight markdown%}
---
#leave this alone
layout: post

#authors name
author: Dave Boyne

#Whats the title of your event.
title:  "Talk on ES6 JavaScript"

#Url to your cover photo for your event. [optional - default will be used if not given]
cover: "https://frontendmasters.com/assets/es6-logo.png"

#The date of the event. 
date:   2016-02-01 16:04:19 +0000

#Add your talk to any categories
categories: jekyll update

---
{% endhighlight %}

#Post content

After you have setup your config, all you need to do know is write your content using markdown.

#Example Post

{% highlight markdown%}
---
layout: post
title:  "Talk on ES6 JavaScript"

cover: "https://frontendmasters.com/assets/es6-logo.png"
date:   2016-02-01 16:00:19 +0000
categories: jekyll update
author: Dave Boyne
---

Hey guys! I'm going to be doing a talk on how to create new websites using Jekyll.
 
Talk will be about 30 minutes long. Be great if you could come along to make it!	

{% endhighlight %}

##Thats all folks
Thats all you need to do. Once the website is built again using `jekyll build` or `jekyll serve` your new event will be shown.