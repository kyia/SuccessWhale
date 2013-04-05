SuccessWhale
============

SuccessWhale is a web-based Twitter, Facebook and LinkedIn client for the SuccessWhale API, written in JavaScript using Backbone.js. It’s a multi-column client that can merge and display feeds from several social networks however you like. It’s free to use by anyone, has no advertising, and source code is available right here on GitHub under the BSD licence.

Visit http://successwhale.com to try it out!

Features
--------

* You can add as many Twitter and Facebook accounts as you like, displaying data from each, and you can choose which to post to every time.
* SuccessWhale has a multi-column view, which can be scrolled through if you want more than will sensibly fit on your screen. Many columns are available for each Twitter and Facebook account you register, including ones that combine notifications from all your accounts.
* SuccessWhale is integrated with my Twitter pastebin, Twixt. Enter a reply longer than 140 characters into the box in SuccessWhale, and it will be shortened automatically using Twixt. SuccessWhale also displays the contents of Twixt posts inline, and expands short URLs.
* You can use SuccessWhale from places where twitter.com and facebook.com are blocked. To do so, you’ll have to log in from a computer that can see the sites first, then click “Accounts” in the top-right and create yourself a SuccessWhale account. You’ll then be able to log in using that password from any computer.
* You can maintain a "banned phrases" list, which will hide tweets containing certain phrases — great if you’ve got too many friends that spam their Foursquare check-ins to Twitter.

Screenshot
----------

[![Successwhale 2 Screenshot](http://onlydreaming.net/wp-content/uploads/2009/08/successwhale-2.0-screenshot-300x159.png)](http://onlydreaming.net/wp-content/uploads/2009/08/successwhale-2.0-screenshot.png)

Status
------

SuccessWhale is complete, released software.  Its latest stable version is 2.0.2, and a semi-stable 2.1 branch also exists. Work is underway on version 3, which will bring massive improvements.

http://successwhale.com runs v2.0.2.
http://test.successwhale.com runs v2.1.1.

It’s used by around 80 people — including myself — as their main Twitter and Facebook client, and a number of sites around the internet have used the source code to integrate SuccessWhale into their own sites. As far as I’m aware it has no bugs, but if you find any or would like to request any new features for the next version, you can contact me on Twitter (I'm [@tsuki_chama](http://www.twitter.com/tsuki_chama)) or via the Issues page on GitHub.

Libraries
---------

TBD

Thanks to...
------------

  * [@abraham](http://www.twitter.com/abraham) for writing [twitteroauth](http://github.com/abraham/twitteroauth), a PHP implementation of the Twitter OAuth API. SuccessWhale uses twitteroauth as its backend.
  * [@tikakino](http://www.twitter.com/tikakino) for the short URLs and Twixt expansion code, and for my introduction to jQuery.
  * [@aefaradien](http://www.twitter.com/aefaradien) for hosting successwhale.com in the early days, and for many bug reports.
  * [@pixify](http://www.twitter.com/pixify) for SuccessWhale version 2's [OSX-inspired button style](http://pixify.com/blog/use-os-x-lion-to-improve-your-ui/).
  * [@glyphish](http://www.twitter.com/pixify) for the [icons to match the above button style](http://glyphish.com/).
  * [Ibrahim Faour](http://stackoverflow.com/users/337227/ifaour), for modifying the Facebook API docs in response to [my question on StackOverflow](http://stackoverflow.com/questions/7122394/in-the-facebook-api-how-can-i-retrieve-the-source-object-from-a-notification-obj).
