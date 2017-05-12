+++
categories = []
date = "2017-05-12T01:48:48-04:00"
tags = []
author = "Marvin Bentley II"
slug = "so-your-site-just-will-not-build"
title = "So your site won't build?"

+++


Good day, and thanks for reaching out to us! I know I've run into a few cases in the past where my site wouldn't build for me. I have some questions for you so that I can get a better handle on your issue, but first let me give you some ammo to try while you're getting back to me (it might even take care of it for you!). Firstly, have you checked your deployment logs? I know from personal experience that I tend to forget to mate my double quotes sometimes, and this often throws some sort of error that I can find by searching my log for "escape character". Once there, I can usually track it down from the line and column numbers it gives. If it's not that, it may be something else that shows up pretty clearly in there (search for "err" codes in your log). If the build failed on our servers, the log can be found in your deployments section (https://app.netlify.com/sites/your-site-name-here/deploys).

If that doesn't take care of it for you, could you kindly get me some more information so that we can troubleshoot this further? Is the build failing locally, or on our end? If on our end, could I trouble you for your user name and site name so that I can dig in and try to help tease apart your logs? If it's failing locally, could you kindly indicate what you're using for your build, and (if possible) send me the log it's generating? Please let me know if I can help with any of the above, and thanks again for reaching out to Netlify!
