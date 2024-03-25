## Atividade - Funções Git e Github

<h2>GIT</h2>
Git é uma ferramenta de versionamento de código, que possui integração com o Github. Ao instalar o git na máquina, é possível usar seus comandos para adicionar, clonar e contribuir com repositórios remotos do Github.

<h2>GITHUB</h2>
Plataforma que visa criar, revisar, participar e atualizar projetos voltados ao desenvolvimento de software. Com suporte a várias linguagens de programação, o Github permite upar, revisar, hospedar e contribuir com projetos desenvolvidos, exibindo no repositório quais tecnologias foram utilizadas. Dessa forma, é possível categorizar projetos por LP usada, facilitando estudos, análises e recrutamento de profissionais. 

Passos para postar um projeto:
1 - Criar uma conta Github
2 - Instalar Git na máquina
3 - Abrir CMD ou Git Bash para executar os comandos
4 - Checar se está instalado:
   	<li>git –version</li>
5 - Ir à pasta no explorador de arquivos, onde está localizado o projeto que deseja upar no Github
6 - Copiar o endereço da pasta
7 - Mudar de diretório no CMD:
    <li>cd url-da-pasta</li>
8 - Configurar email e usuário para commitar
    <li>git config --global user.name "Seu Nome"</li>
        git config --global user.email  "seu@email.com"
9 - Iniciar repositório git 
    <li>git init</li>
    Após esse comando, aparecerá uma pasta .git no diretório do projeto
10 - Adicionar arquivos do diretório para o repositório
    <li>git add nome-do-arquivo  : adiciona um arquivo específico</li>
    <li>git add .                : adiciona todos os arquivos</li>
11 - Fazer commit
    <li>git commit -m “Mensagem de commit”</li>
12 - Adicionar repositório github de destino
    <li>git remote add origin https://github.com/nome-usuario/nome-repositorio.git</li>
	  É possível copiar o link do repositório no github
13 - Enviar para o repositório remoto/Github
    <li>git push origin main</li>
14 - Caso o projeto seja um site: 
    <li>“Settings”</li>
    <li>“Pages”</li>
    <li>Em “Branch” selecione main e “Save”.</li>
	Após isso, o site será hospedado e terá o link de acesso no início de “Pages”, podendo adicioná-lo no README para outras pessoas visualizarem.


