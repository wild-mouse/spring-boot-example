## How to run playbook with EC2 instance

```
ansible-playbook -i ansible/inventory --private-key=~/.ssh/[your_key].pem ansible/playbook.yml -u ec2-user
```