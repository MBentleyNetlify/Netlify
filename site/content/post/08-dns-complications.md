+++
categories = []
date = "2017-05-12T01:48:00-04:00"
tags = []
author = "Marvin Bentley II"
slug = "dns-complications"
title = "Two Major DNS Complications"

+++


Speaking as someone who has dealt with enough quizzical looks when I bring up the subject of DNS records with colleagues, there are a few common issues one could run into.

First is the fact that DNS is NOT instant. It can take a while for changes to propagate across the web. This can lead to a user making a change, seeing it NOT work, and then thinking THEY did something wrong. Which can sometimes lead to them then UNDOING the change in the first place, and setting them back even further.

I have also seen users run into trouble trying to assign a non-IP address to an A record (or similar). New users are often given little indication of what exactly is needed for each setting (especially if they have no formal training in the subject), which can make choosing the correct record to set (and sometimes what to set it to!) a scary thought. Even worse when coupled with what I mentioned above about propagation times.
