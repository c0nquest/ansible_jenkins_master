# Jenkins master and node ansible build

##  Install Jenkins Master
```bash
ansible-playbook -b jenkins-build.yaml --tags "install" -vvv
```
##  Install Jenkins Node
```bash
ansible-playbook -b jenkins-build.yaml --tags "node" -vvv
```
##  Uninstall Jenkins Master
```bash
ansible-playbook -b jenkins-build.yaml --tags "uninstall" -vvv
```
