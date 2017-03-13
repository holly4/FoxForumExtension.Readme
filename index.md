---
layout: default
---

Your Fox Forum Helper extension has been upgraded. The changes for this revision are listed below. 
For a list of changes in other versions see the Release Notes section of the [online help](http://hollies.pw/static/ffh/latest/help/index.html).

### Changes for Version 2.2.3 Beta (3/12/2017)
Version 2.2.3 fixes several small issues but also has changes internally to make future releases less risky. This involves using the JavaScript
linting tool [ESLint](http://eslint.org/) which catches potential errors in JavaScript code to hopefully avoid issues like in version
2.2.1, where the code worked in the cutting-edge version of Chrome but not in the release version. 
The [online help](http://hollies.pw/static/ffh/latest/help/index.html) is now complete. It will still be improved over time but as it is on line it can be reved at anytime without
changes to the extension. **Barring any negative feedback, this version will be used to, finally!, update the non-beta extension**.
- Use ESLint during development process and fixed all issues identified by it.
- Fixed error where lowercasing posts was also controlled by the unbolding checkbox.
- Allow the user to modify trigger levels where posts are unbolded or lowercased.
- Change the default option to remove the video when cleaning the page to inactive.
- Change the default option to remove bold and uppercase in posts to active.
- Remove more of the padding at top of screen of Fox forum page.
