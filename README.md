# LESS Combiner

LESS Combiner is a little helper to aggregate all your LESS and CSS files in to a singular file that can be compiled to CSS during a build process using grunt or another tool. It also handles utf8 and BOM problems for you.

Example:

```
lessCombiner.combine({
    paths: ['./less/', './more-less/', './3rd-party-css/'],
    outputFileName: './build/style.less'
});
```

## Author

**Alexander Marinenko**

+ [http://twitter.com/jo_asakura](http://twitter.com/jo_asakura)
+ [http://github.com/jo-asakura](http://github.com/jo-asakura)

## Copyright and license

[MIT](LICENSE.md)
