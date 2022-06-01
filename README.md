# Bibliotecas Usadas:

* NLTK
* Goose
* Sumy

# Técnicas de Machine Learning e outras:

* Processamento de linguagem natural
* WebScraping


# Construção:

Foi criada a função gerar resumo, ao ser invocada basta passar o link com o texto a ser sumarizado e o numero de linhas que deseja obter, o goose então acessa a pagina identifica o texto no corpo da página, extrai separa palavra por palavra(gerando tokens) e então o sumarizador acessa o documento tokenizado e estipula as partes mais importantes do texto.
