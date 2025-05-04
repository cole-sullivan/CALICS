# Cole's Arch Linux Installation & Configuration Scripts (CALICS)

### CALICS1
on an Arch live USB, connect to ethernet or connect to wifi with
```
iwctl --passphrase [password] station [station] connect [network]
```
then, run
```
curl -LO CALICS.dev/CALICS1.sh
sh CALICS1.sh
```

### CALICS2
after rebooting, sign in as root. then, connect to ethernet or connect to wifi with 
```
nmtui
```
then, run
```
curl -LO CALICS.dev/CALICS2.sh
sh CALICS2.sh
```

## First steps after running scripts
Store GitHub credentials for Git authentication
```
git config --global user.name "Your Name"
git config --global user.email "youremail@yourdomain.com"
git config --global core.editor "nvim"
gh auth login
```
Set up Librewolf extensions by launching Librewolf and clicking the jigsaw icon at the top right
