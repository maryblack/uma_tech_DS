# Challenge Uma Tech. 
Необходимо предсказать отток пользователей условного сервиса. 

### Набор данных для выполнения задачи:
* TRAIN_PREPARED.csv/TEST_PREPARED.csv - уже предподготовленные данные для решения задачи;
* TRAIN_RAW.csv/TEST_RAW.csv - сырые данные, по которым собирались агрегации для решения задачи;
* TRAIN_ADDITIONAL_DATA.csv/TEST_ADDITIONAL_DATA.csv - дополнительные данные из другого источника.
В ходе решения вам стоит предсказать для user из TEST, уйдут ли они в отток, или останутся и будут пользоваться данным сервисом.

### Метод предоставления решения задачи:
Пример сабмита можно посмотреть в test_submit_example.csv.

#### Подготовка завсимостей проекта

Зависимости можно поставить 2мя способами:
- через jupyter notebook
- через venv и requirements.txt,
    - установка virtualenv: `pip install virtualenv`
    - создание virtualenv: `virtualenv --python=python3.6 ./venv`
    - активация: `source venv/bin/activate`
    - установка зависимостей: `pip install -r requirements.txt`
    - далее можно запустить Jupyter notebook с подготвленными зависимостями, указав
    созданный virtualenv в качестве kernel
