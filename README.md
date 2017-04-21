<h1 align="center">
<img src="https://raw.githubusercontent.com/Renien/spark-ml-document-classification/master/doc/blob/article.png" alt="article" width="20%" height="20%">
    <br>
        spark-ml-document-classification
    <br>
  <h4 align="center">example for document classification</h4>
</h1>

<p align="center">
  <a href="https://github.com/Renien/spark-ml-document-classification/blob/master/LICENSE">
    <img src="https://img.shields.io/npm/l/express.svg?maxAge=2592000&style=flat-square"
         alt="License">
  </a>
  <a href="https://travis-ci.org/Renien/spark-ml-document-classification">
    <img src="https://travis-ci.org/Renien/spark-ml-document-classification.svg?branch=master"
         alt="Travis Build">
  </a>
</p>

## Summary
An example on using spark ML models to classify docuements

## Sample DataSet

Sample News article data is from by [www.theguardian.com](https://www.theguardian.com).

This example uses a very small dataset extracted from few articles. Each new line contains article data consisting of following data format:

```json
{ 
    "bodyText": "..", 
    "webPublicationDate": "25-01-1999", 
    "topics": ["media"] 
}
```
