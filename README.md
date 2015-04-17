### Compilando arquivos LATEX
----------------------------
#### Dependencias
 - [TexLive](https://www.tug.org/texlive/)
 - [Node.JS](https://nodejs.org/)

#### Instale o gulpJS 
Rode no bash/zsh/cmd/PowerShell
```sh
npm install -g gulp
```

Para instalar as dependencias, na pasta `docs` deste repositorio rode 
```sh
npm install
```

#### Iniciando monitor de compila�ao do latex
Rode na pasta docs/ onde se encontra o arquivo `gumpfile.js`

```sh
gulp
```

toda alteração no arquivo `.tex` na pasta tex ira gerar altomaticamente o pdf na pasta pdf/

