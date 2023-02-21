.. title: New Project - CVESearch (cves)
.. slug: new-project-cvesearch-cves
.. date: 2018-04-01 13:02:34 UTC-05:00
.. tags: Updates,Application,Project,Security 
.. category: updates 
.. link: 
.. description: 
.. type: text

I've been taking time at work to start a new project, CVESearch or cves for short. I've cloned it over to my public GitHub and have been keeping the two in sync with each other. The end goal is an application that looks up CVEs in OS vendor notifications, namely Ubuntu's USN and Red Hat's RHSA boards. Once identified, it provides a link to the advisory so you know when it was patched for that OS and can go about your day. The current version I'm working on takes this scraper methodology and dumps the data into a database for persistence then facilitates lookups through the local cache first and only scrapes external sites if its needs to be populated still.

https://github.com/wiseeyesent/cves
