# Projeto realizado no primeiro semestre de banco de dados. Fatec

PLIINB
Projeto Integrador - FATEC 2020 1º Sem - Banco de Dados

Equipe 💻
Dev Team
Isidro A. A. Jr. https://www.linkedin.com/in/isidro-augusto-4671661a4/
Israel Zanardi https://www.linkedin.com/in/israel-zanardi-916a57a7/
Lucas Rodrigues https://www.linkedin.com/in/lucas-monteiro-56585117b
Pedro Garcia https://www.linkedin.com/in/pedro-garcia-b41696195/
Master
Bruno G. D. Faria https://www.linkedin.com/in/bruno-dionisio-6134451a7/
O que é o PLIINB? 🔍
Assistente Pessoal Virtual vinculado à API Google Calendar, no qual o usuário usará comandos de voz para acessar a Agenda Google através da API, executar os comandos de consultar, editar e visualizar compromissos da agenda. Além de consumir API do sexto semestre.

Lista de comandos possíveis:
Consultar agenda;
Ler compromissos do dia;
Incluir compromisso;
Editar compromisso;
Excluir compromisso;
Fechar agenda.
Ferramentas e Linguagens 🛠️
Ferramentas utilizadas para o desenvolvimento do projeto:

Python 3.6 (com Flask)

Spyder (IDE)

Agenda do Google (API Google Calendar)

Trello

StackEdit

Github <https://github.com/BrunoGDF/PLIINB/

Criando o PLIINB
Assistente Pessoal Virtual

Pré-requisitos
Instalar os softwares:
-   Python 3.6 (com Flask); 
    
-   Spyder (IDE);
    
-   Agenda do Google (API Google Calendar);
    
-   Gerenciamento de pacotes pip;

-   Dispositivos de áudio e voz (microfone e fones de ouvido/alto-falantes);

-   Possuir acesso a internet;

-   Browser (Google Chrome);

-   Uma conta do Google com o Google Agenda ativado.


Bibliotecas
Bibliotecas necessárias para obter um ambiente de desenvolvimento em execução.

Instalar as bibliotecas:

pip install google-api-python-client
pip install google-auth-oauthlib
pip install google-auth
pip install SpeechRecognition
pip install gTTS
pip install PyAudio
Execução do Código
O código do PLIINB é composto por funções, a primeira função tem o papel de reconhecimento de voz. Código do reconhecimento de voz: https://github.com/BrunoGDF/PLIINB/blob/master/Entrega_2/audio.py

Flask: https://github.com/BrunoGDF/PLIINB/blob/Sprint03/Ol%C3%A1%20mundo.py

Reconhecimento de voz
Iniciado o reconhecimento de voz, é identificado o idioma (Português), ao qual armazena o som em uma variável (retornoAudio).

Autenticação de Usuário
A próxima função faz a autenticação das credênciais direcionando o usuário para dar as permissões necessárias. Autenticação do usuário na conta google através da API com login e senha.

LOGIN:           @gmail.com
SENHA: 
Dadas as premissões, o código possui a função eventos que vai identificar a existência ou não de eventos na agenda.

Acesso à agenda
As funções (eventos) e (day) presentes no código possuem a função de procurar por palavras chave em uma frase dita ao reconhecimento e retornar ao usuário os compromissos daquele dia. Por exemplo, ao falar: "Eventos no dia 10 de Junho", ele identifica compromissos na data ou avisa que não há eventos no dia.

A função (editarEventos) possibilita ao usuário fazer alterações em um evento, seja no título ou data do compromisso.

Frameworks
Utilizamos o Python 3.6 (com Flask) após uma pesquisa entre os frameworks Justpy e o Flask, para saber qual se adequaria melhor ao projeto, onde foi decidido que seria utilizado o Flask pois o justpy apresentou erro ao rodar.

Próximos passos
 Tela inicial do programa;

 Comando para incluir, editar e excluir compromissos na agenda.

 Comando para fechamento da agenda.

Entrega 3
De acordo com o planejado para a entrega 3, o grupo atingiu as metas e obteve os seguintes avanços:

Interação do Python com Google Calender API através da autenticação com json-https://github.com/BrunoGDF/PLIINB/blob/Sprint03/reconhecimentoDeVoz.py

Interação do Python com interface web(Flask)- https://github.com/BrunoGDF/PLIINB/blob/Sprint03/Ol%C3%A1%20mundo.py

Entrega 4
Conforme foi definido os próximos passos para entrega 4, foram encontradas algumas dificuldades, porém sobressaiu o sucesso da equipe em grandes avanços com êxitos onde o codigo executa as seguintes funções:

Comando para abrir agenda. ✔️

Comando para criar compromissos. ✔️

Comando para fechamento da agenda. ✔️

Comando para editar compromissos na agenda. (codigo pronto, porem, finalizando últimas correções visando qualidade ao cliente) 🛠

Acesso aos comandos realizados: https://github.com/BrunoGDF/PLIINB/tree/Sprint04

Vídeo de apresentação está contido no arquivo rar: https://github.com/BrunoGDF/PLIINB/blob/master/Video_Apresentacao_Entrega4.rar

Entrega 5
Nesta entrega realizamos uma interação de voz com a API desenvolvida pelos alunos do 6º semestre voltada a pesquisa de filmes, foi concluído também o comando editar, ele possibilita a consulta e a alteração de um compromisso na agenda. Sendo assim, o objetivo final da entrega de 5 comandos teve sucesso.

Vídeo de apresentação: https://drive.google.com/file/d/1haTgoNxlE3Bz-iWjvClHnNTCGq0rlkxC/view?usp=sharing

Entrega final
Conforme planejado para a última entrega, aperfeiçoamos a consumação da API relacionada a filmes desenvolvida pelo 6º semestre e corrigimos a falha do horário que estava presente no código.

Vídeo de apresentação: https://drive.google.com/file/d/1l-HaBL_MZ-HcfA4BPJVcnjzqV7i7E-4z/view?usp=sharing
