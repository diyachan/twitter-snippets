# twitter-snippets
UserCSS snippets that I personally use. Snippets require [Stylus addon](https://add0n.com/stylus.html) to work (works on most browsers). Unfortunately very untested on mobile.

To make use of these, click the name for the one you want to use, and then click the "Raw" button on the top of the file
![image](https://github.com/diyachan/twitter-snippets/assets/7719971/667b390b-f48e-41ea-9e84-a958a39937a3)
And then an install window will show up. Click install and you're done!

Currently it only offers one thing:
## [Defer long tweets](defer-long-tweets.user.css)
![image](https://github.com/diyachan/twitter-snippets/assets/7719971/ddc9047e-476f-4e7b-bad7-b30132348014)

Are you really irritated with an entire essay on your timeline as a *single* tweet? This UserCSS snippet force it to be small and have extremely low opacity (10%) fading to full transparent.

It works by looking whether the tweet has a "see more" link inside, which unfortunately also affects non-Blue tweets that legitimately needs to expand; and it also affects QRTs.

In theory should be working with any language
