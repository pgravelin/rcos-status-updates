## Last Week's Accomplishments

During thanksgiving break, I did some background research for the user 
authentication system and decided to use social_django. 

## This Week's Plan

This week, I implemented the authentication system to abstract OAuth
and allow us to sign into our website using Github. Currently, the
architecture allows us to restrict page views, e.g. we check the 
authentication status of the user and prompt a sign in via Git before
allowing the user to view the homepage. Going forward, I plan to 
integrate the progress made on the working branch to the improved
GUI in the master branch and encapsulate the OAuth implementation into
a separate app.  

## Anything Blocking?

Not much time this week to make more commits due to testing and homework.