# django + uwsgi
virtualenv ./env<br>
source ./env/bin/active<br>
pip install -r requirements.txt<br>
uwsgi --ini ./uwsgi/uwsgi.ini
