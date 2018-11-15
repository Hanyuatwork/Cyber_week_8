# Project 8 - Pentesting Live Targets

Time spent: **X** hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:
* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each version of the site has been given two of the six vulnerabilities. (In other words, all six of the exploits should be assignable to one of the sites.)

## Blue

Vulnerability #1: SQL Injection

if add the given ' OR SLEEP(5)=0--'  in the salesperson.php page,  then the page will proceeds to wait 5 seconds before returning.

<img src='https://github.com/Hanyuatwork/Cyber_week_8/blob/master/week8_Q3.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

Vulnerability #2: Session Hijacking/Fixation

once we login to the web, and use the hack-tool, and copy the session ID, then, if we use different brower, and change session ID to this one, then it will log-in without  username and password

<img src='https://github.com/Hanyuatwork/Cyber_week_8/blob/master/week8_Q4.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />


## Green

Vulnerability #1: __________________

Vulnerability #2: __________________


## Red

Vulnerability #1: __________________

Vulnerability #2: __________________


## Notes

Describe any challenges encountered while doing the work
