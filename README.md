# directadmin-spamassassin-block-tlds
List of TLDs mostly used for spam. These are almost never valid emails so why not block them inmediately?

## Usage

### Method 1 - For a specific user
- Log in as a DirectAdmin user
- Go to SpamAssassin Setup
- Place the list in the "Email Blacklist" textfield
- Done!

### Method 2 - Globally
- ```nano /etc/virtual/blacklist_domains```
- Copy & paste the list below 
- Done!

## TLDs:

```
*.ar
*.bg
*.bid
*.biz
*.br
*.camera
*.cc
*.click
*.club
*.co
*.co.mz
*.co.nz
*.com.au
*.com.tw
*.computer
*.cricket
*.date
*.email
*.es
*.faith
*.global
*.guru
*.help
*.in
*.info
*.kz
*.link
*.lol
*.loan
*.media
*.news
*.ninja
*.nyc
*.org
*.party
*.photography
*.pt
*.pw
*.racing
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
*.tr
*.uno
*.us
*.vn
*.website
*.win
*.work
*.xyz
```
