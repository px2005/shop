# shop
Чтобы развернуть программу:
python -m venv venv 
pip install -r requirements.txt

 в случае отсуттвии базы или пересоздания:
python
from main import db
db.create_all()
exit()
