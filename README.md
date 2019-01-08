# week6_assignement
# Project 8 - Pentesting Live Targets

Time spent: **X** hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:
1. [X] Username Enumeration:  
          
          GREEN 

  When user login error message - Bold 
  Non-user login Error message - Not Bold 


1. [X] Insecure Direct Object Reference (IDOR): 
      
          RED 

  Blue and Gree are not reveling sales persons after id=9 , but 10 and 11 are available in RED 

1. [X] SQL Injection (SQLi) :
    
        BLUE 
        
Exploit is in slaesperson.php URl 

1. [X] Cross-Site Scripting (XSS) : 
      
        GREEN

  <script>alert('Sushma found the blind xss');</script>

1. [X] Cross-Site Request Forgery (CSRF):
      
        RED

1. [X] Session Hijacking/Fixation: 
      
        BLUE

## Blue

Vulnerability #1: SQL Injection (SQLi)

Vulnerability #2: Session Hijacking/Fixation


## Green

Vulnerability #1: Username Enumeration

Vulnerability #2: Cross-Site Scripting (XSS)


## Red

Vulnerability #1:Insecure Direct Object Reference (IDOR)

Vulnerability #2: Cross-Site Request Forgery (CSRF)
## License
    Copyright [2019] [sushma]
