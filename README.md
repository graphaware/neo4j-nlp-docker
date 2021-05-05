As of May 2021, this [repository has been retired](https://graphaware.com/framework/2021/05/06/from-graphaware-framework-to-graphaware-hume.html).

---

## GraphAware NLP with Docker

### Setup

**Download this repository**

```bash
git clone git@github.com:graphaware/neo4j-nlp-docker
```

**Change directory to plugins**

The following downloads the necessary plugins in their snapshot version

```bash
cd plugins
wget https://products.graphaware.com/download/framework-server-enterprise/graphaware-server-enterprise-all-3.3.5.52.jar
wget https://products.graphaware.com/download/nlp/graphaware-nlp-3.3.3.52.7.jar
wget https://products.graphaware.com/download/nlp-stanford-nlp/nlp-stanfordnlp-3.3.3.52.7.jar
```

**Return to the project directory and run**

```bash
cd ..
docker-compose up
```

**Check your neo4j instance**

For documentation on using the NLP features, see [the GraphAware NLP repository](https://github.com/graphaware/neo4j-nlp)

# Requirements

Make sure docker run with at least 5gb of memory :

![Imgur](https://i.imgur.com/FvmGJtZ.png)
