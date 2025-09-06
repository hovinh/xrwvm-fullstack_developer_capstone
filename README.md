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


## Part 3a

Build docker app

cd server/database
docker build . -t nodeapp

Run docker-compose.yml
docker-compose up

https://hxvinhhcmus-3030.theiadockernext-0-labs-prod-theiak8s-4-tor01.proxy.cognitiveclass.ai/fetchReviews/dealer/29

https://hxvinhhcmus-3030.theiadockernext-0-labs-prod-theiak8s-4-tor01.proxy.cognitiveclass.ai/fetchDealers

https://hxvinhhcmus-3030.theiadockernext-0-labs-prod-theiak8s-4-tor01.proxy.cognitiveclass.ai/fetchDealer/3

https://hxvinhhcmus-3030.theiadockernext-0-labs-prod-theiak8s-4-tor01.proxy.cognitiveclass.ai/fetchDealers/Kansas

## Part 3b

python3 manage.py makemigrations
python3 manage.py migrate --run-syncdb

username: root
password: root

https://hxvinhhcmus-8000.theiadockernext-0-labs-prod-theiak8s-4-tor01.proxy.cognitiveclass.ai/djangoapp/get_cars