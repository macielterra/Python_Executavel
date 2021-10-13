CRIAR ARQUIVO EXECUTÁVEL NO PYTHON
Como criar arquivo executável no Python para que você possa executar seus códigos de forma mais eficiente!
# Resumo
•	Bibliotecas necessárias para utilização do código;
•	Utilização do ambiente virtual (com link para o passo a passo);
•	Criação do arquivo executável.
Arquivo Executável no Python
Temos duas ações, a análise de dados e em seguida o envio desses dados já organizados por e-mail.
Esse envio de e-mail é feito através da integração com Outlook utilizando a biblioteca win32. E claro, vamos utilizar outra biblioteca no Python que já deve ter ouvido falar como biblioteca pandas que é excelente para análise e tratamento de dados.
Se for a primeira vez que estiver utilizando o Python precisa instalar as seguintes bibliotecas:  pandas, pywin32 e openpyxl.
Utilize ambiente virtual na criação do arquivo executável é importante, pois vai deixar o seu arquivo muito mais leve e o processo para essa ação fica mais rápido!
O primeiro passo é instalar o pyinstaller, então pode escrever no seu terminal pip install pyinstaller.
Em seguida vamos utilizar o seguinte código no terminal: pyinstaller –onefile Nomedoarquivo.py
Onde esse Nomedoarquivo.py é o nome do nosso arquivo que será criado o executável.
Isso diz para o programa que vamos transformar os nossos arquivos em uma única coisa. Você pode colocar o parâmetro -w também, mas só se tiver uma tela de interação com o usuário.
OBS: É importante ressaltar que esse processo para transformar em um arquivo executável é um pouco demorado e vai depender do tamanho do seu código e das bibliotecas que vai passar. Por isso é importante utilizar o ambiente virtual para que tenha somente o que precisa e não leve diversas bibliotecas extras sem necessidade.

Pastas criadas após a criação do executável

Você vai notar que após o procedimento serão criadas algumas pastas e o nosso executável está dentro da pasta dist.
Então basta pegar esse executável e jogar para onde temos o arquivo de vendas, pois o nosso código precisa desse arquivo para funcionar..
Pronto, agora você tem o seu arquivo executável. Pode então colocar ele em outra pasta junto com a base de dados, ou até enviar para outra pessoa e você vai ver que ele funciona normalmente
 
E-mail recebido através do arquivo executável.
