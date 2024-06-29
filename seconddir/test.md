ssh-connect
#generate rsa key pair and add to ssh
ssh-keygen -t rsa -b 4096 -N '' -C "rthijssen@gmail.com" -f ~/.ssh/id_rsa
ssh-keygen -t rsa -b 4096 -N '' -C "rthijssen@gmail.com" -f ~/.ssh/github_rsa
ssh-keygen -t rsa -b 4096 -N '' -C "rthijssen@gmail.com" -f ~/.ssh/mozilla_rsa
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/github_rsa
chmod 600 ~/.ssh/github_rsa
chmod 644 ~/.ssh/github_rsa.pub
