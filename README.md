# Codelab3
Applied Computing 

Run Commands:
docker run --name mydba --network mynetwork -p 8081:80 -d my_dba   

docker run  --name mydb --network mynetwork -itd -p5432:5432 my_db 

docker run -it -p8000:8000 -v $(pwd)/app:/app my_django /bin/bash

python /app/app/manage.py runserver 0.0.0.0:8000

docker run -it -p8000:8000 --network mynetwork -v $(pwd)/app:/app my_django /bin/bash
