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

Vulnerability #1: Username Enumeration
If we the user name is jmunroe99 and login failed, the text will display  bolded, otherwise, it will display regularlly

<img src='https://github.com/Hanyuatwork/Cyber_week_8/blob/master/week8_Q1.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

Vulnerability #2: Cross-Site Scripting (XSS)
we can input some Javascript in between a pair of <script> in contact us, and the XSS will be executed. 
  
<img src='https://github.com/Hanyuatwork/Cyber_week_8/blob/master/week8_Q5.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

## Red

Vulnerability #1: Insecure Direct Object Reference (IDOR)
in the salesperson page, we see that id 11 is what we want to hacked, and then from the public/salesperson.php?id=??, change id to 11, we will be able to see the infomation without log in.

<img src='https://github.com/Hanyuatwork/Cyber_week_8/blob/master/week8_Q2.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

Vulnerability #2: Cross-Site Request Forgery (CSRF)

we can link to a page, or bottom, that when we click that salesperson's info will be changed.

<img src='https://github.com/Hanyuatwork/Cyber_week_8/blob/master/week8_Q6.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

## Notes

Describe any challenges encountered while doing the work
