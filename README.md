aretherefuckinghotdogsatkingscrosstoday
==========
hotdogs lets you know (in no uncertain terms) whether there are hot-dogs at [King's Cross Eat Street](http://www.eat.st/) today.
	
	
How it works
------------
It's a Python script that simply grabs the [Eat Street listings page](http://www.eat.st/kings-cross/) using urllib2, uses BeautifulSoup to scrape the relevant data, and spits back the friendly notification.

It's a modified version of [my eat street noms script](https://github.com/dotcode/eat-street).
	
	
How does it look
----------------
Like this:

![the output of hotdogs](https://github.com/downloads/dotcode/aretherefuckinghotdogsatkingscrosstoday/hotdogs.png)
	
Simple, huh?

Requirements
------------
Python, and it's reliant upon [BeautifulSoup](http://www.crummy.com/software/BeautifulSoup/) to parse the HTML … if you see the following error:

	ImportError: No module named BeautifulSoup

… then try installing BeautifulSoup:

	$ easy_install BeautifulSoup

(That's obviously the thing to do for the other modules as well, should they be missing)

Should you wish to display the information on your desktop, like me, then (on OS X) you'll be wanting to grab the fantastic [GeekTool](http://projects.tynsoe.org/en/geektool/). Grab it even if you couldn't care less about Eat Street. GeekTool is *brilliant*!
	
	
Installation
------------
	$ mkdir -p ~/bin
	$ curl -skL https://github.com/dotcode/aretherefuckinghotdogsatkingscrosstoday/raw/master/hotdogs >~/bin/hotdogs
	$ chmod +x ~/bin/hotdogs
	
Make sure `~/bin` is in your `$PATH` - or put the `hotdogs` script somewhere else on your `$PATH`.
	
	
Usage
-----
	$ hotdogs
	
I trigger the command using [GeekTool](http://projects.tynsoe.org/en/geektool/) so that I have the info displaying on my desktop. It's nice like that.
	
	
Author
------
Jude Robinson
-- dotcode at gmail dot com
-- @dotcode