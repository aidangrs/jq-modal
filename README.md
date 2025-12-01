# Burp JQ

This is a Burp Extension to apply [jq](https://github.com/stedolan/jq) queries
to JSON content from the HTTP message viewer. This has been modified to allow multiple JSON objects to be rendered, where before the JQ response window would only display the first overall JSON object. 

![Demo GIF](img/demo.gif)

## Build

```bash
$ gradle fatJar
```

## Credits

Burp JQ relies on `jackson-jq`, a Java implementation of `jq`.

- [jq](https://github.com/stedolan/jq)
- [jackson](https://github.com/FasterXML/jackson)
- [jackson-jq](https://github.com/eiiches/jackson-jq)

