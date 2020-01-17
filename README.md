# niemenglass.com

website provider http://www.mainstreetwebservices.com/ went out of business July of 2015.

History

![](/current/images/2004-06-16.png)
![](/current/images/2011-09-07.png)
![](/current/images/2013-06-05.png)
![](/current/images/2014-04-29.png)
![](/current/images/2014-06-07.png)

So current website is almost at least 6 years old . 2014-04-28T13:45:35+00:00 is the time the website was last modified. Just around that time mobile users have surpassed desktop users, and that trend has been going up ever since.

Running audit on the website Lighthouse 5.5.0 comes with better than mediocre results.

Key technical takeaways from audit: Could optimise image size & Minify CSS, reducing load times ~40%. - Total size was 3,345 KB

Accesibility could be improved by reducing the background color (Background and foreground colors do not have a sufficient contrast ratio.)

```
<meta name="viewport" content="width=device-width, initial-scale=1, minimum-scale=1, maximum-scale=1, user-scalable=0">
```

[user-scalable="no"] is used in the <meta name="viewport"> element or the [maximum-scale] attribute is less than 5.
Disabling zooming is problematic for users with low vision who rely on screen magnification to properly see the contents of a web page. Learn more.

Does not use https.

reobots.txt is not valid

---

Audit To-Do list

- [x] add robots.txt - it actually exists. so modify up to 2020 SEO standarts.
- [] use https
- [] fix meta tag
- [] minify css
- [] optimize images

Cool inspiration to have glass story - http://species-in-pieces.com/#

to add google search console <meta name="google-site-verification" content="RRSaRm97sHnKCK5UPRRp6CAI7yna8ObLQmnoHQLC_bI" /> add this to index.
