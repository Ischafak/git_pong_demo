Cihat bu yazi

yazi yazi

https://stackoverflow.com/questions/11656761/git-please-tell-me-who-you-are-error

The thing to hate for being overcomplex and hostile is git itself, not Github. And there’s not much defense I can give for git, it really is that bad. Do this to fix your repo:

git remote set-url origin git@github.com:MrsColombo/elsevier-twitter-rest-api.git

In the future, clone your repos using ssh and not https, and they’ll always be writable. You can get the ssh url from the green “clone or download” button. Alternatively, use the github desktop app, which uses your ssh keys by default.



asdsa
a
sd
as
d
asd
a