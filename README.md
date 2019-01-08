# week6_assignement
# Project 8 - Pentesting Live Targets

Time spent: **X** hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:
1. [X] Username Enumeration:  GREEN 

  When user login error message - Bold 
  Non-user login Error message - Not Bold 


1. [X] Insecure Direct Object Reference (IDOR): RED 
  Blue and Gree are not reveling sales persons after id=9 , but 10 and 11 are available in RED 

1. [X] SQL Injection (SQLi) : BLUE 
  "id=%27%20OR%20SLEEP(5)=0--%27"

1. [X] Cross-Site Scripting (XSS) : GREEN

  <script>alert('Sushma found the blind xss');</script>

1. [X] Cross-Site Request Forgery (CSRF): RED

1. [X] Session Hijacking/Fixation: BLUE


