# RADAR DE PODCAST

Fiz uma análise de dados comparando os 3 maiores podcasts do Brasil (Flow, Inteligência LTDA, Podpah), analisando views, likes, comentários e vídeos publicados ao decorrer do tempo. Mais explicações, argumentos e análises nesse vídeo: https://youtu.be/REJS0ysKVtg

Os arquivos .csv são os dados que eu busquei na API do Youtube dos canais analisados, disponibilizei aqui caso alguém queira mexer nos dados e fazer análises diferentes sem fazer uma nova busca pela API. Aqui só estão os gráficos com uma breve explicação, a análise foi feita no vídeo do youtube.

## Obtendo dados

Através da API do Youtube, obtive total de views, inscritos e vídeos feitos de cada canal e logo em seguida foi possível obter a ID de cada vídeo produzido pelo canais analisados, através dessa ID consegui consolidar dados de views, likes, comentários, duração, título e data de publicação de cada vídeo, resultando em um grande DataFrame com dados individuais de cada vídeo dos 3 canais analisados.

## Análise inicial
Criei uma divisão baseada na duração da publicação, sendo 60s< = Short, caso contrário a publicação entra como Live, e pode-se ver o total de publicações de cada canal por essa divisão.
![1](https://i.imgur.com/eOpOfI4.png)

Na próximo imagem aparece um consolidado total de views por tipo de publicação, demonstrando qual podcast hoje possui a maior quantidade de visualizações, e a comparação com seus concorrentes, dividido por tipo de publicação.
![2](https://i.imgur.com/15bZeN0.png)

Criei uma medida para ter uma proporação de views por segundo de publicação.
![3](https://i.imgur.com/mNHaxjz.png)

## Flow
Gráficos de quantidade de publicações, views, likes e comentários do Flow no modo linha do tempo. Seguido do gráfico mostrando a tendência.

![4](https://i.imgur.com/l3EteIQ.png)

![5](https://i.imgur.com/vSpQ7dm.png)

![6](https://i.imgur.com/YqAGjcZ.png)

![7](https://i.imgur.com/ja3n0ui.png)

![8](https://i.imgur.com/HUnWrrq.png)

![9](https://i.imgur.com/LCVRHt2.png)

![10](https://i.imgur.com/ryRiLIq.png)

## Inteligência LTDA

Gráficos de quantidade de publicações, views, likes e comentários do Inteligência LTDA no modo linha do tempo. Seguido do gráfico mostrando a tendência.

![11](https://i.imgur.com/iyNFJxM.png)

![12](https://i.imgur.com/ToeDeE6.png)

![13](https://i.imgur.com/jL5TpBp.png)

![14](https://i.imgur.com/uMSLryX.png)

![15](https://i.imgur.com/g7AdrsV.png)

![16](https://i.imgur.com/RMZ82XN.png)

![17](https://i.imgur.com/sKO6mgb.png)

![18](https://i.imgur.com/C4nL32u.png)

## Podpah

Gráficos de quantidade de publicações, views, likes e comentários do Podpah no modo linha do tempo. Seguido do gráfico mostrando a tendência.

![19](https://i.imgur.com/4lOOM8x.png)

![20](https://i.imgur.com/xxnyzf8.png)

![21](https://i.imgur.com/M6eavs6.png)

![22](https://i.imgur.com/hRmGy6f.png)

![23](https://i.imgur.com/cfhcqJY.png)

![24](https://i.imgur.com/R3vEXZJ.png)

![25](https://i.imgur.com/vA8tUxm.png)

![26](https://i.imgur.com/KEv2GaU.png)

## Comparação entre os três

A primeira vista parece que com o decorrer do tempo o Flow foi perdendo relevância frente aos outros dois concorrentes.

FLOW = Azul, PODPAH = Verde, INTELIGÊNCIA LTDA = Laranja

![27](https://i.imgur.com/dntLt0q.png)

![28](https://i.imgur.com/798hAmZ.png)

![29](https://i.imgur.com/M6pweHU.png)

![30](https://i.imgur.com/c2GIxNL.png)

![31](https://i.imgur.com/FM3AIZP.png)

## Estúdios Flow

Acontece que o Flow não pode ser analisado apenas pelo canal de podcast do Flow, visto que eles começaram a expandir e criar os estúdios Flow, a seguir encontram-se as mesmas análises anteriores, porém com os números referentes aos Estúdios Flow como um todo.

![32](https://i.imgur.com/ROORZvv.png)

![33](https://i.imgur.com/YsPfGiF.png)

![34](https://i.imgur.com/fVyU8Wm.png)

## Nova comparação entre Estúdios Flow e os outros dois

Percebe-se nessa nova análise que os Estúdios Flow enquanto aglomerado continuam sendo o podcast/rede com maior engajamento no meio, porém gastando bem mais que seus concorrentos, visto que a quantidade da produção de conteúdo é muito maior. O gráfico a seguir mostra justamente esse consolidado de publicações entre o Estúdios Flow como um todo contra os outros dois concorrentes. No fim encontram-se as comparações no modo linha do tempo.

![35](https://i.imgur.com/vkHTzhp.png)

![36](https://i.imgur.com/yUGIqQ1.png)

![37](https://i.imgur.com/05zErim.png)

![38](https://i.imgur.com/EfIHIJE.png)

![39](https://i.imgur.com/Ztx4JQ2.png)

![40](https://i.imgur.com/gZF8lah.png)

![41](https://i.imgur.com/ugq9hk5.png)

![42](https://i.imgur.com/Izy2Pa6.png)
