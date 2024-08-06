# exercicio01
A - git config --global user.name "conteúdo omitido" #comando usado para identificação do criador do repositório para a finalidade de auditoria

B - git config --global user.email "conteúdo omitido" #comando usado para identificação do criador do repositório para a finalidade de auditoria

C - git init #comando que faz com que o diretório onde estou seja observado pelo git

D - echo 01 > arquivo.txt #comando echo insere o conteúdo 01 dentro do arquivo de texto nomeado como arquivo.txt

E – cat arquivo.txt #comando Linux utilizado para visualizar o conteúdo do arquivo.txt

F – ls -alh #comando Linux utilizado para listar o conteúdo do repositório exercicio01

G - git add . #insere os arquivos contidos dentro do repositório exercicio01 para a área de stage

H - git status #comando exibe que existem dois arquivos observados pelo git e que estão prontos para efetuar commit no repositório

I - git commit -m "git add example - arquivo.txt" #o comando commit vai retirar os arquivos do stage e inserir no repositório exercicio01

J – echo 02 > arquivo.txt #o comando echo insere o conteúdo 02 dentro do arquivo.txt, sobrescrevendo o conteúdo que lá estava gravado, neste exemplo 01

L – git diff arquivo.txt #como sobrescrevemos o conteúdo do arquivo.txt de 01 para 02, porém, sem efetuar o commit, o comando git diff vai exibir a diferença entre eles, neste caso, 01 está contido no repositório e o 02 na área do working dir

M – git add arquivo.txt #vamos inserir este arquivo de texto alterado para a área de stage

N – git status #vai exibir as modificações efetuadas

O – git diff arquivo.txt #neste caso, não haverá diferenças, pois, não há mais o arquivo.txt na área de working dir para comparar, retornando vazio no resultado do comando efetuado, entretanto, se usarmos o git diff –staged, veremos a diferença entre os conteúdos na área de stage

P – echo 03 > arquivo.txt #comando Linux echo para sobrescrever o conteúdo do arquivo.txt para 03

Q – git diff arquivo.txt #como o arquivo.txt teve o seu conteúdo sobrescrito de 02 para 03 no working dir o resultado exibirá o resultado antigo 02 (staging)  e o atual 03 (working) 

R – git restore --stage arquivo.txt #como a alteração estava em stage, é necessário executar o comando com o parâmetro –stage

S – git status #o comando retorna que o arquivo.txt está modificado e está pronto para commit

T – git add arquivo.txt #para adicionar o arquivo modificado para stage

U – git commit -m “git add example 2 – arquivo.txt” #para gerar o commit do arquivo.txt com o conteúdo 03

V – vi .gitignore #para criar o arquivo que o git vai ignorar a observabilidade de quaisquer arquivos que contenham a extensão .txt

X – git add .gitignore #adiciona o arquivo .gitignore na observabilidade do git

Z – git commit -m “git add example 3 – arquivo .gitignore” #efetuamos o commit do arquivo .gitignore  que estava em stage. Após o commit, crie um arquivo de texto intitulado novo.txt e devido a configuração do gitignore, o git deixa de observar qualquer mudança, acréscimo ou deleção em arquivos com extensão .txt

