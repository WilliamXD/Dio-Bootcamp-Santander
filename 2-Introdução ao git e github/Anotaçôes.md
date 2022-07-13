# Importância do git/github.

GitHub é uma ferramenta essencial para as organizações. Por meio desse sistema, torna-se possível fazer a divulgação e 
também fica mais fácil efetuar o compartilhamento entre diferentes ferramentas.
Projetos realizados em equipes que geralmente trabalham em paralelo.
O Git é utilizado de forma tão ampla que ter conhecimento sobre ele é praticamente obrigatório e também é uma sistema de controle de versão


## Comandos Básicos do terminal.

**cls:** Limpa o terminal.
**ls:** exibe uma lista de arquivos dentro da pasta atual.
**cd /:** leva para a base do diretório.
**cd..:** volta para a pasta anterior.
**>cd + nome da pasta:** avança para a pasta designada.
**dir:** mostra uma lista de diretórios na pasta onde se esta situado.
**tecla TAB:** autocompleta o nome de uma pasta no diretório em que se encontra.
**mkdir:** criar uma pasta.
**rmdir + nome da pasta + /S + /Q:** remove a pasta e tudo que a nela.
**echo:** somente retorna o que se digitou.
**echo + palavra > palavra.txt:** se cria um aquivo em txt.
**del + nome da pasta:** deleta tudo que tem dentro das pasta especificada.

## Estados do Git.

**Untracked** é o estado onde o arquivo ainda não foi 'rastreado'.

**Unmodified** é o estado onde o arquivo não sofreu alterações em relação a sua referência.

**Modified** é o estado onde o arquivo sofreu alterações em relação a sua referência.

**Staged** é o estado onde o arquivo já foi endereçado e aguarda ser transferido ao repositório.

[![Estagios do git]](https://i.stack.imgur.com/QaeAZ.png)

## Comandos Básicos do Git.

#####Git init
Isso cria um novo subdiretório chamado .git que contem todos os arquivos necessários de seu repositório — um esqueleto de repositório Git.
Neste ponto, nada em seu projeto é monitorado.

#####Git clone
Você clona um repositório com git clone [url].
Exemplo.: https://github.com/WilliamXD/Dio-Bootcamp-Santander.git

#####Git add
Este comando adiciona os arquivos solicitados ao ambiente de stage, é uma forma de dizer para o git que você deseja que as modificações
daquele arquivo sejam gravadas na próxima remessa. Um exemplo de utilização é: git add. onde o ponto representa todos os arquivos na pasta.

#####Git push
Por fim precisamos subir essas modificações no nosso repositório remoto, para isso basta utilizar o comando git push e, se já estiver tudo
devidamente configurado, os arquivos serão salvos no repositório remoto correspondente ao seu repositório local!

#####Git status
Este comando permite ver quais arquivos estão sendo “rastreados” pelo git e quais modificações já foram enviadas para o stage. É bem útil
para quando se tem dúvidas sobre o que está sendo enviado.

#####Git branch
É usado para verificar todas as branches presentes no repositório. Ao utilizar a flag -r no final do comando é possível ver todas as branches
presentes no repositório remoto e se você quiser criar uma nova branch basta utilizar este comando: git branch <branch_name>.

#####Git checkout
É o comando utilizado para trocar de branch passando o nome da branch destino no final do comando. Caso a flag -b seja colocada após o
“checkout” é possível criar a branch em questão e já trocar para esta imediatamente.

#####Git commit
Agora fazemos a gravação em si das modificações, desta forma criamos um snapshot do estado atual do nosso projeto. Uma forma muito usada é
o git commit -m “descrição das atualizações do projeto” onde o -m é uma flag que aponta para a mensagem de descrição.
