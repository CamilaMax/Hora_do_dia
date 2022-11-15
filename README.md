# Hora_do_dia
conforme muda o horário do aparelho que esta conectado a imagem e a cor de funda mudam.


![Logo do Markdown](Screenshot%202022%2D11%2D14%2018.38.35.png)


 # Autor
  
  [Camila Maximo](https://enchanting-boba-26a643.netlify.app/).



## Linguagens utilizada

- Css
- Html
- JavaScript

## O que aprendi ?
  Conseguir entender o que é uma variável como trabalhar com ela dentro do JavaScript,também, consegui aprender códigos para trabalhar data e hora e a utilização da condicional **IF** e **else**.
  
    ```
  function carregar(){
    var msg = document.getElementById('msg')
    var img = document.getElementById('img')
    var data = new Date()
    var hora = data.getHours()
    
    msg.innerHTML = `Agora são ${hora} horas.`

    if (hora >= 0 && hora < 12) {
        img.src = 'imagens/bomdia.png'
        document.body.style.background = '#B8E3E9'

    } else if (hora >= 12 && hora < 18){
        img.src = 'imagens/boatarde.png'
        document.body.style.background = '#e2cd9f'
    } else {
        img.src = 'imagens/boanoite.png'
        document.body.style.background = '#646279'
        
    }}
  ```
  
  
  
 
  
