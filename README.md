GIT

VS Code

https://www.python.org/downloads/release/python-3100/

check PATH - environment/zmienne środowiskowe

WSL


sudo apt-get update

    sudo apt-get upgrade
    
    sudo apt-get install redis-server
    
    redis-cli -v

redis-server



https://www.postgresql.org/download/windows/

PATH - probably C:\Program Files\PostgreSQL\12\bin

psql -U postgres

CREATE DATABASE jesse_db;

CREATE USER jesse_user WITH PASSWORD 'password';

GRANT ALL PRIVILEGES ON DATABASE jesse_db to jesse_user;

ALTER DATABASE jesse_db OWNER TO jesse_user;

\q


https://visualstudio.microsoft.com/pl/visual-cpp-build-tools/

+ basic C++


https://github.com/ta-lib/ta-lib-python

pip install TA-Lib

PATH

git clone https://github.com/jesse-ai/project-template my-bot

cd my-bot

# create a .env file by copying it from the template

cp .env.example .env


python -m venv env

.\env\Scripts\activate

pip install jesse (time consuming / --use-deprecated=legacy-resolver)

# _________________________________________
cd docker 

docker-compose up
