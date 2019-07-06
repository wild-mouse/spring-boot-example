## How to run playbook with EC2 instance

```
ansible-playbook -i inventory --private-key=~/.ssh/[your_key].pem playbook.yml -u ec2-user
```