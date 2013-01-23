---
layout: post
title: 'New Feature: HTTP Authentication'
who: delano
bio: https://twitter.com/solutious
---

There was a lot to do at launch and some basic features hadn't been implemented yet. Supprt for HTTP authentication is one of those features.

## Run a checkup

As long as the target server returns a 401 status, along with the `WWW-Authenticate` header, you will be prompted with an orange button that reads "Authentication Required".

![Authentication Required](/images/assets/2013/stella-httpauth-step1.png "Authentication Required")


## Enter the credentials

Enter your HTTP auth username and password at the prompt and re-run the checkup.

![HTTP credentials](/images/assets/2013/stella-httpauth-step2.png)

Note: we store the password so that we can monitor pages that require HTTP authentication. Make sure you use passwords that either aren't sensitive (for a testing site for example) or ones that you don't use anywhere use (to be on the safe side).


## Re-run the checkup

Using that username and password combination, we can now run a successful checkup.

![Successful result](/images/assets/2013/stella-httpauth-step3.png)

[Get in touch](https://www.blamestella.com/#feedback) if you have any questions or problems.
