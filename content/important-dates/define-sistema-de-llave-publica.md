---
layout: post
title: Se define el sistema asimétrico o de llave pública
date: 2023-04-13 20:32
author: proyecto.encriptado@gmail.com
comments: true
categories: [Bitcoin, Historia, Tal día como hoy]
---
<!-- wp:paragraph {"style":{"elements":{"link":{"color":{"text":"#0745e3"}}}}} -->
<p class="has-link-color">En noviembre de 1976 aparece el primer trabajo sobre Criptografía de Llave Pública publicado, fue en el paper denominado <a href="https://ee.stanford.edu/~hellman/publications/24.pdf">“New Directions in Cryptography”, versión del IEEE Transactions on Information Theory</a>.</p>
<!-- /wp:paragraph -->

<!-- wp:image {"id":724,"sizeSlug":"full","linkDestination":"none"} -->
<figure class="wp-block-image size-full"><img src="https://proyectobitcoin.com/wp-content/uploads/2023/04/Noviembre-1976.png" alt="" class="wp-image-724"/></figure>
<!-- /wp:image -->

<!-- wp:paragraph {"style":{"elements":{"link":{"color":{"text":"#0745e3"}}}}} -->
<p class="has-link-color">Los primeros investigadores en encontrar y publicar las ideas de criptografía de llave pública fueron<a href="https://autonomia.digital/es/2019/11/11/diffie-hellman.html"> Whitfield Diffie y Martin Hellman de la Universidad de Stanford, junto a Ralph Merkle de la Universidad de Berkeley</a>, que estaban trabajando de forma independiente en los mismos problemas hasta que se conocieron y empezaron a colaborar.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"style":{"elements":{"link":{"color":{"text":"#0745e3"}}}}} -->
<p class="has-link-color"><a href="https://es.wikipedia.org/wiki/Diffie-Hellman">El paper representa las ideas principales de la Criptografía de Llave Pública</a>, incluyendo la generación de firmas digitales, y mostró algunos algoritmos para su ejecución, revolucionando el mundo de la investigación en criptografía que, hasta ese momento, era controlado en los confines del gobierno. </p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"style":{"elements":{"link":{"color":{"text":"#0745e3"}}}}} -->
<p class="has-link-color">Diffie, Hellman y Merkle obtuvieron posteriormente la patente número 4,200,770 correspondiente a su método de seguridad.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"style":{"elements":{"link":{"color":{"text":"#0745e3"}}}}} -->
<p class="has-link-color">El protocolo criptográfico Diffie-Hellman, es un protocolo de establecimiento de claves entre partes que no han tenido contacto previo, utilizando un canal inseguro y de manera anónima (no autenticada).</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"style":{"elements":{"link":{"color":{"text":"#0745e3"}}}}} -->
<p class="has-link-color"><a href="https://www.segu-info.com.ar/criptologia/asimetricos">El sistema se basa en la idea de que dos interlocutores pueden generar conjuntamente una clave compartida sin que un intruso</a>, que esté escuchando las comunicaciones, pueda llegar a obtenerla.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"style":{"elements":{"link":{"color":{"text":"#0745e3"}}}}} -->
<p class="has-link-color">Para ello se eligen dos números públicos y, cada interlocutor, un número secreto. Usando una fórmula matemática, que incluye la exponenciación, cada interlocutor hace una serie de operaciones con los dos números públicos y su número secreto.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"style":{"elements":{"link":{"color":{"text":"#0745e3"}}}}} -->
<p class="has-link-color">Luego los interlocutores se intercambian los resultados de forma pública. En teoría, revertir esta función es tan difícil como calcular un logaritmo discreto (un sextillón de veces más costoso que la exponenciación usada para transformar los números). Por eso se dice que este número es el resultado de aplicar una función unidireccional al número secreto.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"style":{"elements":{"link":{"color":{"text":"#0745e3"}}}}} -->
<p class="has-link-color">A continuación, ambos interlocutores utilizan por separado una fórmula matemática que combina los dos números transformados con su número secreto y al final los dos llegan al mismo número resultado, que será la clave compartida.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"style":{"elements":{"link":{"color":{"text":"#0745e3"}}}}} -->
<p class="has-link-color">El protocolo es sensible a ataques activos del tipo Man-in-the-middle. Si la comunicación es interceptada por un tercero, no se dispone de ningún mecanismo para validar la identidad de los participantes en la comunicación.&nbsp;</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"style":{"elements":{"link":{"color":{"text":"#0745e3"}}}}} -->
<p class="has-link-color">Así, el "hombre en el medio" podría acordar una clave con cada participante y retransmitir los datos entre ellos, escuchando la conversación en ambos sentidos.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"style":{"elements":{"link":{"color":{"text":"#0745e3"}}}}} -->
<p class="has-link-color">Diffie-Hellman es ampliamente usado en varias aplicaciones para encriptar datos, por ejemplo: SSL(Secure Socket Layer), TLS(Transport Layer Security), SSH(Secure Shell) o VPN(Virtual Private Network).</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"style":{"elements":{"link":{"color":{"text":"#0745e3"}}}}} -->
<p class="has-link-color">Whitfield Diffie y Martin Hellman <a href="https://www.oroyfinanzas.com/2016/03/creadores-criptografia-clave-publica-whitfield-diffie-martin-hellman-ganan-premio-turing/">recibieron el prestigioso premio A.M. Turing </a>de 2015 y el de la Association for Computer Machinery en 2016.</p>
<!-- /wp:paragraph -->
