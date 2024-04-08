# Euclidean vs. Canberra distances in KNN

An exploratory study comparing the performance of KNN algorithm in image classification tasks using two different distance metrics: Euclidean distance and Canberra distance. The objective is to analyze and compare the computational performance and accuracy achieved by each distance metric.

## How to run it

To utilize the `persian_letters.ipynb` notebook, you can either run it directly in your Python environment or use Docker with the provided docker-compose file:

```sh
docker compose up -d
```

After starting the container, retrieve the access link for Jupyter by logging the container:

```sh
docker containter logs notebook
```

Look for the access link in the logs. It typically appears as follows:

```sh
    To access the server, open this file in a browser:
        file:///home/jovyan/.local/share/jupyter/runtime/jpserver-7-open.html
    Or copy and paste one of these URLs:
        http://c30fee140b4b:8888/lab?token=3454631729f6ebb95557e080570213a7f9025daedebbd41e
        http://127.0.0.1:8888/lab?token=3454631729f6ebb95557e080570213a7f9025daedebbd41e
```

We recommend using the last URL (starting with 127.0.0.1 or localhost) for easier access.