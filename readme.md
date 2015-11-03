
Keynote Tweet is a simple AppleScript utility that allows you to send tweets from your Keynote presentations.

It was started by Ideo Labs (?) and hosted here: http://code.google.com/p/keynotetweet/
The Twitter OAuthpocalypse came, broke its posting method, and it wasn't updated.

Splatdot.com updated to use a different posting technique. http://splatdot.com/the-oauthpocalypse-and-keynote-tweet/

Toby Harris (tobyz.net) modified to be able to handle multiple tweets per slide and hosted on github. So now you can tweet the slide's text and the asides, links etc. to go with it.

Andrew Steinman used the updated code from Alan Levine and Thomas Brady (Located here: http://cogdogblog.com/2013/09/21/geeking-the-keynote-tweet-app-again-updated-instructions/) with some changes to make Keynote Tweet work in Yosemite with Keynote 6.

**Update (Nov 2015):** Connor Goddard added the full path of `twurl` to become `usr/bin/local/twurl` to fix issues where `do shell script` fails to find the full `$PATH`. 

##Installation

In order for the script to work, you'll need to install and configure twurl. You can find the twurl download and documentation here:

    http://github.com/marcel/twurl

To run the script, simply double-click the ‘Keynote Tweet’ icon. To edit it, open the same file in AppleScript Editor. Note that you cannot run this or any 'Stay-Open' script from the editor, but must run it as an application instead.

