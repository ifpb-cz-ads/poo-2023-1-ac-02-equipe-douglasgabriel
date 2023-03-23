# Equipe DouglasGabriel <h1>
#
## **1°** Explique qual a função da Máquina Virtual Java (JVM).
#
<p>R: O JVM é uma "máquina imaginária" ou programa responsável por carregar e executa aplicativos ou programas escritos em Java em uma máquina real, um computador, por exemplo. O código Java tem uma caracterítica incomum em relação às demais linguagens de programação, onde, o código Java é tanto compilado quanto interpretado, garantindo que haja comunicação com os mais variados dispositivos. E é exatamente nesse contexto, que entra a função da JVM.<br>
<p>Ao ser compilado um código Java em uma máquina, independente do sistema operacional, é gerado um arquivo executável, o bytecode. Esse arquivo, embora já tenha sido compilado, não pode ser lido pela a máquina, sendo necessário uma "tradução" para que a máquina possa compreender o código. É nessa tradução que JVM entra em ação, o JVM interpreta o bytecode e assim garante que máquina possa executar o aplicativo ou programa em Java.<br>
<p>Outra característica peculiar do JVM é que todo sistema operacional tem uma versão do JVM destinada única e exclusivamente para esse sistema, sendo responsável por converter o bytecode de um programa Java, em uma linguagem de máquina exclusiva daquele sistema operacional. Dessa forma, garante-se que várias máquina de diferentes sistemas operacionais, - Desde que tenham o JVM, exclusivo para esse sistema, instalado -, poderá executar um programa em Java, independentemente de onde esse programa tenha sido compilado.   

## **2°** Qual a diferença entre JRE e JDK?
#
R: O ***JRE***, _Java Runtime Environmet_ ou _Ambiente de execução Java_, contém bibiotecas de classe, arquivos de suporte e a _JVM_, ferramentas necessárias para um usuário comum poder executar uma aplicação Java.<br><br> 
O ***JDK***, _Java Development Kit_, é um pacote de software onde se pode desenvolver e compilar arquivos Java, é o pacote destinado aos desenvolvedores de aplicações em Java. Esse pacote é composto pelo ***JRE*** e por algumas ferramentas, como o _JavaLang_ e o _JavaTools_.<br>

## **3°** Crie um programa Java que imprima o seguinte texto “Terminei a primeira aula com um programa Java!”.
#
R: Resposta da questão está no arquivo: _Question3.java_;<br>

## **4°** Compile o programa desenvolvido no exercício anterior. A seguir apague o arquivo .class gerado e tente executar o programa. O que aconteceu?
#
R: Como já esperado, o programa não apresentou resposta, resultando em um erro.<br>
Apresentando como resultado a seguinte mensagem:<br>
>C:\Users\Silva\Desktop\poo-2023-1-ac-02-equipe-douglasgabriel>java Question3<br>
Erro: Não foi possível localizar nem carregar a classe principal Question3<br>
Causada por: java.lang.ClassNotFoundException: Question3<br>

O erro NoClassDefFoundError ocorre quando uma classe existe, mas o ClassLoader do Java não consegue carregá-la ou inicializá-la corretamente.

## **5°** Mude o nome do método “main” para “start”, compile e execute. O que aconteceu?
#
R: O programa compilou, porem ele não foi executado e apresentou o seguinte erro:<br>
>"Error: Main method not found in class Question3, please define the main method as:<br>
>   public static void main(String[] args)<br>
>or a JavaFX application class must extend javafx.application.Application"<br>
Pelo fato do metodo "Main" não existir o programa não foi executado.<br>

## **6°** Crie um programa Java para imprimir duas linhas de texto usando duas linhas de código “System.out”, onde aparecerá o seu nome na primeira linha e na segunda linha aparecerá o time para o qual você torce.
#
R: Resposta da questão está no arquivo: _Question6.java_;<br>

## **7°** Experimente escrever todo o programa anterior em maiúsculo, compile eexecute. O que aconteceu?
#
R: Desta vez o promgrama não chegou a compilar e aprasentou os seguintes erros:<br>
>Question6.java:1: error: class, interface, enum, or record expected<br>
>PUBLIC CLASS QUESTION6{<br>
>^<br>
>Question6.java:4: error: class, interface, enum, or record expected<br>
>                SYSTEM.OUT.PRINTLN("NÃO TORCO PARA NENHUM TIME, POREM MEU COLEGA TORCE PARA O PALMEIRAS");<br>
>                ^<br>
>Question6.java:5: error: class, interface, enum, or record expected<br>
>        }<br>
>        ^<br>
>3 errors<br>
## **8°** Experimente salvar o arquivo com um nome diferente do nome da classe, compile e execute. O que aconteceu?
#
R: Como proposto na questão salvei o arquivo com um nome diferente do nome da classe (original: _Question6.java_ novo: _Question7.java_ ) o programa não foi compliado, consequentemente, não foi executado, e apresemtou o seguinte erro:<br>
>Question7.java:1: error: class Question6 is public, should be declared in a file named Question6.java<br>
>public class Question6{<br>
>       ^<br>
>1 error<br>