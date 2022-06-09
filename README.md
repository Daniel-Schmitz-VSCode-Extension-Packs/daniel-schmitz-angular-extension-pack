# daniel-schmitz-angular-extension-pack

Esta é uma forma que eu uso para ter profiles diferentes para cada tipo de configuração no VSCODE. Por exemplo, o `daniel-schmitz-angular-extension-pack` traz apenas extensões do angular,
então quando eu estou desenvolvendo em angular eu desabilito todos os outros packs e deixo apenas este funcionando.

![](https://user-images.githubusercontent.com/1509692/172887347-ca110094-4633-4842-beb1-25ab7135e63e.png)

Esta extension pack nao está publicada no vscode, é necessário instalar o `vsce` e gerar um pack (arquivo vsix). Então, com o pack pronto, instalo ela. 

## install

```
npm install -g vsce
git clone https://github.com/Daniel-Schmitz-VSCode-Extension-Packs/daniel-schmitz-angular-extension-pack.git
cd daniel-schmitz-angular-extension-pack
vsce package
code --install-extension daniel-schmitz-angular-extension-pack-0.0.1.vsix
```

