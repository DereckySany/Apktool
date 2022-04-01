# Apktool [![apktools](https://s3.amazonaws.com/github/ribbons/forkme_right_green_007200.png)](https://github.com/iBotPeaches/Apktool)
**Este é o repositório do Apktool. Se você estiver procurando pelo site Apktool. Clique [aqui](https://github.com/iBotPeaches/Apktool/tree/gh-pages).**

### Uma ferramenta para engenharia reversa de arquivos apk Android

```
$ apktool d test.apk
I: Using Apktool 2.6.1 on test.apk
I: Loading resource table...
I: Decoding AndroidManifest.xml with resources...
I: Loading resource table from file: 1.apk
I: Regular manifest package...
I: Decoding file-resources...
I: Decoding values */* XMLs...
I: Baksmaling classes.dex...
I: Copying assets and libs...
I: Copying unknown files...
I: Copying original files...
$ apktool b test
I: Checking whether sources has changed...
I: Smaling smali folder into classes.dex...
I: Checking whether resources has changed...
I: Building resources...
I: Building apk file...
I: Copying unknown files/dir...
```

[![Participe do chat em https://gitter.im/iBotPeaches/Apktool](https://badges.gitter.im/iBotPeaches/Apktool.svg)](https://gitter.im/iBotPeaches/Apktool?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![CI](https://github.com/iBotPeaches/Apktool/actions/workflows/build.yml/badge.svg)](https://github.com/iBotPeaches/Apktool/actions/workflows/test.yml)
[![Software License](https://img.shields.io/badge/license-Apache%202.0-brightgreen.svg)](https://github.com/iBotPeaches/Apktool/blob/master/LICENSE)

É uma ferramenta para aplicativos Android binários de terceiros, fechados e de engenharia reversa. Ele pode decodificar recursos para a forma quase original e reconstruí-los após fazer algumas modificações; torna possível depurar o código smali passo a passo. Também facilita o trabalho com o aplicativo devido à estrutura de arquivos semelhante a um projeto e à automação de algumas tarefas repetitivas, como criar apk, etc.

NÃO se destina a pirataria e outros usos não legais. Ele pode ser usado para localizar, adicionar alguns recursos ou suporte para plataformas personalizadas e outros propósitos BONS. Apenas tente ser justo com os autores de um aplicativo que você usa e provavelmente gosta.

#### Apoiar
- [Página do projeto](https://ibotpeaches.github.io/Apktool/)
- [Apktool no libera.chat](https://web.libera.chat/)

#### Patrocinado por

* [Sourcetoad](https://www.sourcetoad.com/cool-tools/apktool/) - ajudando com um patrocínio semanal para melhoria contínua e manutenção do projeto.

#### IDE de escolha

* [JetBrains IntelliJ](https://www.jetbrains.com/idea/)

#### Vulnerabilidades de segurança

Se você descobrir uma vulnerabilidade de segurança no Apktool, envie um e-mail para Connor Tumbleson em connor.tumbleson(at)gmail.com. Todas as vulnerabilidades de segurança serão prontamente solucionadas.

#### Links
- [Downloads](https://bitbucket.org/iBotPeaches/apktool/downloads)
- [Espelho de downloads](https://connortumbleson.com/apktool/)
- [Como construir](https://ibotpeaches.github.io/Apktool/build/)
- [Documentação](https://ibotpeaches.github.io/Apktool/documentation/)
- [Relatórios de bugs](https://github.com/iBotPeaches/Apktool/issues)
- [Chat on Gitter](https://gitter.im/iBotPeaches/Apktool)
- [Changelog/Information](https://ibotpeaches.github.io/Apktool/changes/)
- [Post XDA](https://forum.xda-developers.com/t/util-dec-2-2020-apktool-tool-for-reverse-engineering-apk-files.1755243/)
- [Fonte (Github)](https://github.com/iBotPeaches/Apktool)
- [Fonte (Bitbucket)](https://bitbucket.org/iBotPeaches/apktool/)
