mackerel-plugin-gearmand
=========================

Gearmand custom metrics plugin for mackerel.io agent.

## Synopsis

```shell
mackerel-plugin-gearmand [-host=<host>] [-port=<port>] [-socket=</path/to/unixsocket>] [-tempfile=<tempfile>]
```

## Installation
- `mkr plugin install mackerelio/mackerel-plugin-gearmand`
- Or download binary in Github Releases

## Example of mackerel-agent.conf

```
[plugin.metrics.gearmand]
command = "/path/to/mackerel-plugin-gearmand"
```

