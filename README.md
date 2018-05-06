# DirectAdmin SpamAssassin - Block emails that are send from specific TLDs
Comprehensive list of TLDs mostly used for spam. These are almost never valid emails so why not block them inmediately before SpamAssassin? Do you have a suggestion for another TLD? Open a new issue!

E-mails are rejected with the following error message;

> 554 denied. 5.7.1 Domain Blocked due to SPAM

## Usage

### Method 1 - Globally (preferred)
- ```nano /etc/virtual/blacklist_domains```
- Copy & paste the list below, **change it based on your situation**
- Restart exim
- Done!

### Method 2 - For a specific user
- Log in as a DirectAdmin user
- Go to SpamAssassin Setup
- Place the list in the "Email Blacklist" textfield
- Done!

## Spam TLDs:

```
*.accountant
*.ar
*.bg
*.bid
*.biz
*.biz.ua
*.br
*.camera
*.cc
*.cf
*.click
*.club
*.co
*.co.ua
*.co.in
*.co.mz
*.co.nz
*.com.au
*.com.tw
*.computer
*.cricket
*.date
*.diet
*.download
*.email
*.es
*.faith
*.ga
*.gdn
*.global
*.guru
*.gq
*.help
*.in
*.info
*.kz
*.link
*.lol
*.loan
*.media
*.men
*.news
*.ninja
*.nyc
*.party
*.photography
*.pt
*.pw
*.racing
*.reise
*.review
*.rocks
*.ru
*.science
*.site
*.solutions
*.space
*.stream
*.tech
*.today
*.top
*.tr
*.trade
*.uno
*.us
*.vn
*.webcam
*.website
*.win
*.work
*.xyz
```

## References
https://www.spamhaus.org/statistics/tlds/
