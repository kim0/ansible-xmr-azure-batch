Install and run xmr stak on azure batch

Install steps
===
* ssh batchnode-0 (Usually port 50000), then `sudo apt install -y ansible sshpass`
* `ansible-playbook -k playbook.yml`
