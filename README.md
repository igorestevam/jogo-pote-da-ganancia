# O Pote da Ganância (Trapaceiro)

Este é um projeto de interface interativa com temática **RPG / Dark Fantasy**, inspirado na famosa carta de TCG e, principalmente, na brincadeira viral criada pelo Tiktoker **[@zedejoze](https://www.tiktok.com/@zedejoze)**. 

O objetivo é simular um "duelo" contra uma carta do jogo Yu-Gi-Yo chamada "Pote da Ganância que possui uma personalidade sarcástica e a mesma lógica de trapaça apresentada nos vídeos do criador.

## 🔗 Demonstração
Você pode testar a sua paciência aqui: https://igorestevam.github.io/jogo-pote-da-ganancia/

## Inspiração Original
Este projeto foi desenvolvido como uma homenagem à "regra própria" do **Pote da Ganância** criada pelo **[@zedejoze](https://www.tiktok.com/@zedejoze)**. Nos seus vídeos, ele subverte a regra clássica da carta (que seria apenas sacar 2), transformando o ato em uma sucessão de trapaças acumulativas onde "quem cala consente".

## A Lógica do Sistema (As Regras do Zé)

O código foi programado para seguir fielmente o fluxo da brincadeira:

### 1. O Saque Inicial ("Vou sacar 2")
Ao ativar a ganância, o Pote afirma que vai sacar **2 cartas**. 
- **A Trapaça:** O sistema espera 5 segundos e adiciona **4 cartas** ao contador. 
- **O Deboche:** Ele usa a desculpa de que as "mãos escorregaram".

### 2. A Contestação vs. Silêncio
Após a trapaça, o botão **"VOCÊ TRAPACEOU!"** aparece e o cronômetro de 7 segundos começa:

* **Se você Reclamar (Contestar):** O Pote finge se desculpar e diz que vai sacar "só mais 1". 
    * *Realidade:* Ele saca **mais 2** e reinicia o ciclo, desafiando você a reclamar de novo.
* **Se você ficar em Silêncio (7 segundos):** Entra a regra suprema: **"Quem cala consente!"**. 
    * *Realidade:* O Pote saca **mais 2** cartas (mesmo dizendo que seria 1) e encerra a operação vitorioso sobre o seu silêncio.

## Tecnologias Utilizadas
- **HTML5/CSS3**: Interface com estética RPG, fontes `Cinzel` e efeitos de vibração de tela.
- **JavaScript**: Lógica de timers cumulativos e manipulação dinâmica de diálogos.

---
*Criado para fins de estudo/diversão e como tributo ao conteúdo de @zedejoze. O Pote nunca perde!*
