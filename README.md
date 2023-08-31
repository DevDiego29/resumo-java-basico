# RESUMO JAVA BÁSICO

📖 HISTÓRIA DO JAVA

Interessada em dispositivos eletrônicos inteligentes, a Sun Microsystems financiou uma pesquisa interna com o codinome Green em 1991. O projeto resultou no desenvolvimento de uma linguagem baseada em C e C++ que seu criador, James Gosling, chamou de Oak (carvalho) em homenagem a uma árvore que dava para a janela do seu escritório na Sun.

Descobriu-se mais tarde, que já havia uma linguagem de computador chamada Oak. Quando uma equipe da Sun visitou uma cafeteria local, o nome Java (cidade de origem de um tipo de café importado) foi sugerido e pegou. Mas o projeto Green atravessava algumas dificuldades. O mercado para dispositivos eletrônicos inteligentes destinados ao consumidor final, não estava se desenvolvendo tão rapidamente como a Sun tinha previsto. Pior ainda, um contrato importante pelo qual a Sun competia fora concedido a outra empresa. Então, o projeto estava em risco de cancelamento. Por pura sorte, a World Wide Web e a linguagem HTML explodiu em popularidade em 1993 e as pessoas da Sun viram o imediato potencial de utilizar Java para criar páginas da Web com o chamado conteúdo dinâmico. Isso deu nova vida ao projeto.

Em maio de 1995, a Sun anunciou Java formalmente em uma conferência importante.

Em 2006 a Linguagem Java se tornou Open Source, que tem seu código livre para consultas, pesquisas e personalizações. Java usa a licença GPL (General Public Licence).

Em 2009 a Sun Microsystems foi vendida para a Oracle por US$7,4 bilhões.

Atualmente, a Linguagem Java pode ser encontrada em chips de cartão de crédito, discos de blu-ray, vídeo games (PS4 roda Java), leitores de e-books (Kindle roda Java), smartphones (Android roda Java), TV digital (o padrão Ginga é feito em Java), relógios inteligentes (Moto 360 roda Java) e até mesmo no programa para a Declaração de Imposto de Renda.

📑 CARACTERÍSTICAS DO JAVA

1. **Simples e fácil compreensão.**
2. **Orientada a objetos (OO):**
   + classe e objeto;
   + encapsulamento;
   + abstração;
   + herança;
   + polimorfismo;
3. **Plataforma independente:** Funciona em qualquer plataforma.
4. **Portátil:** os desenvolvedores podem obter o mesmo resultado em qualquer máquina, escrevendo o código apenas uma vez.
5. **Robusta:**
   + Ele usa um gerenciamento de memória forte;
   + Java fornece coleta de lixo automática, pois se preocupa com o consumo de memória;
   + Há tratamento de exceção e mecanismo de verificação de tipo em java, consegue ter algoritmos que conseguem detectar algum tipo de comprometimento na execução de nossas rotinas;
6. **Segura:** Fornece recursos de segurança para os programadores, recursos de criptografia e decriptografia para proteger seus dados contra espionagem e adulteração na Internet.
7. **Interpretada e compilada:** os programas Java são compilados para gerar arquivos de bytecode e a JVM interpreta o arquivo de bytecode durante a execução. 
8. **Multi-thread:** thread é um subprocesso leve e independente de um programa em execução, ou seja, processo, que compartilha recursos. Multi-threading é o nome dado ao processo de vários threads sendo executados simultaneamente, conseguindo nos proporcionar uma alta perfomace de execução.

💻 PLATAFORMAS E COMPONENTES

<div align="center">
<img src=https://github.com/DevDiego29/resumo-java-basico/assets/106121812/aacb6733-025a-41ac-974e-f44711509450 width="700px" />
</div>

Com a linguagem Java, conseguimos desenvolver softwares para várias finalidades de negócio. Seja uma aplicação desktop, uma distribuição web, eletrônicos e dispositivos móveis. Isso graças a distribuição dos recursos da linguagem, através de plataformas bem estruturadas. 

+ **JSE (Java Standard Edition):** É a base da plataforma. Inclui o ambiente de execução e as bibliotecas comuns, sendo direcionado a aplicações para PCs e servidores.

+ **JEE (Java Enterprise Edition):** A edição voltada para o desenvolvimento de aplicações corporativas e para a Web. Possui diversos frameworks, como JPA (Java Persistence API), JSP (Java Server Pages), etc.

+ **JME (Java Micro Edition):** É a edição para o desenvolvimento de aplicações para dispositivos móveis e embarcados.

+ **JFX (Java FX):** JavaFX é uma tecnologia de software que, ao ser combinada com Java, permite a criação e implantação de aplicações de aparência moderna e conteúdo rico de áudio e vídeo.

O Java se subdivide em componentes de desenvolvimento (JDK) e de execução (JRE). Isso significa que, para desenvolver aplicações, é necessário ter instalado o JDK. Mas para apenas iniciar o executável (.jar), simplesmente a instalação da JRE será o suficiente.

