# ltg
Repo para o website da LTG


Para implementar o formulário com upload de arquivos, segue um passo a passo sugerido com JS e Pipedream:

Create a form with a file upload field on your static website.
Use JavaScript to listen for the form submission event.
When the form is submitted, use the FormData API to create a new FormData object.
Add the file input to the FormData object.
Use the fetch API to make a POST request to Pipedream with the FormData object as the request body.
In Pipedream, use the HTTP trigger to receive the POST request from the form submission.
Use a Pipedream integration to upload the file to your drive.