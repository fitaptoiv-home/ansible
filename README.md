# ansible

git status

git diff README.md

git add README.md

git commit -m "just testing"

git push origin main


ansible linux -a "cat /etc/os-release"

ansible-playbook iluvnano.yml

ansible-playbook update_linux.yml -K

ansible-playbook update_dns.yml -K

ansible linux -m ping
