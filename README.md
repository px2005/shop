# shop
Чтобы развернуть программу:

python -m venv venv 

pip install -r requirements.txt

 в случае отсутствия базы или удаления:
 
python

from main import db

db.create_all()

exit()

