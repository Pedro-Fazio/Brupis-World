# Introdução a Brupi's World
Esse projeto foi realizado como hobby, sendo ele um jogo 2D no estilo plataforma onde o usuário pode coletar moedas, matar monstros que são spawnados pelo mapa. E, embora o jogo seja curto, contendo apenas 1 hora de gameplay, ele também conta com uma história interessante e diálogos com a Brupi (personagem principal).

# Como jogar Brupi's World:
Para joga-lo é simples, basta baixar o repositório do projeto, ir na pasta **Build do jogo** e clicar em **Brupi World.exe**

# Controles do jogo
O jogo apenas possui duas mecânicas simples, os controles de movimentação do personagem e de atirar projéteis nos inimigos
![alt text](https://i.imgur.com/7cu9lWu.png)

# Inimigos
O jogo conta com **quatro** tipos de inimigos diferentes, tendo cada um deles suas próprias características:

### Lobo
![alt text](https://i.imgur.com/2SkRilf.png)

🡪 Causam dano ao contato
🡪 A velocidade desse inimigo pode variar de lobo para lobo
🡪 Perseguem o seu personagem
🡪 Não conseguem pular plataformas
🡪 Colidem com as paredes
🡪 Perigosos em ambientes fechados

**Dica contra esse inimigo:**
Atirar no lobo antes que ele chegue em você ou também é possível evitá-los apenas indo para outra plataforma, pois eles não conseguem pular plataformas, sendo assim, não vão mais te perturbar

### Abelha
![alt text](https://i.imgur.com/BIWLKPv.png)

🡪 Causam dano ao contato
🡪 Normalmente aparecem em bando
🡪 Irão seguir seu personagem 
🡪 Conseguem voar
🡪 São capazes de atravessar paredes

**Dica contra esse inimigo:**
Ir para um local aberto e atirar nas abelhas enquanto anda para trás

### Sapo
![alt text](https://i.imgur.com/fPdRs2Q.png)

🡪 Permanecem sempre no mesmo lugar
🡪 Não invertem sua posição (virar para trás)
🡪 Atiram projéteis de fogo de forma constante
🡪 Estão sempre em lugares estratégicos no mapa
🡪 Possuem um Fire rate de 1.8s entre cada projétil
🡪 Causa dano ao contato

**Dica contra esse inimigo:**
Tente chegar por trás dos sapos, pois eles atiram somente para frente, portanto são muito vulneráveis nas costas; outra forma de elimina-los é usar o Intervalo dos tiros para criar uma brecha e poder atacá-los


### Planta Carnívora
![alt text](https://i.imgur.com/PBSOzmn.png)

🡪 Permanecem sempre no mesmo lugar
🡪 Não inverte sua posição (virar para trás)
🡪 Não são tão perigosas se não chegar perto delas
🡪 Estão sempre em lugares estratégicos no mapa
🡪 Causa dano ao contato

**Dica contra esse inimigo:**
Não se aproximar das plantas carnívoras e atirar nelas à distância

# Falas da personagem e instruções
Hora ou outra aparecerão algumas bolinhas pretas com borda alaranjadas pelo mapa ou até mesmo plaquinhas, então, ao passar nesses triggers aparecerá uma tela de instruções ou alguma fala de Brupi
![alt text](https://i.imgur.com/bPY72kx.png)

# Coletáveis
Há dois tipos de coletáveis que o usuário consegue interagir, sendo eles para contar pontos no score do jogador ou para aumentar os seus pontos de vida
![alt text](https://i.imgur.com/6Vrolhv.png)

# Menu
O design do menu foi criado a partir da ferramenta de edição Photoshop CS6. Todas as imagens geradas a partir das edições de imagem no PSCS6 para a sua criação estão na diretório de **Imagens Usadas**
![alt text](https://i.imgur.com/s2vymQv.png)

# Criação da personagem
A ideia na hora de criar o jogo foi ser apenas mais um dia no dia de Brupi, como se ela fizesse essa rotina todos os dias e fosse algo normal para ela, então é algo rotineiro eliminar os animais da floresta para ganhar moedas valiosas e em seguida voltar para a sua casinha simples e ir dormir. Essa histórinha é contada através dos dialógos que ela tem com o jogador e também analisando o ambiente que ela se encontra 

**Para cria-la eu tentei transmitir as seguintes caracterísitcas de Brupi para o jogador:**
- Ser carismática
- Não ter plena noção das coisas
- Não possuir maldade nos seus atos

**O design da personagem**
Seu design foi criado todo a mão no papel e em seguida digitalizado utilizando a ferramenta de edição Photoshop CS6, enquanto todas as sprites do jogo foram retiradas da [Unity Assets Store](https://assetstore.unity.com/)
![alt text](https://i.imgur.com/IudgTtH.png)

# Bugs

### Bug no Pulo
Esse é um bug que se da ao pular para uma plataforma mais elevada e encostar nela muito rápido, fazendo com que o personagem não consiga pular mais, então o jogador terá que se mexer para os lados para que só então possa pular novamente. Esse bug também afeta a sprite do persongem, onde em determinadas situações, ao pular ele não restaura a animação idle (animação do personagem parado) e a sprite faz com que pareça que ele está caindo para sempre.
![alt text](https://i.imgur.com/ALyzFa0.png)

### Bug na Vida
Em alguns momentos da gameplay o personagem consegue parar de levar dano dos inimigos, fazendo com que a Brupi se torne imortal enquanto permanecer parada. Tudo volta ao normal quando o jogador se mexe novamente.
![alt text](https://i.imgur.com/z9qNErq.png)

### Bug da queda infinita
Esse não é bem um bug mas sim um mal design de mapa, onde uma parte no mapa não possui uma parede para obrigar que o jogador fique no mapa, desta forma o jogador pode pular para fora do mapa fazendo com que o personagem fique caindo para sempre.
![alt text](https://i.imgur.com/y7GfBN7.png)

# Considerações finais
No fim de tudo foi muito divertido criar esse joguinho! 
Eu criei para testar o que estava aprendendo sobre a Unity utilizando a linguagem C#. Acabei pensando no jogo plataforma 2D pois era o mais simples para começar e ver algum resultado mais prático, e também porque as sprites e tiles de mapa são muito mais fáceis de achar e ajustar para o jogo 2D do que 3D. Acabei conversando com alguns colegas para me darem ideias e alguns deles me ajudaram com o desenho, ideias para nome do personagem e até um pouco do design de mapa e história. Portanto foi uma ótima experiência para mim.

### Créditos
Aqui estão algumas peças essenciais para a criação desse projeto:
- Desenho das versões do personagem no papel: Ana Luiza Oliveira e Bruna Oliveira
- Ajuda na criação do nome da personagem: Bruna Ferreira
- Todas as sprites foram retiradas do site: https://assetstore.unity.com
- Musicas utilizadas: Magic Scout - Farm; Magic Scout - Cottage; Magic Scout - Northen Glade que foram retiradas do site: https://incompetech.com