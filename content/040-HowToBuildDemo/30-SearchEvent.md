---
title: "How to send Predictive Engagement 'Search Event'"
chapter: true
weight: 30
---


### How to send Predictive Engagement 'Search Event'
To capture a Search Event, we need to send a 'pageview' event with the configured search term. In the case of PureCloudNow (PCN), we need to send a pageview with URL = ?searchTerm=<the searched expression>

- Choose an element, possibly the 'Search' button of the website
- Right-click on this element
- In the contextual menu, click on 'Create function'
- Select 'Page View'
- Fill URL with ?searchTerm=<the searched expression>, and the title to the same value (or anything else)
- 'Save', then 'Close'


{{< youtube id="iC4rCgFWn8w" title="Demo Extension Dev Mode 3 Search Event" >}}

