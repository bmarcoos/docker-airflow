Based on Puckel's repo https://github.com/puckel/docker-airflow

-----

This repo makes a workaround to install python packages using docker-compose

### Run it

```$docker-compose up -d```

### Check

```$ docker exec -it <mycontainer> bash```

```$ pip freeze```

Your python libraries should be there 

