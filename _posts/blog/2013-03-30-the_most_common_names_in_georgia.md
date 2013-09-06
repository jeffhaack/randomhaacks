---
layout: blog
category: blog
permalink: /blog/the_most_common_names_in_georgia
title: The Most Common Names in Georgia
thumbnail: /assets/thumbs/names_georgia_blog_thumb.png
---

{{ page.title }}
================
<span class="postdate">30 March 2013</span>

Some time back I came across a rather interesting <a href="http://spatialanalysis.co.uk/2011/01/whats-in-a-surname/" target="blank">surname map of the United States</a>. The designer determined the most common names in every state, and then displayed them on the map, a name's size reflecting how common it is, and its color reflecting the ethnic origins of the surname itself.

<a href="http://spatialanalysis.co.uk/2011/01/whats-in-a-surname/" target="blank"><img src="/assets/images/georgia_name_map/surnames_usa.jpg" width="500" alt="USA Surname Map" /></a>

Having a particular affinity for the country of Georgia (aka <span class="smaller">საქართველო</span>), I thought it would be interesting and informative to make a similarly styled map of the region, which is a wild ethnic hodgepodge resulting from the enormously complex history of the Caucasus.

At first I thought getting the data might be a challenge, but it was actually quite simple. The Georgian Central Election Commission has a list of all eligible voters in the country, including their names and surnames and the district in which they are registered. This means my dataset excludes anybody under the age of 18.

Last October was the big parliamentary election (which led to a peaceful exchange of power), and some friends at <a href="http://jumpstart.ge" target="blank">JumpStart Georgia</a> were mapping the results on election day, so they had already pre-processed a bit of the data. Long-story short, a few ruby scripts left me with a nice array of interesting data &#8722; the top surnames for each of the sixty-odd districts in Georgia.

After some more scripting, geo-nerd-ery and design my map was starting to take shape. As it unfolded I learned some interesting things &#8722; for example, that 6.4% of Georgian men are named Giorgi! This wasn't entirely surprising, as shouting "Gio!" in any populated place will surely elicit a great many responses, but having a quantifiable number is pretty cool.

<center>
<a href="{{ site.baseurl }}/projects/the-most-common-names-in-georgia"><img src="/assets/images/georgia_name_map/Georgia_Name_Map_small.png" width="500" alt="The Most Common Names in Georgia" />
Click to see more detail</a></center>

It is also interesting that the great majority of <i>idzes</i> and <i>adzes</i> are from the western part of the country, while the <i>shvilis</i> tend to hail from the east. I'm sure any local could have explained that beforehand, but it never occurred to me that the names were region-specific.

While designing the map I started to realize that the suffixes of the surnames are directly linked to the ethnicity of the people &#8722; again, a thought which hadn't really occurred to me when I started. Sure there were the Georgians &#8722; <i>idzes</i>, <i>adzes</i>, and <i>shvilis</i>. Then there are the <i>ias</i> and <i>avas</i> from Samegrelo, the <i>ianis</i> of Svaneti, the Armenian <i>ians</i>, and the Azeri <i>evis</i> and <i>ovis</i>, who must have Russified their names during Soviet times.

It's a beautiful hodgepodge of ethnicities, and it helps to remind that Georgia is not just for Georgians &#8722; it's a melting pot of peoples and cultures now as it has been for thousands of years.









