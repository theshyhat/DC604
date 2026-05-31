# Web App Security 101 with Just a Web Browser
## Pre-Start Links
### CyLab Signup Page
If you don't have an account at CyLab, you can create an account [here](https://learn.cylabacademy.org/register)
### Firefox Web Browser Download Page
If you don't have the Firefox web browser on your device, download it [here](https://www.firefox.com/en-US/download/all/desktop-release/)

## Part 1: Accessing HTTP source
Pico [Inspect HTML](https://learn.cylabacademy.org/library/275)

Pico [Unminify](https://learn.cylabacademy.org/library/426)

Pico [Includes](https://learn.cylabacademy.org/library/274)
## Part 2: Client-Side Secrets
Pico [Don't Use Client Side](https://learn.cylabacademy.org/library/66)

Pico [Local Authority](https://learn.cylabacademy.org/library/278)
## Part 3: Robots.txt and Data Obfuscation
[Deciphering Base64](https://cyberchef.io/#recipe=From_Base64('A-Za-z0-9%2B/%3D',true))

Sample Strings to Decipher

String 1

`dGhpcyBjb3VsZCBiZSBhIHN1cGVyIHNlY3JldCBwYXNzd29yZA==`

String 2

`aWYgeW91IGRlY2lwaGVyZWQgdGhpcyBzdHJpbmcsIHN0YW5kIHVwIGFuZCBsaWZ0IHVwIHlvdXIg
YXJtcywgdGhlbiBzaXQgZG93biBhZ2Fpbg==`

[Deciphering ROT13](https://cyberchef.io/#recipe=ROT13(true,true,false,13))
Sample Strings to Decipher

String 1

`Va EBG13, ahzoref naq chapghngvba ner abg punatrq.`

String 2

`Vs lbh frr n zrffntr jvgu n ohapu bs fcnprf, vg'f cebonoyl abg Onfr64 rapbqvat.`

Pico [Where Are The Robots?](https://learn.cylabacademy.org/library/4)

Pico [Roboto Sans](https://learn.cylabacademy.org/library/291)
## Part 4: Cookies
### How to Access Cookies in Firefox Browser
1) Click on the menu (three line) button at the top-right of the window
2) Click on `More Tools`
3) Click on `Web Developer Tools`
4) Click on the `Storage` tab at the top of the new window that appears
5) Click on the `Cookies` tab on the side-menu

Pico [Power Cookie](https://learn.cylabacademy.org/library/288)

Pico [Logon](https://learn.cylabacademy.org/library/46)

Pico [Cookie Monster Secret Recipe](https://learn.cylabacademy.org/library/469)
## Part 5: HTTP Headers and HTTP Header Injection 
### How To Send Modified Requests to Websites in Firefox
1) Click on the menu (three line) button at the top-right of the window
2) Click on `More Tools`
3) Click on `Web Developer Tools`
4) Click on the `Network` tab at the top of the new window that appears
5) Click on the `Reload` button on the page
6) In the list that appears, click on the web request you want to modify and resend (usually the top one)
7) Right-click the request and select `Edit and Resend`
8) In the `New Request` tab that appears, scroll down and click the value of any header you want to modify, then type in the value
9) If you want to create a new header: click on the `name` header at the bottom of the list, the type in the name of the header you want to create, then click on the `value` box and type in the value
10) Once you've modified the headers to your liking, click on the `Send` button at below all of the headers
11) A new window should appear with a the response from the webpage on the right-side of the Web Developer Tools window
### Example Website
[Example Website](https://example.com)
### Challenges
Pico [Picobrowser](https://learn.cylabacademy.org/library/9)

Pico [Crack the Gate 1](https://learn.cylabacademy.org/library/520)
## Part 6: SQL Injection Basics - Login Auth Bypass
### Example Websites to Try To Break Into
[OWASP Juice Shop](https://juice-shop.herokuapp.com/#/login)

Pico [More SQLi](https://learn.cylabacademy.org/library/358)

### Challenges
Pico [Irish Name Repo 1](https://learn.cylabacademy.org/library/80)

Pico [SQLiLite](https://learn.cylabacademy.org/library/304)
## Part 7: Capstone Challenges
Pico [Cookies](https://learn.cylabacademy.org/library/173)

Pico [Scavenger Hunt](https://learn.cylabacademy.org/library/161)

## Education Links For Web Security
[Web App Hacking Education Resources](https://github.com/theshyhat/hackerfrogs/blob/main/education_resources/web_app_hacking.md)

## Other Links
[My Twitch livestreaming channel](https://www.twitch.tv/theshyhat)

[My YouTube channel](https://www.youtube.com/@theshyhat)

[The slides for this presentation](https://github.com/theshyhat/DC604/blob/main/web101/bsides2026_web_app_101_04.pdf)
