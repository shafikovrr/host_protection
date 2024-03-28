# Домашнее задание к занятию "`Название занятия`" - `Фамилия и имя студента`


---

### Задание 1

1. `Установите eCryptfs.`
2. `Добавьте пользователя cryptouser.`
3. `Зашифруйте домашний каталог пользователя с помощью eCryptfs.`
   
`В качестве ответа пришлите снимки экрана домашнего каталога пользователя с исходными и зашифрованными данными.`

### Решение 1 

```
sudo apt update && sudo apt upgrade -y
sudo apt install ecryptfs-utils
sudo adduser cryptouser
su cryptouser
cd /home/cryptouser
touch cryptouser.password
ls
```

![cryptouser_adduser_touch](img/cryptouser_adduser_touch.png)

![cryptouser_admin_sudo_ls](img/cryptouser_admin_sudo_ls.png)

```
sudo ecryptfs-migrate-home -u cryptouser
sudo ls /home/ryptouser
```

![cryptouser_ecryptfs-migrate-home_sudo_ls](img/cryptouser_ecryptfs-migrate-home_sudo_ls.png)

---

### Задание 2

1. `Установите поддержку LUKS.`
2. `Создайте небольшой раздел, например, 100 Мб.`
3. `Зашифруйте созданный раздел с помощью LUKS.`

`В качестве ответа пришлите снимки экрана с поэтапным выполнением задания.`

### Решение 2

```

```

![Название скриншота 2](ссылка на скриншот 2)

---

### Задание 3

1. `Установите apparmor.`
2. `Повторите эксперимент, указанный в лекции.`
3. `Отключите (удалите) apparmor.`

`В качестве ответа пришлите снимки экрана с поэтапным выполнением задания.`

### Решение 3

```

```

![Название скриншота 3](ссылка на скриншот 3)

---
