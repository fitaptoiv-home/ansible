# ansible

git status

git diff README.md

git add README.md

git commit -m "just testing"

git push origin main


ansible linux -a "cat /etc/os-release"

ansible-playbook iluvnano.yml -bK

ansible-playbook update_linux.yml -K

ansible-playbook update_dns.yml -K

ansible linux -m ping


eval `ssh-agent -s`       Start ssh-agent
ssh-add ~/.ssh/git_key    Add a key to ssh-agent Kol...
ssh-add -l                List keys for ssh agent
cat git_key.pub
ssh -vT git@github.com
