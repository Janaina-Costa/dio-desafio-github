<h1 style="color:#01A9DB" >Tipos de Funções</h1> 

<h2 style= "color:#FE2E64; text-align:center">#Function Declaration# 	</h2>

<p style= "font-style: italic">Função clássica cujo padrão de escrita é a palavra 'function' + um nome seguido de '()'</p>

<h4 style = "color: #848484">1- Sem parâmetro && Sem retorno</h4>

​    	<span style = "color: #FE2EF7">function </span><span style = "color:#00BFFF">sayHello()</span>{
​    		<span style = "color: #8258FA">console. <span style= "color:#64FE2E">log</span>('Olá!')</span>
​    }
​	<span style = "color:#00BFFF">sayHello()</span> 

​	<span style= "color:#BDBDBD">//Olá!</span>

<h4 style = "color: #848484">2- Com parâmetro && Sem retorno</h4>

<span style = "color: #FE2EF7">function </span><span style = "color:#00BFFF">meuPet(<span style="color:#FF8000">nome</span>)</span>{
    		<span style = "color: #8258FA">console</span>. <span style= "color:#64FE2E">log</span>('Minha gatinha se chama' + <span style="color:#FF8000">nome </span> )
    }
	<span style = "color:#00BFFF">meuPet()</span> 

​	<span style= "color:#BDBDBD">//Minha gatinha se chama Miah.</span>


<h4 style = "color: #848484">3- Sem parâmetro && Com retorno</h4>

​    <span style = "color: #FE2EF7">function </span><span style = "color:#00BFFF">saudacao()</span>{
​    		<span style = "color: #FE2EF7">return</span>('Olá, bom dia!')
​    }
​	<span style = "color: #8258FA">console</span>. <span style= "color:#64FE2E">log</span> (<span style = "color:#00BFFF">saudacao()</span>)

​	<span style= "color:#BDBDBD">//Olá, bom dia!</span>



<h4 style = "color: #848484">4- Com parâmetro && Com retorno</h4>

<span style = "color: #FE2EF7">function </span><span style = "color:#00BFFF">soma(<span style="color:#FF8000">a,b</span>)</span>{
    		<span style = "color: #FE2EF7">return</span> <span style="color:#FF8000">a + b</span>
    }
	<span style = "color: #8258FA">console</span>. <span style= "color:#64FE2E">log</span> ('Soma = ' + <span style = "color:#00BFFF">soma(2,5)</span>)

​	<span style= "color:#BDBDBD">//Soma = 7.</span>

<h2 style= "color:#FE2E64; text-align:center">#Function Expression#</h2>

<p style= "font-style: italic">Função que é atribuída a uma variável. Qualquer variável pode receber função como atributo</p>

<span style = "color: #8258FA">const</span> <span style = "color:#00BFFF">soma</span> = <span style = "color: #FE2EF7">function </span><span style = "color:#00BFFF">soma(<span style="color:#FF8000">a,b</span>)</span>{
    		<span style = "color: #FE2EF7">return</span> <span style="color:#FF8000">a + b</span>
    }
	<span style = "color: #8258FA">console</span>. <span style= "color:#64FE2E">log</span> ('Soma = ' + <span style = "color:#00BFFF">soma(2,5)</span>)

​	<span style= "color:#BDBDBD">//Soma = 7.</span>



<h2 style= "color:#FE2E64; text-align:center">#Arrow Function#</h2>

<p style= "font-style: italic">Muito mais enxuta, sua sintaxe se resume à atribuição de função anônima a uma variável. A palavra 'function' é substituiída pelo simbolo '=>' </p>

<span style = "color: #8258FA">const</span> <span style = "color:#00BFFF">incrementar</span> = <span style = "color:#00BFFF">(<span style="color:#FF8000">n</span>)</span> => {
    		<span style = "color: #FE2EF7">return</span> <span style="color:#FF8000">n + 1</span>
    }
	<span style = "color: #8258FA">console</span>. <span style= "color:#64FE2E">log</span> (<span style = "color:#00BFFF">incrementar(8)</span>)

​	<span style= "color:#BDBDBD">//9.</span>

<p style= "font-style: italic">Achou enxuta???? pode ficar ainda melhor!!! </p>

<span style = "color: #8258FA">const</span> <span style = "color:#00BFFF">incrementar</span> = <span style = "color:#00BFFF"><span style="color:#FF8000">n</span></span> =>  <span style="color:#FF8000">n + 1</span>
    }

<p style= "font-style: italic">As chaves podem ser suprimidas(desde que não haja mais de um argumento no bloco de código ), neste caso não se usa a palavra return. Quando houver apenas um parâmetro os parenteses também são facultativos. </p>

<h2 style= "color:#FE2E64; text-align:center">#Function Factory#</h2>

<p style= "font-style: italic">Vamos criar objetos?? &#128540;</p>

<span style = "color: #FE2EF7">function </span><span style = "color:#00BFFF">criarPessoa()</span>{
    		<span style = "color: #FE2EF7">return</span>{

​						<span style = "color: #8258FA">nome:</span>	"Maria",

​						<span style = "color: #8258FA">sobrenome:</span>	"Salazar",

​						<span style = "color: #8258FA">idade:</span>	"53"							

}
    }
	<span style = "color: #8258FA">console</span>. <span style= "color:#64FE2E">log</span> (<span style = "color:#00BFFF">criarPessoa()</span>)

​	<span style= "color:#BDBDBD">//{nome: Maria, sobrenome: Salazar, idade: 53}</span>





