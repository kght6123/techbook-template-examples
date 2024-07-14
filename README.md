# techbook-template-examples

## Memo


## Developer Guide

### Update Examples

```sh
# 105x173
npm run build
cp -Rf ./node_modules/@vivliostyle/viewer/lib/* ../techbook-template-examples/105x173/
cp -Rf ./dist ../techbook-template-examples/105x173/
cp -Rf ./images ../techbook-template-examples/105x173/dist/
cp -Rf ./dist ../techbook-template-examples/105x173/dist/
rm ../techbook-template-examples/105x173/dist/.gitignore
rm ../techbook-template-examples/105x173/dist/dist/.gitignore
# JIS-B5
npm run build
cp -Rf ./node_modules/@vivliostyle/viewer/lib/* ../techbook-template-examples/JIS-B5/
cp -Rf ./dist ../techbook-template-examples/JIS-B5/
cp -Rf ./images ../techbook-template-examples/JIS-B5/dist/
cp -Rf ./dist ../techbook-template-examples/JIS-B5/dist/
rm ../techbook-template-examples/JIS-B5/dist/.gitignore
rm ../techbook-template-examples/JIS-B5/dist/dist/.gitignore
```

https://kght6123.github.io/techbook-template-examples/105x173/index.html#src=./dist/publication.json&bookMode=true&renderAllPages=true&style=./dist/global.css

### Error

アンダーバーからはじまるファイルが無視されるので、ファイル名を変更する必要がある

