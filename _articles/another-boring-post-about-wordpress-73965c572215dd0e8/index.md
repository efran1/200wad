---
title: "Another boring post about Wordpress"
created_at: 2019-02-04T01:17:09.000Z
published_at: 2019-02-04T02:08:08.000Z
---
Yesterday I wrote [about Wordpress](https://200wordsaday.com/words/boring-post-about-wordpress-stuff-72315c55d67c23db4) .. surprise surprise today it's gonna be about Wordpress as well.

I am playing with local copies of the Wordpress site. After a big fight, I could make it. Today I tried the other way around. Replace my live site with the local copy.  I tried it with my old e-commerce site (mentioned in my fail story [here](https://200wordsaday.com/words/fail-story-e-commerce-project-part-1-56295c4acb69ec1c7), [here](https://200wordsaday.com/words/fail-story-e-commerce-project-part-2-56515c4b0be46a6bf) and [here](https://200wordsaday.com/words/fail-story-e-commerce-project-part-3-56535c4b0cd0a1e90)) because there is nothing to lose. 

I was prepared quite well. In the beginning, I change the config file, prepared the script for database links change, log to my hosting provider, log to hosting phpMyAdmin, Total commander opened. Simply ready for the action nothing could surprise me.

..... buuut as you can guess It didn't go smoothly haha. First pain in the ass is just deleting and uploading files with the Total Comanned. My hosting provider doesn't use cPanel so everything just took so much time (my files were just 200MB I cannot imagine if it would be more) and the worst is I had to do it twice. 

So delete the old files, drop the tables in the database and upload a new database (with new links) I could get there after a while. 

But the problem was with the uploading, I don't count how long it takes cuz it was just crazy long ... but after the upload, the site wasn't working. I googled the problem and actually, I couldn't find the solution. The same problem appeared but there were no right answers.

Fortunately, I didn't give up and after a while, I could find what happened. Long story short the problem was with the Total Commander. If you use for FTP the Total Commander there always pop up a small window before the start, with a small checkbox (really small). If you want to lowercase the files names. Sure I didn't want that haha cuz the location path differs so I deleted the files again and upload this time with unchecked checkbox aaaaannd. Hey hey hey the site is live again. Another small win in this cruel Wordpress world haha.

\------------

Next time about my life again haha.

\------------

Stay with me. Efran.
