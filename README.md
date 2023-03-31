# PesquisaPam
 Tipos de dados do Java, Sintaxe do Looping Java, Condicional Java

# Tipos de Dados:

#### Dados Primitivos
 Os dados primitivos funcionam da seguinte maneira; quando se declara uma variável de um tipo primitivo não será possível colocar outro tipo de dado nessa variável. Por esemplo, se você colocar uma variável como int, você só poderá colocar valores int nessa variável.
 
No Java nós temos 8 tipos de dados primitivos. São esses:
  -	byte;
  -	short;
  -	int;
  -	long;
  -	boolean;
  -	char;
  -	float; 
  -	double.
 
 E podemos dividi-los em 2 grupos:
  -	Boolean;
  -	Numérico;

##### Boolean 
Temos apenas 2 valores 
  -	True;
  -	False;

##### Numérico 
Temos 2 subdivisões 
  -	Integrais;
  -	Ponto Flutuante;
 ##### Integrais 
  -	byte - possui 1 byte de informação ou 8 bits;
  -	short - possui 2 bytes de informação ou 16 bits;
  -	int - possui 4 bytes de informação ou 32 bits;
  -	long - possui 8 bytes de informação ou 64 bits.
  -	char - Possui 2 bytes de informação ou 16 bits. Serve para a armazenagem de dados alfanuméricos. Também pode ser usado como um dado inteiro com valores na faixa entre 0 e 65535. (Apesar do tipo char receber caracteres ele também pode receber valores numéricos)


##### Ponto Flutuante
  -	Float - possui 4 bytes de informação ou 32 bits;
  -	Double - possui 8 bytes de informação ou 64 bits.
  
#### Dados de Referência
 São utilizados para armazenar as localizações dos objetos da memória do computador. E dentro desses obejtos podem existir variáveis de instância e métodos. 
Quando um objeto é atribuído para uma variável, aquela variável está na verdade associada a uma referência do objeto, e não ao objeto em si. Essa referência é o endereço de memória em que aquele objeto está localizado.

##### Tipos de dados: 
  - Arrays; - Permite armazenar valores de um meso tipo em alocações de memória contínuas. São indenfrificados por índice de números inteiros, que começa do 0 e vai até n-1, onde *n* é o número de elementos disponíveis. Elementos do array devem conter o mesmo tipo de dados. o Array é um tipo de dado de referência pois ele é uma classe do java - java.lang.Object 
  - Strings; - Comporta até 2 bilhões de caracteres; Armazena uma sequência de caracteres, um objeto String é imutável, o que significa que o texto que ele carrega nunca é alterado.
  - Outros tipos tipo de classe instanciável 
  
  # Condicional
  
  ### Sintaxes de Condicional
  
  A condicional do Java é bem parecida com a que já usamos no c# e a sintaxe da condicional é a mesma.
  -If e Else;
  
  #### Estrutura da condional 
 	 ***if( condição ) {
	    // ação se a condição for verdadeira
 	 }
 	 else{
    	// ação se a condição for falsa
  	}***
  
  Vamos aplicar em um exemplo, com códigos! Veja a seguir:
  
   - Programa para verificar se o usuário é maior de idade
   
 		***public class Teste{
	   	     public static void main(String Args[]){
		     	 int idade = 19;
		        	if (idade >= 18 ){
			          System.out.println("Você é maior de idade!");
		       		 }
          			else{
			          System.out.println("Você é nem pode dirigir ainda :)");
		         }
     		     }
		 }***
   
 ### Condicional Encadeado
   
