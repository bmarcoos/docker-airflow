Based on Puckel's repo https://github.com/puckel/docker-airflow

-----

This repository makes a workaround to install python packages using docker-compose.

### Run it

Make sure there is a *requierements.txt* with the libraries you want to install in the airflow container. Then run:

```$docker-compose up -d```

### Check the installation

Get into the console of the container:
```$ docker exec -it <mycontainer> bash```

In the container shell run:
```$ pip freeze```

Your python libraries should be there.

