# ltg
Repo para o website da LTG


## Para fazer a animacao da 'cover'
pode ser utilizado somente CSS mesmo, parece que dá pra utilizar o scroll como um parametro para um transition de transform.
A ideia seria o menu superior da esquerda estar com visibility: hidden e os 3 links centrais com visibility: visible. Conforme a pagina é scrollada pra baixo, os 3 links vão encolhendo pra esquerda até ficar do tamanho e posição do texto do menu (os caminhos se juntariam formando um L). Nessa interseção eles mudam pra visibility: hidden e o menu que vinha de cima muda pra visibility: visible;

## Para fazer a trocar de texto na seção de Metodologia
Pode se utilizar a pseudoclass :focus e ir trocarndo a visibility dos <p>'s que estão todos sobrepostos

## Para implementar o formulário com upload de arquivos, segue um passo a passo sugerido com JS e Pipedream:

Create a form with a file upload field on your static website.
Use JavaScript to listen for the form submission event.
When the form is submitted, use the FormData API to create a new FormData object.
Add the file input to the FormData object.
Use the fetch API to make a POST request to Pipedream with the FormData object as the request body.
In Pipedream, use the HTTP trigger to receive the POST request from the form submission.
Use a Pipedream integration to upload the file to a drive (isolated and/or secured)


## Lembrar de tomar medidas de segurança para evitar submits maliciosos:

HTTPS
Validate and Sanitize User Input
File size and type limitation