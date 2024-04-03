Download Milvus Docker Image

```
wget https://raw.githubusercontent.com/milvus-io/milvus/master/scripts/standalone_embed.sh
bash standalone_embed.sh start
```

To stop milvus

```
bash standalone_embed.sh stop
```

To delete the docker image and the volume

```
bash standalone_embed.sh delete
```

Setting up Milvus Python SDK, this is meant for testing the milvus client.

```
python3 -m pip install pymilvus==2.4.0
pip3 install grpcio-tools
pip3 install protobuf==3.20.0
```
