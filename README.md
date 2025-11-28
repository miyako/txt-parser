![platform](https://img.shields.io/static/v1?label=platform&message=mac-intel%20|%20mac-arm%20|%20win-64&color=blue)
[![license](https://img.shields.io/github/license/miyako/opc-parser)](LICENSE)
![downloads](https://img.shields.io/github/downloads/miyako/opc-parser/total)

### Dependencies and Licensing

* the source code of this CLI tool is licensed under the MIT license.
 
# txt-parser
CLI tool to extract text from TXT

```
text extractor for txt documents

 -i path  : document to parse
 -o path  : text output (default=stdout)
 -        : use stdin for input
 -r       : raw text output (default=json)
```

## JSON

|Property|Level|Type|Description|
|-|-|-|-|
|document|0|||
|document.type|0|Text||
|document.pages|0|Array||
|document.pages[].paragraphs|1|Array||
|document.pages[].paragraphs[].text|2|Text||
