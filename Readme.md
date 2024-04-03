# Milvus Setup

Milvus is a vector database built for scalable similarity search.

It is specifically designed for computer vision tasks such as for Face Recognition Search and Image Similarity Search.

# Setup 

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
```

To test a client script:

```
cd client
python hello_milvus24.py
```





