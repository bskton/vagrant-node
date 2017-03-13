# Окружение для разработки под Node.js

Конфигурация для запуска виртуальной машины под управлением Vagrant, 
Виртуальная машина конфигурируется с помощью Ansible, ее можно использовать 
для разработки и запуска предложения под Node.js.

## Системные требования

 * Ubuntu 16.04 64-bit
 * Vagrant 1.8.6
 * VirtualBox 5.1
 * Ansible 2.3.0
 * Git 2.7.4

## Использование

Склонировать репозиторий на свой комьютер
```bash
~$ git clone https://github.com/bskton/vagrant-node.git
```

Запустить виртуальную машину
```bash
~/vagrant-node/vagrant$ vagrant up
```

Выполнить настройку виртуальной машины с помощью Ansible
```bash
~/vagrant-node/ansible$ ansible-playbook dev.yml
```