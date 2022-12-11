# TR5_535935
implementação de uma heap ordenada em c.

## baixando o codigo.
#### na pagina do repositorio:
- para poder baixar o codigo, tenha certeza de ter o git instalado.
- copie o link do repositorio como mostrado na imagem do link a seguir.  
![copiando o link](https://i.imgur.com/ZqOvIFE.png)
- clique no botão verde "code" e em segida no icone de copiar.
#### no terminal:
- com o git instalado abra um novo terminal.
- no terminal digite, git clone e cole o link copiado.  
![clonando o repositorio](https://i.imgur.com/QvxFi84.png)
- agora você deve ter uma copia do repositorio  na pasta que estava aberta no terminal.
## compilando e executando o codigo.
- salve sua main como main.c e coloque na pasta TR5_535945 no diretorio em que vocẽ clonou o repositorio.
- abra um terminal no diretorio em que vocẽ clonou o repositorio.
- para compilar e executar copie e cole ou digite as seguintes linhas de codigo em seu terminal.
```bash
cd TR5_535935
gcc heap.h TR5_535935.c main.c -o tr5
./tr5
```
- repositorio foi copiado para a pasta TR5_535935, a primeira linha leva o terminal para esse diretorio.
    - se o seu terminal ja estiver aberto nesse diretorio, a linha pode ser ignorada.
- a segunda linha compila o codigo em um arquivo chamado tr5.
    - se for rodar o programa por uma segunda vez, ja estiver no diretorio e não houver alterações no codigo, pode ignorar essa linha.
- a terceira e ultima linha executa o programa.   
*obs: o codigo funciona corretamente mesmo se você apenas copiar e colar tudo de novo toda vez que usar
## ultilização.
- vocẽ precisa criar em sua main.c uma funçao de comparação para os elementos do vetor.
- HEAP_create()
    - cria heap ordenada.
    - recebe como parametros um inteiro que define o tamanho da heap e a função de comparação.
    - devolve um ponteiro para a heap ordenado.
- HEAP_add()
    - adciona elemento ao heap ordenado criado.
    - o elemento ja é adicionado na posição correta.
    - recebe como parametros a heap e o elemento que deseja adicionar.
- HEAP_remove()
    - recebe uma heap criado pela função HEAP_create como parametro.
    - remove o menor elemento da HEAP.
    
*para maior detelhes do funcionamento das funções por favor checar o arquivo heap.h

