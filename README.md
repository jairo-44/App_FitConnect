Projeto Integrador 2ª Entrega

Faculdade SENAC

Integrantes da equipe:

- Bianca Silva de Oliveira
- Cicero Pereira Lira
- Eduardo Motta Justo
- Giovany Dal Bello
- Guilherme Lima Rett
- Jairo Souza dos Santos

Orientadores: Débora Richter, Evandro Carlos Teruel

_______________________________________________________________________________________________________________

Aplicativo: FitConnect

Aplicativo para pessoas que necessitam de programas de emagrecimento, com orientação nutricional e atividade física. O FitConnect, após analisar os dados prestados pelo usuário, indicará uma gama de profissionais da área de nutrição e educação física, facilitando a conectividade (pessoas com demanda por saúde/desenvolvimento físico e profissionais da área), promovendo facilitação para o usuário encontrar o profissional adequado ao seu caso.

_______________________________________________________________________________________________________________

Ferramentas utilizadas

-Back-And : PHP e MYSQL (Xamp)
-Front-And: React_native, JavaScript e CSS
-Banco de dados: MySQL (Xamp/Apache)

_______________________________________________________________________________________________________________

Instruções de utilização

O FITConnect é um sistema que poderá ser acessado por diversos dispositivos móveis como smartphones e tablets. Bastando para tanto, baixar o apk e instalar. Caso não tenha um login, poderá cadastrar-se, e então logar no sistema.

O aluno será direcionado para sua página onde através de links terá acesso a “Área do Aluno”, “Profissionais indicados”, “Pagamentos”, “Seu perfil/desempenho” e “Aluguel de Bicicletas”.

Já profissional terá acesso a sua área com alunos agendados, sendo listados por data e horários, bem como poderá também gerenciar os treinos/consultas dos alunos/pacientes.

O Sistema está integrado ao banco de dados “fitconnect.sql” que se encontra na pasta "instruções" no google drive "https://drive.google.com/drive/folders/1B1EhiJn3v9jcujBaDsPlki83sYcsABv4?usp=drive_link".

Formulários integrados ao banco de dados: Cadastro do aluno; Cadastro do profissional, Login, Aluguem de bicicletas e Pagamentos.

Link: https://github.com/jairo-44/App_FitConnect


Youtube O vídeo resumido demonstrando do sistema em funcionamento está disponível no Link: https://youtu.be/visg7pEB3c0

_______________________________________________________________________________________________________________

Instruções de instalação:

-Instale o React Native e Xampo em sua máquina.
-Baixe a pasta PI do diretório compartilhado no Google Drive (https://drive.google.com/drive/folders/1B1EhiJn3v9jcujBaDsPlki83sYcsABv4?usp=drive_link)
-Baixe o banco de dados "fitconnect.sql" compartilhado no mesmo link (https://drive.google.com/drive/folders/1B1EhiJn3v9jcujBaDsPlki83sYcsABv4?usp=drive_link) 
-Clone o projeto para sua máquina (git@github.com:jairo-44/App_FitConnect.git) ao entrar nela pelo link https://github.com/jairo-44/App_FitConnect 


_______________________________________________________________________________________________________________

Como clonar o projeto GitHub para sua máquina:

- Entre no projeto “App_FitConnect” (Link: https://github.com/jairo-44/App_FitConnect)
- Clique no botão verde “Code” 
- Copie o link 
- Crie uma pasta no seu computador, dê-lhe um nome 
- Abra a pasta e com o botão direito do mouse clique em “Open Git Bash Here” 
- digite “git clone coleOLinkAqui” + enter 
- Caso alguma alteração tenha sido feita diretamente no repositório, e queira atualizar o arquivo do seu PC, basta • Abra a pasta e com o botão direito do mouse clique em “Open Git Bash Here” • Digite “git pull” + enter


_______________________________________________________________________________________________________________

Importar banco de dados 
- Instale o Xamp (https://www.apachefriends.org/pt_br/index.html) 
- Crie um novo banco de dados, descompacte e importer o aquivo fitconnect.sql 
- Vá ao local de instalação do Xamp (geralmente é em c:), abra a pasta htdocs crie uma pasta com nome pasta fitConnect dentro dela, em "fitConnect" criada, copie e cole todas as apis que estão compartilhadas no Google Drive (https://drive.google.com/drive/folders/1B1EhiJn3v9jcujBaDsPlki83sYcsABv4?usp=drive_link). São essas APIs que fazem a conexão do app com banco de dados. 
- Na mesma pasta fitconnect que está em htdocs crie uma pasta com o nome 'uploads' é pra lá que as imagens salvas irão.

- Observações: nos códigos dos formulários CadastroAluno, CadastroProf e login é necessário que nas URLs (http://192.168.1.9/fitConnect/addAluno.php) sejá colocado o IP da sua máquina Exemplo: (http://seu_IP/fitConnect/addAluno.php) para todas as URLs que chamam alguma API. São essas APIs que fazem a conexão do app com banco de dados. 

- À medida que colocar o projeto pra roda, o próprio react-native poderá gerar erros solicitando a instalação de dependências necessárias.

- O comando para iniciar o projeto em emuladores ou no smartphone é: npm start (na pasta "fitConnect" clonadada projeto). 


--------------------------------------------------
Todas as pessoas ou empresas que acessarem este projeto tem autorização para colaborar, copiar e alterar estes códigos para fins didáticos.

