<<<<<<< HEAD
ssh-connect
#generate rsa key pair and add to ssh
ssh-keygen -t rsa -b 4096 -N '' -C "rthijssen@gmail.com" -f ~/.ssh/id_rsa
ssh-keygen -t rsa -b 4096 -N '' -C "rthijssen@gmail.com" -f ~/.ssh/github_rsa
ssh-keygen -t rsa -b 4096 -N '' -C "rthijssen@gmail.com" -f ~/.ssh/mozilla_rsa
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/github_rsa
chmod 600 ~/.ssh/github_rsa
chmod 644 ~/.ssh/github_rsa.pub
=======
#!/Bin/Bash
12
12
222
>>>>>>> 33361045545fa82ce4b7cec31c9902277feecce9
223
23
24
25
26
