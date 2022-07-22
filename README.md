### 3.7-skillbox

### Запуск
ansible-playbook -K -i host.inv site.yml --ask-vault-pass

### Проверка
ansible-playbook -K -i host.inv site.yml --ask-vault-pass --list-tasks --skip-tags nginx

ansible-playbook -K -i host.inv site.yml --ask-vault-pass --list-tasks --tags tagged

ansible-playbook -K -i host.inv site.yml --ask-vault-pass --list-tasks --skip-tags print

ansible-playbook -K -i host.inv site.yml --ask-vault-pass --list-tasks --tags print
