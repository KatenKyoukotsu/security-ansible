# security-ansible
Практическая работа иннополис №2
Этот скрипт предназначен для автоматизации базовой настройки безопасности серверов Linux с использованием Ansible. Скрипт обновляет пакеты, устанавливает и настраивает Fail2Ban, настраивает брандмауэр, а также отключает ненужные службы.
Установка
Убедитесь, что у вас установлен Ansible.
```bash
   sudo apt install ansible  # Для Debian/Ubuntu
   sudo yum install ansible  # Для RedHat/CentOS
   ```
Склонируйте репозиторий или создайте файл security_harden.yml в вашем рабочем каталоге.
```bash
   git clone https://github.com/KatenKyoukotsu/security-ansible.git
   cd /path/to/security-ansible.git                 
   ```
Запуск
Для запуска playbook выполните следующую команду:

```bash
ansible-playbook security_harden.yml --ask-become-pass
```


