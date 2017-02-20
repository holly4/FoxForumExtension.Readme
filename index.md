---
layout: default
---

The [Fox Forum Helper](https://github.com/holly4/FoxForumExtension) is a Chrome extension that adds customization to the Fox News Forums. 

### Changes for Version 2.2.2 Beta (2/19/2017)
Version 2.2.2 is critical fix for the last version which had a fatal problem. My bad for not catching it but it seems the Chrome Canary build I develop with is mor
permissive, (or has a bug), that allowed my code with a syntax error in it to run. So will also test on the release version of Chome in the future. 
Sorry for any confusion.

### Changes for Version 2.2.1 Beta (2/19/2017)
Version 2.2.1 is the last intended version of the beta extension for this cycle. Barring any notification of problems this version will be used
to update the main extension midweek:
- Comments are now processed for blank line removal, unbolding and lowercasing when a user edits them as well as on initial post.
- Improvement to the pop-up U/I so changes are only sent to the extension when actual changes are made to the filter state or users to filter. 
Before this change, any click to various elements on the pop-up U/I page notfied all extenson modules. (This resulted in no issues, 
as the modules would see their state had not change, but still was redundant)
- Trim spaces from usernames to be added to the filter list and detect and do not add duplicate users.
- Remove the `Enable logging` check box from the pop-up U/I. The logging feature can now only be changed in the options page.
- Update the count of filtered posts from the table content on change and not by keeping a counter. This was resulting in the `Total Filterred Posts` being incorrect
when users were removed from the filter list and had filtered posts.

### Changes for Version 2.2.0 Beta (1/30/2017)
Version 2.2.0 includes:
- A fix for when Fox News has incorectly marked more than one HTML node on the page as a comment stream as in the case of the Todd Starnes story today.
- Lowercasing of posts that are more than 20% UPPERCASE TEXT. **Note that at present this in opt-in** so you need to enable this in the options page. See this page
for further details on this feature: [STOP SCREAMING AT ME!](http://hollies.pw/2017/01/31/stop-screaming-at-me/)

### Changes for Version 2.1.1 Beta (1/27/2017)
Version 2.1.1 includes:
- Changes to detect the current user name. This is needed because of changes Fox made to the page on Thursday.
- Unbolding of posts that are more than 10% bold text. **Note that at present this in opt-in** so you need to enable this in the options page. See this page
for further details on this feature: [Stop using up all the bold pixels, dude!](http://hollies.pw/2017/01/27/stop-using-up-all-the-bold-pixels-dude/)
- Marking your own filtered posts is now enabled by default.
- A fix where things broke in the Clean Comments feature when logging was turned on

### Changes for Version 2.1.0 Beta
Version 2.1 adds an indication when your own posts have been filtered. **Note that at present this in opt-in** so you need to enable this in the options page. See this page
for further details on this feature: [What? You filtered my comment?](http://hollies.pw/2017/01/22/what-you-filtered-my-comment/)

### Changes for Version 2.0.0 Beta
Version 2.0 is a major change so the extension acts automatically on pages on Fox News with Comment Forums. So no more having to click the 
extension icon and press apply. It also adds new features and fixes some bugs in the prior version. 
This page describes the changes [Fox Forum Helper Version 2.0.0 in the store](http://hollies.pw/2017/01/18/fox-forum-helper-version-2-0-0-in-the-store)
