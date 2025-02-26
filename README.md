# Palestra: Introdução à TypeScript & features 2.x (Wo Makers Code)

Demos realizadas durante o evento Wo makers Code!

**p.s.: deseja tirar um certificado desse curso?! Basta clicar (disponível na UDEMY) - [AQUI](https://www.udemy.com/curso-typescript-para-desenvolvedores-c)**

A apresentação da palestra encontra-se [AQUI](https://pt.slideshare.net/GlauciaLemos/apresentao-introduo-typescript-net-caxias-do-sul)

### Configuração do Ambiente de Desenvolvimento:

Se você optar em usar o Visual Studio Code, será bem simples de configurar o ambiente.

#### Antes de tudo.....
Há necessidade de instalar:

* Node.Js: [LINK - AQUI](https://nodejs.org/en/)
* TypeScript: [LINK - AQUI](https://www.typescriptlang.org/) 

Assim que segue os links acima!! ;)

#### 1º Passo:
Vá até a página do Visual [Studio Code](https://code.visualstudio.com/docs/languages/typescript) -> Docs - Languages -> TypeScript -> tsconfig.json (conforme segue a imagem abaixo):

![alt tag](https://uploaddeimagens.com.br/images/000/921/644/original/pic_1.png?1495141187)

#### 2º Passo:
Depois basta copiar as informações inerentes ao arquivo: **tsconfig.json**

#### 3º Passo:
Abre o seu Visual Studio Code e crie na raiz do projeto o arquivo: **tsconfig.json** e logo em seguida copie
as informações copiadas no site do Visual Studio Code e Salve o arquivo.


#### 4º Passo:
Depois de ter criado o arquivo tsconfig.json, clique nos botões: Crtl + Shift + P e digite: 'Configure Default Build Task' e escolha a opção 'tsc:build - tsconfig.json' e vai gerar uma pasta e arquivo: 

* .vscode
* task.json


#### 5º Passo:
Abre o arquivo: tasks.json e altere para as seguintes linhas:

```
{    
  // See https://go.microsoft.com/fwlink/?LinkId=733558
  // for the documentation about the tasks.json format
  "version": "2.0.0",
  "tasks": [
    {
      "taskName": "compile",
      "type": "shell",
      "command": "tsc -p tsconfig.json",
      "group": {
        "kind": "build",
        "isDefault": true
      },
      "problemMatcher": ["$tsc"]
    }
  ]
}

```

#### 6º Passo:
Para executar o código, basta clicar nos botões: CTRL + SHIFT + B.. e com o terminal integrado no Visual 
Studio Code, basta ir até o diretório do arquivo e digitar o seguinte comando:

```
> node [nome-do-arquivo] || Ex.: -> node animal
```

## Dúvidas?!

Se tiverem alguma dúvida referente ao código feito ou para configurar o ambiente basta criar uma Issue aqui no GitHub que estarei respondendo a vocês!! :D :D 
De qualquer forma estou disponibilizando aqui um vídeo, a qual mostra o passo-a-passo como realizar a configuração no VS Code. 

**Para versões antigas do TypeScript (versão.: 1.x**): Link do video: [AQUI](https://www.youtube.com/watch?v=DwEJEVVqFVw&t=23s&list=PLb2HQ45KP0Wt32eCnju3lyncXUvDV5Nob&index=2)


