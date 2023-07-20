# twitter-snippets
UserCSS snippets that I personally use. Snippets require [Stylus addon](https://add0n.com/stylus.html) to work. Unfortunately very untested on mobile.

Currently it only offers one thing:
## Defer long tweets
Are you really irritated for a literal essay on your timeline? This UserCSS snippet force it to be small and have extremely low opacity (10%) fading to full transparent.

![image](https://github.com/diyachan/twitter-snippets/assets/7719971/8d0acd8a-4b98-44ac-8015-7d95b7cbc4b1)

It works by looking whether the tweet has a "see more" link inside, which unfortunately also affects non-Blue tweets that legitimately needs to expand; and it also affects QRTs.

In theory should be working with any language
