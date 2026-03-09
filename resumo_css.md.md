**resumo\_css.md**



**O que é CSS e para que ele serve**



O CSS (Cascading Style Sheets) é uma linguagem utilizada para estilizar páginas web. Enquanto o HTML é responsável pela estrutura da página (títulos, parágrafos, imagens, etc.), o CSS é responsável pela aparência visual, como cores, tamanhos, espaçamentos e organização dos elementos.



Com o CSS é possível deixar um site mais bonito, organizado e responsivo, controlando como os elementos aparecem na tela.



**Por que usar um arquivo externo (style.css)?**



O uso de um arquivo CSS externo é o mais recomendado porque: Mantém o código HTML mais limpo e organizado, permite reutilizar o mesmo estilo em várias páginas, ajuda na organização do projeto



Exemplo de ligação do CSS com o HTML: <link rel="stylesheet" href="style.css">





**Glossário de Propriedades CSS**



**color**

**Define a cor do texto de um elemento.**

ex: p {

&nbsp; color: blue;

}





**background-color**

**Define a cor de fundo de um elemento.**

**ex**:div {

&nbsp; background-color: lightgray;

}



**margin**

**Define a distância entre ele e outros elementos.**

ex: div {

&nbsp; margin: 20px;

}



**padding**

**Define o espaço interno do elemento, ou seja, a distância entre o conteúdo e a borda do elemento.**

**ex:** div {

&nbsp; padding: 15px;

}



**display: flex**

**A propriedade display: flex ativa o Flexbox, que é um sistema usado para organizar elementos em linha ou coluna, facilitando o alinhamento e a distribuição de espaço.**



**ex:**.container {

&nbsp; display: flex;

}





**Modelo de Caixa (Box Model)**



No CSS, todo elemento é tratado como uma caixa composta por:



**Content** (conteúdo) – texto ou imagem



**Padding** – espaço interno



**Border** (borda) – contorno do elemento



**Margin** – espaço externo



A diferença principal é:



**Padding** → espaço dentro do elemento



**Margin** → espaço fora do elemento





**Uso de Classes no CSS**

**As classes são utilizadas para aplicar estilos específicos a determinados elementos.**

**Elas ajudam a organizar melhor o código e permitem reutilizar estilos em vários elementos diferentes.**



ex HTML: <p class="texto-destaque">Este é um texto importante.</p>



ex CSS:



.texto-destaque {

&nbsp; color: red;

&nbsp; font-weight: bold;

}

**Nesse caso, qualquer elemento que tiver a classe texto-destaque receberá esse estilo.**





**Conclusão**



**O CSS é fundamental para o desenvolvimento web, pois permite separar estrutura (HTML) de estilo (CSS). O uso de arquivos externos e classes facilita a organização do código e torna o desenvolvimento mais eficiente.**





