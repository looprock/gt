A way to alias hosts for ssh. See config for examples.

drop gt.cnf and hosts under ~/gt, configure them and you should be good to go

hosts format:

[alias] [hostname/ip] [optional: username] [optional: identity file] [optional: port]

example: 

ec2-instance1 alias.domain.com ubuntu /home/username/ec2/personal.pem 2222
