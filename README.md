    O Git e o GitHub são ferramentas essenciais para qualquer profissional que deseja trabalhar com 
programação. Quando falamos em versionamento de códigos e colaboração e postagem de projetos
as ferramentas citadas são referência.

    O Git é uma ferramenta de versionamento de código, ou seja, nela voçê registra todas as mudanças 
e atualizações realizadas durante um projeto,  permitindo voltar para uma versão anterior já funcional
ou criar diferentes ramificações do seu código, as chamadas "branchs".

    Já o GitHub é uma plataforma Online que utiliza e facilita o uso do Git. Nela você cria repositórios 
para seus projetos, esses armazenados em nuvem. Permite também compartilhar projetos com outros usuários, tornando
essa a principal e mais utilizada plataforma para colaboração entre programadores.

    Para colocar seu projeto no GitHub, o Primeiro passo é criar um repositório na plataforma. Tendo uma conta no site
basta ir em seu perfil e criar um repositório novo. Com isso feito, ao entrar na pasta onde está seu projeto em seu computador
abra-o com o Git, e depois siga os seguintes comandos:

1. git init
Comando que inicializa o git no diretório da pasta onde está localizado seu projeto.

2. git add NomeArquivo.extensao ou Git add .
Adiciona o Arquivo especifico para a area onde será commitado ou adiciona todos os arquivos da pasta para a area de commit

3. git commit -m "Nome do commit"
Registra as mudancas realizadas, os chamados commits 

Com esses tres primeiros passos seu repositório local está criado em sua máquina. Agora ele deve ser conectado ao seu repositório 
no GitHub. Para isso faça os seguintes comandos:

4. git branch -M main
Renomeia a brain de Master para main

5. git remote add origin (link do repositorio do GitHub)
Cria uma conexao entre o repositorio local com o repositório do GitHub

6. git push -u origin main
Puxa os arquivos automaticamente para o Github.

Para commits futuros basicamente basta repetir os passos dos comandos add e commit e depois executar o comando:

git push origin main

Assim todas as atualizações serão feitas no GitHubx