.. title: Check Yo Sigs
.. slug: check-yo-sigs
.. date: 2017-04-25 09:55:57 UTC-05:00
.. tags: News 
.. category: News
.. link: 
.. description: Webroot Fucks the World
.. type: text

Received an `interesting report`_ from a colleague today. Apparently `WebRoot`_ released a `false positive signature`_ which totally borked Windows and legitimate applications in a substantial volume. I haven't used their software in a while as I've been on `Avast`_ for the last decade or so.

Malware scanning itself is something highly selective and rather difficult to perform, particularly due to the usually randomized nature of the malware itself. When I was working in security, I performed a significant number of application level cleanings and found that RegEx was usually the most beneficial, coupled with selective file searching based on ctime & OS reported file type (got a JPEG reported as an ASCII text file? May wanna take a look at it). The DHS `Grizzly Steppe report`_ also includes a sample signature of theirs on page 5. Worth a read if you haven't looked at it.

.. _interesting report: https://arstechnica.com/security/2017/04/av-provider-webroot-melts-down-as-update-nukes-hundreds-of-legit-files/
.. _WebRoot: https://www.webroot.com/
.. _false positive signature: https://community.webroot.com/t5/Announcements/W32-Trojan-Gen-False-Positive-Fix-April-24/td-p/290198
.. _Avast: https://www.avast.com/
.. _Grizzly Steppe report: https://www.us-cert.gov/sites/default/files/publications/JAR_16-20296A_GRIZZLY%20STEPPE-2016-1229.pdf
