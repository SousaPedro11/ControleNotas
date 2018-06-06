# controlenotas
Projeto de controle pessoal de rendimento acad�mico.

Este projeto tem por finalidade inicial, criar uma aplica��o de gerenciamento pessoal de notas e rendimento acad�mico.


UTILIZA��O PELO USU�RIO:

1 - Cadastrar seus dados acad�micos: Nome, Matr�cula, Turma e etc.

2 - Cadastrar o semestre e as disciplinas (informando os dados referentes � disciplina - Nome da disciplina, Professor, N�mero de avalia��es,
notas, etc...)

RETORNO ESPERADO:

1 - C�lculo da conceito de acordo com a m�dia da disciplina.

2 - C�lculo do rendimento semestral de acordo com conceitos e cargas hor�ria das disciplinas do semestre.

2 - C�lculo do CRG de acordo com os conceitos e cargas horaria de todas as disciplinas.


OBS:

Dever� ser implementado o CRUD com conexão ao H2 Database para facilitar a manipula��o dos dados.

Poder� ser implementada uma interface gr�fica para facilitar o uso.


RECURSOS UTILIZADOS

1 - ECLIPSE NEON EE

2 - APACHE MAVEN 3.5.0

3 - ORACLE JAVA JDK 8_144


INSTALA��O DOS RECURSOS UTILIZADOS

Baixe o arquivo zip (nos LINKS EXTERNOS) contendo os programas nas vers�es informadas anteriormente (opcional)

De preferencia crie uma pasta na raiz do sistema para instala��o do Eclipse e do Maven, ex: C:\\Desenvolvimento (opcional)

Instale o Oracle Java SDK no diret�rio de sua prefer�ncia, mas recomendo instalar na padr�o do sistema.

Copie o diret�rio do eclipse para a pasta de sua escolha (recomendo na C:\\Desenvolvimento)

Instale o Apache Maven (Recomendo instalar em C:\\Desenvolvimento

Ap�s instalar os programas devemos configurar o ambiente


CONFIGURA��O DO AMBIENTE

� necess�rio criar vari�veis de sistema e amiente, para ter acesso a essas configura��es:
 Win(janelinha)+Pause Break -> Configura��es Avan�adas do Sistema -> Vari�veis de Ambiente
 
Crie ou edite a Vari�vel de Usu�rio Path adicionando o caminho para \bin do Java JDK (ex: C:\Program Files\Java\jdk1.8.0_144\bin)

Crie a Vari�vel de Sistema JAVA_HOME adicionando o caminho da pasta do Java JDK (ex: C:\Program Files\Java\jdk1.8.0_144)

Crie a Vari�vel de Sistema M2_HOME adicionando o caminho da pasta do Maven (ex: C:\Desnvolvimento\build\apache-maven-3.5.0)

Crie a Vari�vel de Sistema M2 adicionando o valor %M2_HOME%\bin

Crie a Vari�vel de Sistema MAVEN_OPTS adicionando o valor -Xms256m -Xmx521m

Edite a Vari�vel de Sistema Path adicionando as linhas: %JAVA_HOME%\bin e %M2%

Aperte OK nas janelas para validar as configura��es

Agora devemos testar se funcionou

Pressione Win(janelinha)+R , digite cmd e aperte enter para abrir o Prompt

No CMD digite mvn -version e aperte enter

Se o ambiente foi configurado com sucesso, aparecer�: Apache Maven, Maven home, Java version, Java home, Default locale e OS name


LINKS EXTERNOS

https://mega.nz/#!9cBDGS6b!6jh7UylLNfZuHBnpB1ikw9Awi1vJx8plm_4N0GjMoVE (link do zip)

http://www.eclipse.org/downloads/packages/eclipse-ide-java-ee-developers/neon3

http://www.oracle.com/technetwork/pt/java/javase/downloads/jdk8-downloads-2133151.html

https://maven.apache.org/download.cgi

https://mvnrepository.com/

https://www.tutorialspoint.com/maven/maven_environment_setup.htm