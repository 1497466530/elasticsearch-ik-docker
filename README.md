# elasticsearch-ik-docker

elasticsearch(2.3.3) + ik(1.9.3) plugin docker

# How to pull

```bash
docker pull 1497466530/elasticsearch-ik:2.3
```
# How to start

```bash
docker run -d -p 9200:9200 -v "/home/grantchen/esdata":/usr/share/elasticsearch/data 1497466530/elasticsearch-ik:2.3
```
