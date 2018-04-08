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

Vulnerability #1: Session Hijacking  
Using two different browsers to hijack another person's session
![sessionhijacking](https://user-images.githubusercontent.com/15334096/38468589-8bc0654a-3b16-11e8-8716-9ff4d41a1928.gif)

Vulnerability #2: CSRF Token
![csrf](https://user-images.githubusercontent.com/15334096/38469459-28cfa5e2-3b23-11e8-9fe6-ee43585cc690.gif)


## Green

Vulnerability #1: Username Enumeration  
Correct username, the alert is bold  
Incorrect username, the alert isn't bold
![usernameenumeration](https://user-images.githubusercontent.com/15334096/38468684-a4fbf618-3b17-11e8-8b07-280d74c2df8c.gif)


Vulnerability #2: Stored XSS  
Submit feedback with alert in name field. The input is not sanitized.
![xss](https://user-images.githubusercontent.com/15334096/38468886-4d4f0114-3b1a-11e8-8378-d6b0f11a4761.gif)



## Red

Vulnerability #1: Insecure Direct Object Reference  
Changing the id number is allowed which granted me access to a user that wasn't supposed to be public yet.
![insecure direct object reference](https://user-images.githubusercontent.com/15334096/38468930-e94adc00-3b1a-11e8-86d2-5b2d0ba00063.gif)


Vulnerability #2: ____



## Notes

Describe any challenges encountered while doing the work
