# OpenSearch Example

This is a little example of creating an index, uploading data, and searching with AWS OpenSearch (+ knn plugin).

The file create_small_dataset.ipynb crawls and scrapes constitutioncenter.org to get the text and ratification date of all the ammendments to the US constitution, then runs the text through a transformer to compute embeddings (later used for semantic search).

The file main.ipynb has all the OpenSearch stuff.

I've removed the username, password, and url relevent to my project in main.ipynb.
