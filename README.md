# Seletores

<h1> Telefone </h1>
 
email: document.querySelector('body').innerText.match(/([a-zA-Z0-9.-]+@[a-zA-Z0-9.-]+\.[a-zA-Z0-9_-]+)/gi)[0];

<h2> e-mail </h2>

phone: document.querySelector('body').innerText.match(/\b(?:\+?55\s?)?(?:\(?[1-9][0-9]\)?\s?)?(?:9\d{4}|\d{4})[-]?\d{4}\b/g); 

teste regex https://regex101.com/r/4i866k/1 
