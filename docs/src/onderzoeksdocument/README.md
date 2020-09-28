---
sidebar: auto
---

# WebRTC & Websockets

> Jeroen Vervaeck - 3 NMD - Web Of Things

## WebRTC

= Web Real-Time Communication

WebRTC maakt het mogelijk om spraak- en videocommunicatie te implementeren in de webbrowser. Zonder dat de browser extra plugin moet bezitten.

WebRTC bestaat sinds 2011, sindsdien is het gestegen in populariteit. Het is volledig gratis te gebruiken en het is open-source. Het is compatibel in alle moderne browsers. Google chrome, Firefox, Safari en Microsoft edge. Je kan WebRTC ook integreren in een applicatie of ingebouwd apparaat zonder de nood van een browser.

Wat WebRTC doet is de toegang tot apparaten mogelijk maken. Je hebt toegang tot de microfoon van je apparaat, de camera die je op je telefoon of laptop hebt - of het kan een scherm zijn. Je kunt het scherm van de gebruiker vastleggen en vervolgens dat scherm op afstand laten delen of opnemen.

Wat WebRTC ook doet, dat doet het in real time, waardoor er live interacties mogelijk zijn.

WebRTC is niet beperkt tot spraak en video. Het maakt het mogelijk om elk type van willekeurige data te verzenden


## Websockets

Websockets zijn bidirectionele mechanismen voor webbrowser communicatie.

Er zijn 2 types van transportkanalen in de webbrowser:
- HTTP 
- Websockets

HTTP is wat gebruikt wordt voor het ophalen van webpagina’s, afbeeldingen, stylesheets en js files alsook andere resources. In essentie is HTTP een client-server protocol, waarbij de browser de client is en de webserver de server.

⇒ uw browser maakt verbinding met een webserver en vraagt er iets van. De server stuurt dan een antwoord op dat verzoek en dat is het einde van het HTTP protocol.


Websockets zorgen ervoor dat de webbrowser connecteert met de webserver door het opzetten van een Websocket-verbinding. Over die connectie, beide de browser en de server kunnen elkaar ongevraagde berichten sturen. 

Omdat WebSockets voor het doel zijn gebouwd en niet de alternatieve XHR/SSE-hacks (HTTP requests), presteren WebSockets beter, zowel wat betreft de snelheid als de middelen die het opneemt op zowel de browsers als de servers.


## WebRTC vs Websockets

WebRTC maakt het mogelijk om data te sturen tussen browsers zonder dat de data eerst bij de server moet passeren. Deze data zal meestal spraak en video zijn.

Wanneer je een WebRTC sessie wil starten in een browser, zal deze verbinding gemaakt worden met een Websocket (of HTTP). Dus Websocket is geen vervanger van WebRTC, maar eerder een enabler. 

eenmaal die WebRTC verbinding vast ligt, zal er geen communicatie meer gebeuren met de server. enkel tussen de peers.

![img](https://bloggeek.me/wp-content/uploads/2019/05/201905-websocket-vs-datachannel-768x288.jpg)

::: tip
**Quick question: Wat is het verschil tussen WebRTC en WebSockets?**

Beide maken ze deel uit van de HTML5-specificatie. WebSockets is bedoeld om bidirectionele communicatie tussen een browser en een webserver mogelijk te maken. 
:::

WebRTC is bedoeld om real-time communicatie tussen browsers aan te bieden (voornamelijk spraak- en videocommunicatie).

## Bronnen


[What is WebRTC](https://bloggeek.me/what-is-webrtc/)

[webrtc-vs-websockets](https://bloggeek.me/webrtc-vs-websockets/)
