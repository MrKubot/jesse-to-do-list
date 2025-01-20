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

pip install TA-Lib
