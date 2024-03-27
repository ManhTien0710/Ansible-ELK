# Edit inventory.ini
```bash
change host IP:

```
# Edit vars.yml
```bash
Change var 
```
# Install ELK
```bash
ansible-playbook -i inventory.ini playbook.yml -u root
```
# Uninstall ELK
```bash
ansible-playbook -i inventory.ini playbook-uninstall.yml -u root
```