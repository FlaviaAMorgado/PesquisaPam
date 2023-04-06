# PesquisaPam
 Tipos de dados do Java, Sintaxe do Looping Java, Condicional Java
 
 Flavia Morgado e Daniel Biondi

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
  
  #### Text
  ##### TextView
  É um elemento de interface que exibe um texto para o usuario. Para permitir que o usuario modifique o texto, consulte EditText.
  
  ##### AutoCompleteAutoView
  Exibe sugestões de conclusões enquanto o usuario digita. A lista de sugestões aparece em um menu suspenso, no qual o usuario pode selecionar uma das sugestões. A lista de sugestões só aparece depois que um numero limite de caracteres determinados é digitado.
  
  ##### MultiAutoComplete
  É um extensão do AutoCompleteAutoView, com a diferença que este mostra sugestões para o substring (uma parte de um string completo, como uma palavra em uma frase).
  
  ##### CheckedTextView
  Uma extensão para TextView que oferece suporte à interface Checkable e exibições. É usado principalmente em um ListView onde queremos mostrar qual item está selecionado ou não.
  ListView: Exibe uma coleção de exibições com rolagem vertical, onde cada exibição é posicionada imediatamente abaixo da exibição anterior na lista.
  
  #### Button
  ##### Button
  É um elemento no qual o usuario pode clicar para executar uma ação.
  
  ##### Chip
  Chips são elementos compactos que representam um atributo, texto, entidade ou ação. Eles permitem que os usuários insiram informações, selecionem uma opção, filtrem conteúdo ou acionem uma ação.
   
  ##### CheckBox
  A caixa de seleção é constituida por opções que possuem dois estados: assinalado e não assinalado.
 
  ##### RadioButton
  São as opções da CheckBox, porém, de forma individual.
 
  ##### Switch
  Um Switch é um widget de alternância de dois estados. Os usuários podem arrastar o botão "polegar" para frente e para trás para selecionar uma das duas opções ou simplesmente tocar no botão para alternar entre as opções.
  
  #### Widgets
  Widgets são como visualizações rapidas de dados e funcionalidades mais importantes de um app. Como por exemplo o ImageView, que é usado para a visualização de     imagens.
	
  #### Layouts
  ##### ConstraintLayout
  Usado para posicionar um widget de forma mais flexivel.
  
  ##### LinearLayout
  Um layout que organiza outras exibições horizontalmente em uma única coluna ou verticalmente em uma única linha.
  
  ##### Frame Layout
  FrameLayout é projetado para bloquear uma área na tela para exibir um único item. 
 
  #### Containers
  ##### RecyclerView
  O RecyclerViews facilita e torna eficiente a exibição de grandes conjutos de dados. o RecyclerViews recicla elementos individuais. Quando um item vai para fora da tela o RecyclerView reutiliza a visualizações para novos itens que aparecerem na tela. Isso melhora muito o desempenho, aperfeiçoando a capacidade e reduzindo o gasto de energia de um app.
  
  ##### Spinner 
  O Spinner é um elemento que ofornece um menu suspenso, com todos os valores disponíveis.
  
  #####  FragmentContainerView
 É uma exibição personalizada que estende o FrameLayout. Mas, ao contrário de outros ViewGroups, aceita apenas exibições de fragmentos. Ele também oferece suporte aos atributos <fragment>, mas oferece mais flexibilidade de transações Fragment e também possui recursos adicionais para coordenar o comportamento do fragmento.
 
 ##### ScrollView
 Permite que a Hierarquia de Visualização colocada dentro dela seja rolada verticalmente (caso seja necessário usar a rolagem horizontal usar 'HorizontalScrollView). 
 
  		java.lang.Object
  		 ↳ android.view.View
 	   		↳ android.view.ViewGroup
 	 	  	   ↳ android.widget.FrameLayout
 	 	 	      ↳ android.widget.ScrollView
			      
 #### Helpers 
 ##### Group 
  Controla a visibilidade de um conjunto de widgets referenciados. A visibilidade do grupo será aplicada aos widgets refenciados. É uma maneira de conveniente de ocultar ou exibir facilmente um conjuntos de widgets sem precisar manter esse conjunti programaticamente.
  
 ##### Barrier
  Semelhante a uma diretriz, uma barreir é uma linha invisível, qual você pode restringir as visualizações. Mas uma barreira não define sua própria posição; em vez disso, a posição da barreira se move com base na posição das visualizações contidas nela. Isso é útil quando você deseja restringir uma visualização a um conjunto de visualizações, em vez de a uma visualização específica.
  Uma barreir faz referência a vários widgets como entrada e cria uma diretriz virtual com base no widget mais extremo do lado especificado. *Por exemplo, uma barreira esquerda se alinhará à esquerda de todas as visualizações referenciadas.*
  
  ##### Guideline
   Permite que vários widgtes sejam posicionados facilmente a partir de uma Guideline ou permitindo o comportamento reativo do layout usando o posicionamento percentual. Uma Guideline/ Diretriz pode ser horizontal ou vertical; Uma guideline pode ser posicionada de três maneiras diferentes: 
   
   - especificando uma distância fixa da esquerda ou da parte superior de um layout  	    (layout_constraintGuide_begin)
   - especificando uma distância fixa da direita ou da parte inferior de um layout 	  (layout_constraintGuide_end)
   - especificando uma porcentagem da largura ou altura de um layout             	 (layout_constraintGuide_percent)
 
 #### Google 
  ##### MapView 
   Exibe um mapa a (com dados obtidos do serviço do Google Maps). Quando está em foco, ele captura teclas e gestos de toque para mover o mapa. Precisa-se adquirir um GoogleMap usando "getMapAsync(OnMapReadyCallback)". O MapView inicializa automaticamente o sistema de mapas e visualizações. 
  
#### Legacy 
 ##### ListView
   Exibe uma coleção de visualizações com rolagem vertical, onde cada visualização está posicionada uma abaixo da outra visualização na lista. Para um desempenho mais moderno, flexível e abordagem para exibir listas, use RecyclerView.
 
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


#### Android Studio
https://developer.android.com/reference/android/widget/ScrollView

https://uware.com.br/como-usar-o-scrollciew-no-android-studio/

https://developer.android.com/reference/androidx/fragment/app/FragmentContainerView

https://developer.android.com/guide/topics/ui/layout/recyclerview?hl=pt-br

https://developer.android.com/guide/topics/ui/controls/spinner?hl=pt-br

https://jafapps.com.br/spinner-android-studio/?doing_wp_cron=1680286310.6129720211029052734375

https://developer.android.com/reference/android/widget/ListView

https://developers.google.com/maps/documentation/android-sdk/reference/com/google/android/libraries/maps/MapView?hl=pt-br

https://developer.android.com/reference/androidx/constraintlayout/widget/Guideline

https://developer.android.com/reference/androidx/constraintlayout/widget/Group

https://stackoverflow.com/questions/47114672/what-is-difference-between-barrier-and-guideline-in-constraint-layout
	
https://abhiandroid.com/ui/checkedtextview
	
https://developer.android.com/reference/android/widget/CheckedTextView
	
https://developer.android.com/reference/android/widget/MultiAutoCompleteTextView
	
https://developer.android.com/reference/android/widget/AutoCompleteTextView
	
https://developer.android.com/reference/android/widget/TextView
	
https://developer.android.com/guide/topics/appwidgets/overview?hl=pt-br
	
https://developer.android.com/reference/android/widget/ImageView
	
https://developer.android.com/reference/androidx/constraintlayout/widget/ConstraintLayout
	
https://developer.android.com/reference/android/widget/FrameLayout
	
https://developer.android.com/reference/android/widget/LinearLayout
	
https://developer.android.com/reference/android/widget/Switch
	
https://developer.android.com/reference/android/widget/ToggleButton
	
https://developer.android.com/reference/android/widget/RadioButton
	
https://developer.android.com/reference/android/widget/CheckBox
	
https://developer.android.com/reference/android/widget/Button#inherited-xml-attributes
	









  
  
  
  
  
  
  
  
  
