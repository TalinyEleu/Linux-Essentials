# Linux: Introdução

## O que é Linux?

Linux é um software de sistema operacional que é executado em um sistema de computador de hardware. Um sistema operacional é um software que permite que outros programas, como processadores de texto e navegadores web, sejam instalados e executados em um computador.

A principal razão pela qual aprender Linux é útil, é que Linux é usado em quase todos os lugares! O Linux é usado em computadores desktop e laptop, servidores web, dispositivos móveis (Android), tecnologia de nuvem pública (ou seja, Google, Amazon, etc), Chromebooks e redes (ou seja, Cisco Networks).

## Quem pode usar o Linux?
Para entender por que as habilidades do Linux são únicas, vamos examinar a interface gráfica do usuário (GUI).

- GUI (Graphical User Interface): Esta é a interface que você provavelmente está usando em seu smartphone, tablet ou computador hoje. Uma GUI exibe ícones e imagens que você pode selecionar para dizer ao dispositivo o que deseja fazer ou usar. Atrás da GUI, está um código que um programador desenvolveu. Quando você clica em um ícone ou pasta em uma GUI, ele envia um comando para o código dizendo ao sistema o que fazer. 

![Exemplo de GUI](/imagens/Imagem1.jpg)

- CLI (Command-line interface): A linha de comando do Linux é uma interface baseada em texto que aceita comandos digitados nela. Esses comandos fazem com que uma ação seja executada no sistema operacional do computador.

![Exemplo de CLI](/imagens/Imagem2.png)

## Sintaxe de Comando Básico

### O que é um comando?

Um comando é um programa de software que, quando executado na CLI (Command-line Interface), executa uma ação no computador. Quando você digita um comando, um processo é executado pelo sistema operacional que pode ler o input (Entrada), manipular dados e produzir output (Saída). Um comando executa um processo no sistema operacional, que faz com que o computador execute um trabalho.
A maioria dos comandos segue um padrão simples de sintaxe:
```
comando [opcoes…] [argumentos…]
```

### Argumentos
Um argumento pode ser usado para especificar algo para o comando agir.
```
comando [opcoes…] [argumentos…]
```
### LS (List)
- ls (List, letras minúsculas L e S):  é usado para listar arquivos ou diretórios no Linux e em outros sistemas operacionais baseados no Unix.
```
ls [flags] [diretório]
```
**_OBS:_** Os diretórios são equivalentes a pastas no Windows e Mac OS. Assim como esses sistemas operacionais mais populares, uma estrutura de diretórios Linux tem um nível superior. Não é chamado de **“Meu Computador”**, mas sim o **diretório root (raiz)** e é representado pelo caractere **/**.