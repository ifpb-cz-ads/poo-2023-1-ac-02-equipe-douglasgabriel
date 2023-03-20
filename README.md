# Equipe DouglasGabriel <h1>
#
## **1°** Explique qual a função da Máquina Virtual Java (JVM).
#
<p>R: O JVM é uma "máquina imaginária" ou programa responsável por carregar e executa aplicativos ou programas escritos em Java em uma máquina real, um computador, por exemplo. O código Java tem uma caracterítica incomum em relação às demais linguagens de programação, onde, o código Java é tanto compilado quanto interpretado, garantindo que haja comunicação com os mais variados dispositivos. E é exatamente nesse contexto, que entra a função da JVM.<br>
<p>Ao ser compilado um código Java em uma máquina, independente do sistema operacional, é gerado um arquivo executável, o bytecode. Esse arquivo, embora já tenha sido compilado, não pode ser lido pela a máquina, sendo necessário uma "tradução" para que a máquina possa compreender o código. É nessa tradução que JVM entra em ação, o JVM interpreta o bytecode e assim garante que máquina possa executar o aplicativo ou programa em Java.<br>
<p>Outra característica peculiar do JVM é que todo sistema operacional tem uma versão do JVM destinada única e exclusivamente para esse sistema, sendo responsável por converter o bytecode de um programa Java, em uma linguagem de máquina exclusiva daquele sistema operacional. Dessa forma, garante-se que várias máquina de diferentes sistemas operacionais, - Desde que tenham o JVM, exclusivo para esse sistema, instalado -, poderá executar um programa em Java, independentemente de onde esse programa tenha sido compilado.   

## **2°** Qual a diferença entre JRE e JDK?
#
R: O ***JRE**, _Java Runtime Environmet_ ou _Ambiente de execução Java_, contém bibiotecas de classe, arquivos de suporte e a _JVM_, ferramentas necessárias para um usuário comum poder executar uma aplicação Java.<br> 
O ***JDK***, _Java Development Kit_, é um pacote de software onde se pode desenvolver e compilar arquivos Java, é o pacote destinado aos desenvolvedores de aplicações em Java. Esse pacote é composto pelo ***JRE*** e por algumas ferramentas, como o _JavaLang_ e o _JavaTools_.