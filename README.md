# ansible

Testing testing


git status
git diff README.md
git add README.md
git commit -m "just testing"
git push origin main

ansible all --become-user tapio --private-key ~/.ssh/id_rsa -i hosts -m ping

ansible all --become-user tapio --list-hosts
ansible all --become-user tapio  -m gather_facts --limit 192.168.0.20
