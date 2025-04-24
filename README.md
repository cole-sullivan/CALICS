# Cole's Arch Linux Installation & Configuration Scripts (CALICS)
on an Arch live USB, run
```
curl -LO CALICS.dev/CALICS1.sh
sh CALICS1.sh
```
after rebooting, as root, connect to the internet and then run
```
curl -LO CALICS.dev/CALICS2.sh
sh CALICS2.sh
```

## First steps after running scripts
Store GitHub credentials for Git authentication
```
git config --global user.name "Your Name"
git config --global user.email "youremail@yourdomain.com"
gh auth login
```
