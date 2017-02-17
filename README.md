# Networking Coding Challenge
### Friday, Feb. 17th

**Context:** This coding challenge is a self-assessment for iOS networking architecture competency. This challenge is estimated to take 4-6 hours. See how far you can get during the 2 hours in class.

**If you're stuck:** Treat this as a mock interview take-home coding challenge. Try to see if you can figure out the answer with Google, StackOverflow, or other resources first. If you've tried multiple resources and are at a deadend, ask the instructor to point you in the right direction.

**Specs:** You're going to be building an app for discovering, saving, and creating Github gists. Your app should have the following:

**The only library you can use is Alamofire**

1. TabBarController with 3 tabs: public gists, your starred gists, your own gists
2. Gists cannot be anonymous and must have a user picture, username, and description
3. Loading user pictures should be cached and cancelled if appropriate
4. All three tabs should have pagination and request 100 gists per page
5. Ability to star / unstar gists
6. Create / delete gists
