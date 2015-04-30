---
layout: article
title: Mailing Lists
date: April 29 2015
permalink: /mailing-lists/
modified:
excerpt:
image:
  feature:
  teaser:
  thumb:
ads: false  
share: false
---

Below is a listing of all the public mailing lists on the MUUG server. Click on a list name to get more information about the list, or to subscribe, unsubscribe, and change the preferences on your subscription.

<ul>
{% for mailinglist in site.data.mailinglists %}
	<li>
		<a href='{{mailinglist.infoLink}}'>{{ mailinglist.name }}</a> - <a href='{{mailinglist.archiveLink}}'>(archives)</a><br />
		{{mailinglist.description}}
	</li>
{% endfor %}
</ul>
