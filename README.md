# Megadex Server
Megadex server is a application that connects a web search interface to data
indexed in Elasticsearch by [megadex](https://github.com/hodgesds/megadex).
This search application provides an easy way to find files based on (meta)data
when the file was indexed. This is extremely powerful when combined with the
real time file system monitoring/indexing capabilities of megadex.

# Installation
Installation uses done via **pip** and is as simple as:

```sh
pip install megadexserver
```

# Example
Start the server and navigate to the default [search
page](http://127.0.0.1:7000).

```sh
megadex-server
```
