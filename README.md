
ansible-playbook -b jenkins-build.yaml --tags "install" -vvv

ansible-playbook -b jenkins-build.yaml --tags "node" -vvv

ansible-playbook -b jenkins-build.yaml --tags "uninstall" -vvv
