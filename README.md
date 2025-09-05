# coding-project-template


## Part 1
cd xrwvm-fullstack_developer_capstone/server
pip install virtualenv
virtualenv djangoenv
source djangoenv/bin/activate

python3 -m pip install -U -r requirements.txt

python3 manage.py makemigrations
python3 manage.py migrate
python3 manage.py runserver

## Part 2
python3 manage.py createsuperuser
superviolet, violet@email.com, pass789qwsa

Application: port = 8000, open browser, then append /admin to the end of url.

cd /home/project/xrwvm-fullstack_developer_capstone/server/frontend
npm install
npm run build

cd /home/project/xrwvm-fullstack_developer_capstone/server/frontend
npm run build