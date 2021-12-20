Ansible & Git

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

git config --global user.name "TapioT"
git config --global user.email "xxxx@gmail.com"
git init
git clone https://github.com/fitaptoiv-home/ansible
eval ssh-agent -s Start ssh-agent
ssh-add ~/.ssh/git_key Add a key to ssh-agent Kol...
ssh-add -l List keys for ssh agent
cat git_key.pub
ssh -vT git@github.com test authentication
git remote -v check linked remote repository
git pull
git pull origin
git clone https://github.com/fitaptoiv-home/basic ~/basic Clone remote and create local from scratch




git branch bugfix
git checkout bugfix
git commit
git merge main/bugfix
git push origin main
