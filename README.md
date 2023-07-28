# midnight-limo

With this repo you can easily set up your .eth.limo site with a breeze, a pfp and some links. Your online business card, built on your ENS (with fleek). 

Why with fleek? Cause it is way easier than to set up some scripts to refresh/renew the ipfs/ipns. You could also do it manually without a platform of course.

## Steps

1. Clone repo. 
``` 
git clone https://github.com/yougogirldoteth/midnight-limo.git 
```
2. Add 'my-pfp.png' and 'my-breeze.png' to folder.
3. Change html: title, icon / meta / description, h1, qoute, links. Then
```
git add .
git commit -m 'first commit'
```
4. Create new repo on Github. Push clone to your new Github repo: 
```
git remote set-url origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
```
```
git push -u origin main
```
5. Go to fleek.co and login (with wallet sign in or just with github acc).
6. 'Create new site' and connect to your repo. Deployed! -> https://dry-voice-3732.on.fleek.co/
7. Then go to 'Settings' -> 'Domain Management' -> 'ENS'. Pay a small gas fee ( 6-10$ ) to put the content hash in your ENS records.

   And there you go! You built a small (gud looking) business card website on your ENS domain.

## Thank you

This is a shameless copy pasta from https://jalil.eth.limo! As always ty Jalil.