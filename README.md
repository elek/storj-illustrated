# Storj on Diagrams

Diagrams are under: https://github.com/storj/illustrated/tree/master/docs

But it's also visible in one HTML page at: https://storj.github.io/illustrated/

The diagrams represent my (may or may not be good) understanding.

If you see any problems, please create an issue.

If you need something to be explained, please create an issue.

## How to contribute

Original source of the diagrams can be edited with online or offline version of [diagrams.net](https://app.diagrams.net)

When one diagram is saved, both the export (svg) both the embedded source are updated. 

PR can be created where the old version and new version of the SVG can be seen, just click to the *rich diff* option:

![Rich diff](https://user-images.githubusercontent.com/170549/137105249-4fc31311-dbe0-49a9-82d9-37dace8ebcfa.png)

To regenerated the preview above, the following can be used (after existing lines are removd):

```
docs/*.svg | sort | xargs -n1 -IFILE printf "\![FILE](FILE)\n\n\`\`\`\n\n\n\n\`\`\`\n\n"
```


## Diagrams

![docs/0title.svg](docs/0title.svg)

```



```

![docs/authservice.svg](docs/authservice.svg)

```



```

![docs/core.svg](docs/core.svg)

```



```

![docs/edge.svg](docs/edge.svg)

```



```

![docs/encrypted-keys.svg](docs/encrypted-keys.svg)

```



```

![docs/encrypted-path.svg](docs/encrypted-path.svg)

```



```

![docs/grant.svg](docs/grant.svg)

```



```

![docs/macaroon.svg](docs/macaroon.svg)

```



```

![docs/read1.svg](docs/read1.svg)

```



```

![docs/read2.svg](docs/read2.svg)

```



```

![docs/reputation.svg](docs/reputation.svg)

```



```

![docs/satellite-api.svg](docs/satellite-api.svg)

```



```

![docs/secrets.svg](docs/secrets.svg)

```



```

![docs/versioncontrol.svg](docs/versioncontrol.svg)

```



```

