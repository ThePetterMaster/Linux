# Linux

## pwd

````
/home/guilherme
````
## echo Bem vindo ou echo "Bem vindo"

````
Bem vindo
````

## Escrevendo em um arquivo (criando caso não exista)

````
echo "Bem vindo" > bemvindo.txt
````
## Lendo o conteúdo do arquivo criado

````
cat bemvindo.txt
````

## Manual de um comando

````
man ls
````
## Nome do usuário do linux

````
whoami
````
Resultado:
````
wsl
````

## Mudar para uma pasta do mesmo diretório

````
cd Desktop/
````

## Escrever em um arquivo sem sobrescrever o conteudo atual

````
echo "Faithless" >> musicas-favoritas.txt
````

## Criando uma pasta 

````
mkdir projetos-java
````

##  Outros comandos

- pwd: para descobrir o diretório atual.
- ls: para listar arquivos e diretórios, vimos as opções -l e -la, que listam além dos arquivos e diretórios ocultos, informações extras sobre cada um deles.
- echo para imprimir mensagens e o operador > para modificar o destino da mensagem.
- clear para limparmos o terminal.
- man para consultar o manual sobre determinado comando.
- setas para cima e para baixo para navegador no histórico de comandos do terminal.

## Remover diretório vazio

````
rmdir projetos-java
````

## Remover diretório com arquivos e pastas

````
rm -r workspace/
````
## Ver conteúdo de nome arquivo com SOMENTE uma letra/número a mais

Pode aparecer mais de um arquivo.

````
cat arquivo?.txt
````

## Ver conteúdo de arquivos que começem com "arquivo"

````
cat arquivo*.txt
````
