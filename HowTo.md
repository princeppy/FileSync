# How To generate vsix and install FileSync

```shell
npm install -g vsce
```

```shell
$ cd myExtension
$ vsce package
# myExtension.vsix generated
$ vsce publish
# <publisherID>.myExtension published to VS Code Marketplace
```