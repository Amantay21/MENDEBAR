# MENDEBAR
MENDEBAR

##Зависимости
 Для запуска проекта у вас должен быть установлен Python3.7 и выше и pip

 ## Локальный запуск проекта

 После клонирования проекта выполняете команды:

### Cоздайте виртуальное окружение командой

```bash
python -m venv venv
```

### Установите зависимости командой 
```bash
pip install -r requirements.txt
```

### Перейдите в папку source командой
```bash
cd source
```

### Примените миграции командой 
```bash
python3 manage.py migrate
```

### Запустите проект
```bash
python3 manage.py runserver localhost:8000

Для доступа к панел  администратора перейдите по ссылке http://localhost:8000/admin
