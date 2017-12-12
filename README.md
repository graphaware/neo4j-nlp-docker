##GraphAware NLP with Docker

###Setup

**Download this repository**

```bash
git clone git@github.com:graphaware/neo4j-nlp-docker
```

**Change directory to plugins**

The following downloads the necessary plugins in their snapshot version

```bash
cd plugins
wget https://products.graphaware.com/download/framework-server-enterprise/graphaware-server-enterprise-all-3.3.0.51.jar
wget https://www.dropbox.com/s/ms1v6ht7zvqpufq/original-graphaware-nlp-3.3.0.51.2-SNAPSHOT.jar
wget https://www.dropbox.com/s/bb3ugb7nm33u0k2/nlp-stanfordnlp-3.3.0.51.2-SNAPSHOT.jar
```

**Return to the project directory and run**

```bash
cd ..
docker-compose up
```

**Check your neo4j instance**




---

Requirements

Make sure docker run with at least 5gb of memory :

![Imgur](https://i.imgur.com/FvmGJtZ.png)


