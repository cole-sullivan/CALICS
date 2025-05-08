# Cole's Arch Linux Installation & Configuration Scripts

CALICS consists of 2 scripts: CALIS (the installation script) and CALCS (the configuration script).

### CALIS
on an Arch live USB, connect to ethernet or connect to wifi with
```
iwctl --passphrase [password] station [station] connect [network]
```
then, run
```
curl -fsSL CALICS.dev/CALIS.sh | sh
```

### CALCS
after rebooting, sign in as root. then, connect to ethernet or connect to wifi with 
```
nmtui
```
then, run
```
curl -fsSL CALICS.dev/CALCS.sh | sh
```

## First steps after running scripts
Store GitHub credentials for Git authentication
```
git config --global user.name "Your Name"
git config --global user.email "youremail@yourdomain.com"
gh auth login
```
Set up Librewolf extensions by launching Librewolf and clicking the jigsaw icon at the top right