double livroLinux;
double livroBancosDados;
livroLinux = 78.60;
livroBancosDados = 56.75;

	double total = livroLinux + livroBancosDados;
	System.out.println("O preço total é " + total );

         if (total < 120.00 ) {
          System.out.println("O preço está bom!");
	}
   	else if (total > 180.00 ){
    	System.out.println("Livros muito caros!");
	}	
	else {
    	System.out.println("Preço razoável.");
	}
   
   
   
  # Looping
  ### Sintaxes de Looping
  Os looping's são parametros usados para fazer com que uma parte do pragrama seja executada até determinado ponto, que é definido por um condição.
  Temos 3 tipos de looping, esses são:
  - While;
  - Do While;
  - For;
  
  ##### While
  O Loop While funciona de forma booleana, enquanto tal condição especifica existir, ele continua sendo executado.
  Sintaxe:
  while (condição) {
  // código a ser executado
  }
  
  ##### Do While
  A diferença entre esse loop e o loop anterior, é que esse executa pelo menos uma vez o programa, antes de checar a condição, já que a sintaxe "while" está no final     do programa, como um fechamento do "Do".
  Sintaxe:
  do{
  // código a ser executado
  } while (condição);
  
  ##### For
  O For é tecnicamente uma forma compacta do "Do While", já que todo o funcionamento se encontra no inicio da sintaxe.
  Sintaxe:
  for (inicialização; condição; incr / decr) {
  // código a ser executado
  }
  
  Sempre lembrando que cada um atende certa necessidade, então sempre analise a situação para saber qual usar.
  
  # Tipos de elementos do Android Studio 
  
  #### Containers
  ###### - RecyclerView
  O RecyclerViews facilita e torna eficiente a exibição de grandes conjutos de dados. o RecyclerViews recicla elementos individuais. Quando um item vai para fora da tela o RecyclerView reutiliza a visualizações para novos itens que aparecerem na tela. Isso melhora muito o desempenho, aperfeiçoando a capacidade e reduzindo o gasto de energia de um app.
  
  ###### - Spinner 
  O Spinner é um elemento que ofornece um menu suspenso, com todos os valores disponíveis.
  
  ###### - FragmentContainerView
 É uma exibição personalizada que estende o FrameLayout. Mas, ao contrário de outros ViewGroups, aceita apenas exibições de fragmentos. Ele também oferece suporte aos atributos <fragment>, mas oferece mais flexibilidade de transações Fragment e também possui recursos adicionais para coordenar o comportamento do fragmento.
 
 ###### - ScrollView
 Permite que a Hierarquia de Visualização colocada dentro dela seja rolada verticalmente (caso seja necessário usar a rolagem horizontal usar 'HorizontalScrollView). 
 
  
## Referências:
https://tdsa2014.blogspot.com/2014/05/tipos-de-dados-primitivos-e-de.html

https://www.javatpoint.com/pt/tipo-de-dado-em-java#:~:text=Existem%20dois%20tipos%20de%20dados,Incluem%20classes%2C%20interfaces%20e%20arrays

https://www.academicotech.com/post/tipos-de-dados-em-java

https://www.dm.ufscar.br/~waldeck/curso/java/part22.html

https://blog.grancursosonline.com.br/os-tipos-primitivos-da-linguagem-java/

https://www.devmedia.com.br/tipos-de-dados-por-valor-e-por-referencia-em-java/25293

#### Condicional
https://www.computersciencemaster.com.br/estruturas-condicionais-if-else-lacos-de-repeticao-while-for-em-java/

https://www.devmedia.com.br/estruturas-condicionais-em-java/21135

http://www.bosontreinamentos.com.br/java/estrutura-de-decisao-condicional-if-em-java/


#### Looping
https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjPhMrckoL-AhWoBLkGHZpIDeoQFnoECAkQAQ&url=https%3A%2F%2Fwww.javatpoint.com%2Fpt%2Floops-em-java&usg=AOvVaw1iEFAkqgCXLkm3mP8MXeEB

https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjPhMrckoL-AhWoBLkGHZpIDeoQFnoECAoQAQ&url=https%3A%2F%2Fblog.betrybe.com%2Ffor-java%2F&usg=AOvVaw3MyVi4bGhhoyVkz5FqVY2Q

https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjPhMrckoL-AhWoBLkGHZpIDeoQFnoECDUQAQ&url=https%3A%2F%2Fwww.techiedelight.com%2Fpt%2Fwhile-loop-do-while-loop-java%2F&usg=AOvVaw2kvp-UC7SnS0p06L8afE2Z




  
  
  
  
  
  
  
  
  
