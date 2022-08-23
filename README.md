
# Configurações para o Visual Studio Code

Algumas extensões e configurações muito uteis para o VS Code.

- Ctrl/Command + shift + p para abrir a paleta de comandos;
- Open user settings, tem a opção JSON e UI (eu prefiro o JSON);

##

- Salva automaticamente os arquivos depois de um tempo que pode ser configurável:
```bash
    "files.autoSave": "afterDelay"
```

- Tira o mapa que vem do lado direito do VS Code por padrão:
```bash
    "editor.minimap.enabled": false
```

- Configura o menu para aparecer só quando apertar Alt:
```bash
    "window.menuBarVisibility": "toggle"
```

- Muda a forma de como o cursor pisca:
```bash
    "editor.cursorBlinking": "smooth"
```

- Desativa a navegação estrutural:
```bash
    "breadcrumbs.enabled": false
```

- Seleciona a quantidade de espaços do tab:
```bash
    "editor.tabSize": 2
```

- Seleciona se o editor vai inserir espaços para os tabs: 
```bash
    "editor.insertSpaces": true
```

- Não mostra os arquivos com as extensões selecionadas:
```bash
    "files.exclude": {
        ".vscode": true,
        "node_modules": true
    },
```

- Se o editor pede confirmação para mover arquivos:
```bash
    "explorer.confirmDragAndDrop": false
```

##
Extensões que eu uso:


- [Ballerini Theme](https://marketplace.visualstudio.com/items?itemName=BalleriniServer.ballerini-theme) e [vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons) para deixar o editor mais bonito :)
- [Rainbow Brackets](https://marketplace.visualstudio.com/items?itemName=2gua.rainbow-brackets), para deixar os colchetes coloridos, fica mais fácil de identificar;
- [Flutter](https://marketplace.visualstudio.com/items?itemName=Dart-Code.flutter) e [Dart](https://marketplace.visualstudio.com/items?itemName=Dart-Code.dart-code), para desenvolver em Flutter;
- [Beautify](https://marketplace.visualstudio.com/items?itemName=HookyQR.beautify), para identar o código ;
- [Code Runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner), para rodar o código em linha de comando do próprio VS Code;
- [CodeSnap](https://marketplace.visualstudio.com/items?itemName=adpyke.codesnap), para tirar print do código.
