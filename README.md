# Домашнее задание к занятию 9.4 «Prometheus» - Куприянов Владимир

### Инструкция по выполнению домашнего задания

1. Сделайте fork [репозитория c шаблоном решения](https://github.com/netology-code/sys-pattern-homework) к себе в Github и переименуйте его по названию или номеру занятия, например, https://github.com/имя-вашего-репозитория/gitlab-hw или https://github.com/имя-вашего-репозитория/8-03-hw).
2. Выполните клонирование этого репозитория к себе на ПК с помощью команды `git clone`.
3. Выполните домашнее задание и заполните у себя локально этот файл README.md:
   - впишите вверху название занятия и ваши фамилию и имя;
   - в каждом задании добавьте решение в требуемом виде: текст/код/скриншоты/ссылка;
   - для корректного добавления скриншотов воспользуйтесь инструкцией [«Как вставить скриншот в шаблон с решением»](https://github.com/netology-code/sys-pattern-homework/blob/main/screen-instruction.md);
   - при оформлении используйте возможности языка разметки md. Коротко об этом можно посмотреть в [инструкции по MarkDown](https://github.com/netology-code/sys-pattern-homework/blob/main/md-instruction.md).
4. После завершения работы над домашним заданием сделайте коммит (`git commit -m "comment"`) и отправьте его на Github (`git push origin`).
5. Для проверки домашнего задания преподавателем в личном кабинете прикрепите и отправьте ссылку на решение в виде md-файла в вашем Github.
6. Любые вопросы задавайте в чате учебной группы и/или в разделе «Вопросы по заданию» в личном кабинете.

Желаем успехов в выполнении домашнего задания.

---

### Задание 1

Установите Prometheus.

*Приведите скриншот systemctl status prometheus, где будет написано: prometheus.service — Prometheus Service Netology Lesson 9.4 — [Ваши ФИО].*
![image](https://user-images.githubusercontent.com/124167007/223275626-df18a3f6-ecfd-4a75-92c1-79f4b74be3b5.png)
---

### Задание 2

Установите Node Exporter.

*Приведите скриншот systemctl status node-exporter, где будет написано: node-exporter.service — Node Exporter Netology Lesson 9.4 — [Ваши ФИО].*
![image](https://user-images.githubusercontent.com/124167007/224185084-c8bd1ddd-22dc-472d-94f2-2bc15b8a0691.png)
---

### Задание 3

Подключите Node Exporter к серверу Prometheus.

*Приложите скриншот конфига из интерфейса Prometheus вкладки Status > Configuration.*
![image](https://user-images.githubusercontent.com/124167007/224188577-26ba8f5e-c556-4920-bcda-7c7e9aa5616f.png)
*Приложите скриншот из интерфейса Prometheus вкладки Status > Targets, чтобы было видно минимум два эндпоинта.*
![image](https://user-images.githubusercontent.com/124167007/224188612-dc6c7842-2d55-4574-b1f2-f84e120029a3.png)
---
## Дополнительные задания со звёздочкой*

Эти задания дополнительные. Их можно не выполнять. Это не повлияет на зачёт. Вы можете их выполнить, если хотите глубже разобраться в материале.

---

### Задание 4*

Установите Grafana.

*Приложите скриншот левого нижнего угла интерфейса, чтобы при наведении на иконку пользователя были видны ваши ФИО.*

![image](https://user-images.githubusercontent.com/124167007/224516110-56eb1893-7a97-4d6c-8fbc-01285a3249ef.png)
---

### Задание 5*

Интегрируйте Grafana и Prometheus.

*Приложите скриншот дашборда (ID:11074) с поступающими туда данными из Node Exporter.*

![image](https://user-images.githubusercontent.com/124167007/224516605-d7d1f145-146b-4eda-a20d-996c2c4fd454.png)
