## Jornada IA EBAC - 04/12 a 11/12
#### Projeto realizado utilizando JavaScript.
Esse projeto é o resultado da Jornada IA EBAC.
Esta teve como objetivo a criação de uma Inteligência Artificial para jogar o *"T-Rex Game"* (ou *"Chrome Dino"*), que é um jogo integrado ao navegador Google Chrome.

### Como aplicar a IA
1. Abrir o arquivo `script.js` no *VSCode*;
2. Iniciar um servidor local para hospedar seu projeto, clicando no botão ***Go Live*** (da extensão *Live Server*);
3. Abrir a página **[chrome://dino/](chrome://dino/)** ;
4. Clicar **F12** para abrir o menu *DevTools*;
5. Selecionar a seção ***Console*** do menu aberto;
6. Digitar no ***Console*** o seguinte código:
```javascript
   const s = document.createElement('script');
   s.type = 'module';
   s.src = 'http://localhost:5500/script.js';
   document.body.appendChild(s);
```
7. Automaticamente, a IA começará a jogar o jogo;
