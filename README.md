# webfont-testpages
Groupings of HTML pages for testing the look of web fonts in various desktop browsers and testing a font for its support for a given language and/or character set.

## The Basic Approach

While these test pages can and will be made available linked together as a comprehensive suite of pages_ - one requirement has always been that each page, unlinked and standing alone should be totally complete as a test page without any dependencies upon subsidiary files containing .js and/or .css files.
All necessary JavaScript and Style Sheets are replicated within each .htm file - redundantly - with the same text repeated over and over in each page like biological DNA is replicated in each and every cell of a living body.
Yes, this means more work updating a lot of files when there is a change. And that may seem wasteful and inelegant. But it pays off in that you can pick just the one test page you want and begin using it without any thinking about any other files.
Another simplification that makes it easier to integrate pages like these into a font designer's work flow is that they don't require a web server to run. They run as ordinary .html files on the local PC's file system. There is also an added privacy benefit to this in that many type designers may feel uncomfortable uploading their font for testing to a web site without any guarantees about what actually happens to the uploaded file after it's uploaded to the site.


## These Pages Can Be Used By Novices and Experts Alike

There is the advantage of accessibility to the approach outlined above: anybody anywhere is capable of downloading a single HTML page and clicking it open and dragging in the font they wish to test. The pages work using "file://" urls within the computer's ordinary file system and thus no web server is needed. Now, test pages that make use of PHP and scripting languages like Python can be great and they are perfectly suitable for power users and expert type professionals. These pages, on the other hand, aim for simplicity above all else. And they are, of course, perfectly useful to the power user and expert type professional, too. They are professional-level yet accessible to the novice.

Some other requirements that these pages meet are:

1) All sample "test" text in the HTML markup is written in Unicode characters. 
For example, the Thai Character NGO NGU would be included using either or both the decimal and/or hex designations as follows:

THAI CHARACTER NGO NGU

&amp;#3591; 
<!-- &#3591; -->
and/or

&amp;#x0E07;
<!-- &#x0E07; -->

The reason for this is the increasing ubiquitousness of Unicode - it seems pointless to use any legacy encoding scheme in this day and age. Plus, it makes for a more "bulletproof" test page: it makes for a page that can't easily be mangled by, for example, selecting an alternate encoding in the browser. It is, in programming terms, "defensive coding". 
(The only exception to this right now is for the basic Latin set. I simply haven't decided if it's wise or necessary to convert those characters to Unicode in the HTML. English has become the world's fallback "pivot" language and it might create more confusion to use Unicode points rather than the characters themselves. I will decide on this at some point.)


2) Acknowledgments:
These pages started out as my private way of testing web fonts. Now, in conjunction with work I'm doing with fonts coming out of the Google Web Fonts project under the aegis of Dave Crossland, they are being released here under an open-source license and  (Adding a license in this case just makes it clear that you can take what you want and build upon these pages as you please) But I haven't as yet determined which license. I will add a license.md soon. In the meantime, take, take, take, as you will.
I am busily working on new pages for Arabic and Hindic language sets plus other stuff which will appear soon.
I'm extremely grateful to Pablo Impallari and Vernon Adams for the test pages they've freely published. I have borrowed and will continue to borrow freely. My thanks.

Richard Fink - Feb 1, 2016

