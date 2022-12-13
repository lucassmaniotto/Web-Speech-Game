# Web Speech Guessing Game

Projeto de jogo de adivinhação por fala consumindo dados externos da Web Speech API.

| :placard: Vitrine.Dev |     |
| -------------  | --- |
| :sparkles: Nome        | **Web Speech Guessing Game**
| :label: Tecnologias | html, css, javascript
|  🖥  Curso     | https://cursos.alura.com.br/formacao-javascript-front-end
| :rocket: URL         | https://web-speech-game.vercel.app/

## Detalhes do projeto

<img src="https://user-images.githubusercontent.com/101435037/207368715-e640c3e5-bf46-4807-bad7-43561aa7d0ad.png" align="center">

O projeto foi feito através do curso da Alura de [Javascript para Frontend](https://cursos.alura.com.br/formacao-javascript-front-end), utilizando a [Web Speech API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API).

A aplicação consiste em um jogo de adivinhação de números com chances infinitas. Para jogá-lo basta utilizar seu microfone e dizer seu chute. Os algoritmos da aplicação sorteiam um número aleatório e os dados que são enviados do microfone são validados, retornando certos tipos de mensagem para cada caso.

### Browsers support

| [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/edge/edge_48x48.png" alt="IE / Edge" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>IE / Edge | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png" alt="Chrome" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>Chrome | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/safari/safari_48x48.png" alt="Safari" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>Safari | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/safari-ios/safari-ios_48x48.png" alt="iOS Safari" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>iOS Safari | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/samsung-internet/samsung-internet_48x48.png" alt="Samsung" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>Samsung | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/opera/opera_48x48.png" alt="Opera" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>Opera |
| :---------: | :---------: | :---------: | :---------: | :---------: | :---------: |
| 79 | 33 | 14.4 | 14.5 | 2.0| 20

### Funcionamento
Para cada chute, caso o número não for acertado, dicas são postas com o chute na tela para o usuário acertar o número secreto

<img src="https://user-images.githubusercontent.com/101435037/207372538-544ff108-8dca-4e1a-b396-1165edd722b1.png" align="center">

Caso algum dado a ser validado seja um absurdo, o algoritmo trata de formas diferentes:
* Para valores fora do intervalo é informado uma mensagem dizendo em que intervalo devemos operar:<img src="https://user-images.githubusercontent.com/101435037/207373186-5ff794dd-5d60-4dc2-97df-35e1c0e13a46.png" align="center">
&nbsp;
* Para valores que não sejam números, também é tratado de forma diferente informando que o dado não é válido:<img src="https://user-images.githubusercontent.com/101435037/207373929-8df26b57-4d24-4a4a-9969-95bcc1fe586c.png" align="center">

### Efeitos CSS
O Projeto também conta com efeitos visuais quando ocorre uma vitória, onde é simulado fogos de artifício com keyframes, feitos com CSS puro:
<p align="center">
<img src="https://user-images.githubusercontent.com/101435037/207378283-be7a6bfd-e95c-4235-b8de-8b4ade66cdd3.gif">
</p>

### Responsividade
O jogo pode ser jogado tanto no computador, como tablet e smartphone:

| Desktop :desktop_computer: | Tablet :computer: | Mobile :iphone: |
| :---------: | :---------: | :---------: |
| ![image](https://user-images.githubusercontent.com/101435037/207378857-6e6c409a-646c-4f06-8088-081c06dceda7.png) | ![image](https://user-images.githubusercontent.com/101435037/207378959-b4e18dad-63e7-43a6-8637-19846cc31076.png) | ![image](https://user-images.githubusercontent.com/101435037/207379162-a705a112-e3d7-4912-878f-f83e6466515c.png) |
