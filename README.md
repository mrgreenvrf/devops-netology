#the first commentary
#the second commentary
#
#
#Дополнение к домашнему заданию по расшифровке правил .gitignore  в каталоге terraform
#
#В репозиторий не попадут следующие файлы из директории terraform:
#1)любые файлы, находящиеся в любом подкаталоге .terraform
#2)любые файлы, заканчивающиеся на (с расширением) .tfstate, а также файлы, содержащие в названии .tfstate.
#3)файл crach.log в любом подкаталоге
#4)любые файлы с расширением .tfvars
#5)файлы override.tf и override.tf.json, а также имеющие произвольное начало имени и заканчивающиеся на _override.tf и _override.tf.json
#6)любые файлы .terraformrc и terraform.rc
