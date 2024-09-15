# Seletores

<h1> EC- Telefone </h1>
 
phone:  document.querySelector('body').innerText.match(/\b(?:\+?55\s?)?(?:\(?[1-9][0-9]\)?\s?)?(?:9\d{4}|\d{4})[-]?\d{4}\b/g); 


<h2> EC-  e-mail </h2>

email: document.querySelector('body').innerText.match(/([a-zA-Z0-9.-]+@[a-zA-Z0-9.-]+\.[a-zA-Z0-9_-]+)/gi)[0];

Link teste regex https://regex101.com/r/4i866k/1 

<h1> Cliques de botão </h1>

href: ('a[href*="api.whatsapp"]')

Atributo([]): ('input[type="text"]'), 

    // Seletores Personalizados: ('a[href*="CONTEUDO"]') - * Seleciona o link que contém "api.whatsapp" no href em qualquer posição, podendo ser o texto de qualquer botão

    // Seletores Personalizados: ('a[href^="INICIO-DO-CONTEUDO"]') - ^ Seleciona o link que começa com "https://api.whatsapp", podendo ser o texto de qualquer botão