JDK (Java Development Kit) - Kit de Desenvolvimento Java:

+ Composto pelo compilador (javac + JVM);
+ Visualizador de applets, bibliotecas de desenvolvimento;
+ Programa para composição de documentação (javadoc);
+ Depurador básico de programas e versão da JRE.

                         JDK = JRE + ferramentas de desenvolvimento

JRE (Java Runtime Environment) - Ambiente de Execução Java: É composta de uma JVM e por um conjunto de bibliotecas, que permite a execução de softwares em Java. 

                                   JRE = JVM + bibliotecas

<div align="center">
<img src=https://github.com/DevDiego29/resumo-java-basico/assets/106121812/0f9e152d-4132-4ef8-b756-d11bb4e832b6 width="700px" />
</div>

O processo de desenvolvimento é muito simples, todo código-fonte escrito em arquivo texto possui extensão .java, este arquivo é compilado com o javac gerando o arquivo .class, o arquivo .class não contém código de máquina nativo, e sim o bytecodes.

A máquina virtual Java (JVM) é um programa que carrega e executa os aplicativos Java, convertendo os bytecodes em código executável de máquina. A JVM é responsável pelo gerenciamento doa aplicativos na medidade que são executados. Graças a JVM, os programas escritos em Java podem funcionar em qualquer plataforma. 

<div align="center">
<img src=https://github.com/DevDiego29/resumo-java-basico/assets/106121812/83e26764-c52e-4aa9-a034-a4c870da7641 width="700px" />
</div>

🦴 ANATOMIA DAS CLASSES 

A escrita de códigos de um programa é feita através da composição de, palavras pré-definidas pela linguagem, com as expressões que utilizamos para determinar o nome do nossos arquivos, classes, atributos e métodos.


<div align="center">
<img src= https://github.com/DevDiego29/resumo-java-basico/assets/106121812/dc9836e2-1654-4b34-9326-0e8cdfed7480 width="700px" />
</div>

+ 99,9% das nossas classes iniciarão com **public class**;
+ Toda classe precisa de nome, exemplo **MinhaClasse**;
+ O nome do arquivo deve ser idêntico ao nome da classe pública;
+ Após o nome, definir o corpo **{ }** , onde iremos compor nossas classes com atributos e métodos.
+ Dentro de uma aplicação, recomenda-se que somente uma classe possua o método main, responsável por iniciar todo o nosso programa.
+ O método main recebe seu nome main, sempre terá a visibilidade public, será difinido como static, não retornará nenhum valor com void e receberá um parâmetro do tipo array de caracteres String[].

Quando se trata de escrever códigos na linguagem Java, é recomendado seguir algumas convenções:

+ **Arquivo .java**: Todo arquivo .java deve começar com letra MAIÚSCULA. Se a palavra for composta, a segunda palavra deve também ser maiúscula, exemplo:
  
                         Calculadora.java CalculadoraCientifica.java
  
+ Nome da classe no arquivo: A classe deve possuir o mesmo nome do arquivo.java.
+ Nome de variável: toda variável deve ser escrita com letra minúscula, porém se a palavra for composta, a primeira letra da segunda palavra deverá ser MAIÚSCULA, exemplo: ano e anoFabricacao. O nome dessa prática para nomear variáveis dessa forma se chama "camelCase".
+ Deve conter apenas letras, _ (underline), $ ou os números de 0 a 9;
+ Deve obrigatoriamente se iniciar por uma letra (preferencialmente), _ ou $, jamais com número;
+ Deve iniciar com uma letra minúscula;
+ Não pode conter espaços;
+ Não podemos usar palavras-chave da linguagem;
+ O nome deve ser único dentro de um escopo.

Para declarar variáveis e métodos devemos seguir a estrutura:

                     tipo NomeDaVariavel = atribuição de valor (opcional em alguns casos);
                            Exemplo: int idade = 20; double salario = 2700;
                     TipoRetorno NomeObjetivoInfinitivo Parametro(s)
                            Exemplo: int somar(int numeroUm, int numeroDois){}

Uma variável deve ser clara, sem abreviações ou definição sem sentido, uma variável é sempre no singular, exceto quando se referir a um array ou coleção.

Os métodos deverão ser nomeados como verbos, através de uma mistura de letras minúsculas e maiúsculas. Em princípio todas as letras que compõem o nome devem ser mantidas em minúsculo, com exceção da primeira letra de cada palavra composta, a partir da segunda palavra.

🔍 REFERÊNCIAS

+ Um pouco mais da história sobre Java no canal do [Guanabara Curso em Vídeo](https://www.youtube.com/watch?v=sTX0UEplF54&list=PLHz_AreHm4dkI2ZdjTwZA4mPMxWTfNSpR)

+ Introdução às plataformas JAVA [DEVMEDIA](https://www.devmedia.com.br/introducao-as-plataformas-java/29544)

+ Bibioteca JAVA (https://docs.oracle.com/javase/8/docs/api/)

