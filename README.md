Ansible Playbook, который устанавливает Wordpress.
Хост Ubuntu, клиент Centos/7.

Проект задумывался реализоваться в AWS, но к сожаленю не хватило времени и знаний, что бы это свершилось. На данном этапе были успешно проведены тесты только на vagrant.

Если систему разворачивать на локальном сервере, то можно обойтись простой генерацией ssh ключа, что позволит проводить беспорольную аутентификацию сервера с клиентом. 

В данном проекте я не забыл про систему шифрования ansible-vault. Зашифрован основной плейбук и файл с достаточно ценной информацией, что позволяет защититься от копипаста и неправомерного доступа к информации. 

Я сразу признаю что не всё решено оптимально, возможно было бы лучше завернуть WP-CLI в плейбук и уже с его помощью проводить манипуляции с Wordpress. Но увы, к дедлайну не успел.  

Задание определенно интересное, со своими тонкостями, в процессе я многое узнал и глубоко окунулся в основы devops'a, но также обнаружил и пробелы в знаниях и нехватку практики. Независимо от результата проверки, буду его дорабатывать. 


