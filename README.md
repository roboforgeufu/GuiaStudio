# Guia do Forgiano para o Studio 2.0
Instruções e dicas para utilização do software `Studio 2.0`, da BrickLink.

~RoboForge 2020

***

# Index
* [Visão Geral](https://github.com/roboforgeufu/GuiaStudio#vis%C3%A3o-geral)
* [Primeiro Contato](https://github.com/roboforgeufu/GuiaStudio#primeiro-contato)
* [Construindo além do caracol](https://github.com/roboforgeufu/GuiaStudio#construindo-al%C3%A9m-do-caracol)
    * [Ferramentas para Construção](https://github.com/roboforgeufu/GuiaStudio#ferramentas-para-constru%C3%A7%C3%A3o)
    * [Câmera](https://github.com/roboforgeufu/GuiaStudio#c%C3%A2mera)
    * [Views](https://github.com/roboforgeufu/GuiaStudio#views)
    * [Selection tool](https://github.com/roboforgeufu/GuiaStudio#selection-tool)
    * [Movimentação](https://github.com/roboforgeufu/GuiaStudio#movimenta%C3%A7%C3%A3o)
    * [Hinge tool](https://github.com/roboforgeufu/GuiaStudio#hinge-tool)
    * [Clone tool](https://github.com/roboforgeufu/GuiaStudio#clone-tool)
    * [Hide tool](https://github.com/roboforgeufu/GuiaStudio#hide-tool)
    * [Collision](https://github.com/roboforgeufu/GuiaStudio#collision)
    * [Snap, Grid](https://github.com/roboforgeufu/GuiaStudio#snap-grid)
    * [Connect tool](https://github.com/roboforgeufu/GuiaStudio#connect-tool)
    * [Stability](https://github.com/roboforgeufu/GuiaStudio#stability)
* [Algumas Peças Comuns](https://github.com/roboforgeufu/GuiaStudio#algumas-pe%C3%A7as-comuns)

***

![Studio Interface](/imagens/studio-interface.png)

## Visão Geral
O Studio é um software desenvolvido para construção, renderização e criação de guias de montagens de construtos de LEGO. Funcionalidades que são muito úteis no processo de desenvolvimento de robôs dos kits de robótica da LEGO, como os Mindstorms NXT e EV3.

É com esta visão que nós, da equipe de robótica RoboForge, sediada na Faculdade de Computação da Universidade Federal de Uberlândia, criamos este guia: para auxiliar o primeiro contato de roboticistas empolgados com esse simples e poderoso software de modelagem LEGO, além de reunir instruções e dicas básicas de forma intuitiva para futuras eventuais consultas. 

## Primeiro Contato

Instalado o Studio, na primeira vez que o usuário abrí-lo será recebido por uma tela que propõe a realização do tutorial. São apresentados então, as seguintes funcionalidades:


| Comandos | Função |
|----------|--------|
| Scroll do mouse | Controla o zoom |
| Botão direito + Arrastar | Rotaciona a câmera em volta de um ponto fixo |
| Espaço + Clique + Arrastar | Movimenta a câmera |
| Clique com o botão esquerdo | Selecionar bloco |
| Seleção + Setas do teclado | Rotacionam o bloco selecionado |
| Seleção + Arraste | Conecta peças |
| Ctrl + Seleção | Seleção de múltiplas peças |

Além disso, o tutorial também ensina:

* Pesquisa por nome de peça no catálogo de peças:
Basta digitar o que quiser pesquisar na caixa de pesquisa sobre o catálogo de peças, geralmente na parte esquerda ou inferior da tela.
* Mudança de cor de peças:
Basta selecionar a(s) peça(s) que o usuário queira escolher a cor e então selecionar uma cor na janela "Color Pallete", que aparece por padrão na parte direita da tela;
* Hinge tool:
Ferramenta para articulações e engrenagens, abordada aqui.

Essa já é uma boa introdução para alguém que caiu de paraquedas no Studio, mas para uma boa utilização e contrução de modelos mais complexos, outras informações também são muito importantes.

## Construindo além do caracol
![Snail](/imagens/snail.png)

### Ferramentas para construção
![Toolbar](/imagens/tool_bar.png)

### Câmera
Os controles de câmera são basicamente os abordados no tutorial. 

| Comandos | Função |
|----------|--------|
| Scroll do mouse | Controla o zoom |
| Botão direito + Arrastar | Rotaciona a câmera em volta de um ponto fixo |
| Espaço + Clique + Arrastar | Movimenta a câmera |

Além dos controles básicos, as teclas `A`,`W`,`S`,`D`, também podem ser usadas para movimentar a câmera, quando não houver nenhuma parte selecionada.

### Views

![Camera](/imagens/views.png)

Clicando no ícone da câmera, no canto superior esquerdo da tela de contrução, é possível escolher diferentes vistas do projeto, para vê-lo em diferentes perspectivas: lateral, frontal, de baixo, de cima, ortogonal.

![Views Bar](/imagens/views_bar.png)

### Selection tool
A maioria das ferramentas são utilizadas através do mouse no Studio. Para voltar para o cursor normal de seleção padrão, basta apertar `Esc` ou `V`.

Para selecionar uma peça, basta clicar sobre ela.
Para seleção múltipla manual, basta segurar `Ctrl` enquanto seleciona as peças clicando sobre elas.

![Multiple Selection](/imagens/multiple_selection.png)

![Selection Menu](/imagens/selection_menu.png)

No menu de seleção, as seguintes seleções adicionais estão disponíveis:
* Padrão:
Seleciona a peça que recebeu o clique.
* Por cor:
Seleciona todas as peças da mesma cor que a selecionada manualmente.
* Por tipo de peça:
Seleciona todas as peças do mesmo tipo que a selecionada manualmente.
* Por tipo e cor:
União de ambos acima;
* Por conectadas:
Seleciona todas as peças conectadas à selecionada manualmente.

### Movimentação
Para mover uma peça ou um grupo de peças selecionado, basta arrastar com o mouse.
Outra alternativa é utilizar as teclas `A`, `W`, `S`, `D`, que movem o grupo selecionado.
Para girar o grupo selecionado, basta utilizar as setas no teclado. Cada clique será um giro de 90 graus naquela direção.
`Shift` + Setas giram da mesma forma, mas em giros de 45 graus.

Também é possível mover as peças pelo cursor, clicando na peça e depois em um dos ícones que aparecer próximo a ela. Aí é só arrastar.

![Movimentação](/imagens/mov.png)
![Movimentação](/imagens/mov_1.png)
![Movimentação](/imagens/mov_2.png)

### Hinge tool
É a segunda ferramenta da barra de ferramentas, e também pode ser acessada pela tecla `H`.
Selecione uma peça ou um conjunto de peças para girá-las em qualquer direção arrastando os cursores que aparecerem.

Se a peça ou a seleção de peças estiver conectada a outra peça ou outro conjunto de peças, o giro da seleção terá como centro o ponto de conexão.

![Hinge](/imagens/hinge.png)

### Clone tool
Terceira ferramenta da barra de ferramentas, também acessada pela tecla `C`.
Selecione uma peça para duplicar. A cópia fica disponível no cursor do mouse.

### Hide tool
Quarta ferramenta da barra de ferramentas, também acessada pela tecla `L`.
Esconde peças selecionadas clicando nelas. Para voltar a ver as peças escondidas, basta clicar no botão `Show All` que aparecerá no canto superior direiro da tela enquanto houverem peças escondidas.

![Hide Example](/imagens/hide_example.png)

### Collision
A ferramenta `Collision` verifica se no modelo existem peças conflitantes, ocupando o mesmo espaço ao mesmo tempo.

![Collision Off](/imagens/collision_off.png)

Com ela ativada, as peças em conflito ficam destacadas no modelo.

![Collision On](/imagens/collision_on.png)

Também pode ser ativada/desativada por `Ctrl` + `Alt` + `C`.

### Snap, Grid
As ferramentas `Snap` e `Grid` controlam como as peças vão se comportar no modelo virtual, a partir da interação com outras peças.

Com `Snap` ativado, as peças irão se encaixar mais facilmente, enquanto que com ele desativado elas ficam mais livres, com posições menos truncadas. (Para mais versatilidade para conectar peças, fica a dica de utilizar a ferramenta `Connect`, descrita a seguir).

Já o `Grid` controla a disposição geral das peças. Quanto menores os detalhes da grade, mais posições intermediárias as peças poderão ocupar.

![Grid](/imagens/grid.png)

### Connect tool
Ferramenta muito útil para conectar peças, mais versátil e precisa do que a técnica de arrastar peças umas sobre as outras.
Basta selecionar a peça que será conectada, a posição dela que será conectada (em azul) e a posição em que será conectada na segunda peça (também em azul).

![Connect Example](/imagens/connect_1.png)
![Connect Example](/imagens/connect_2.png)
![Connect Example](/imagens/connect_3.png)

Cuidado ao conectar grupos de peças: o primeiro se moverá para a posição de conexão do segundo.

Cilindros azuis representam posições internas das peças, conectam peças uma dentro da outra.

Os cubos azuis representam posições externas das peças, colocam peças lado a lado. Podem também representar posições de peças que só tem uma única posição. Ex: pneus só tem uma posição de conexão com rodas.

### Stability
Ferramenta utilizada para conferir a estabilidade do modelo.

![Unstable example](/imagens/unstable_example.png)
![Unstable example](/imagens/stability_1.png)

![Stable example](/imagens/stable_example.png)
![Stable example](/imagens/stability.png)


## Algumas Peças Comuns
O BrickLink Studio foi feito para construções de LEGO em geral, então pode ser difícil achar peças específicas dos kits de robótica. Para facilitar isso, aqui está uma lista de peças comuns nos kits da LEGO. Pesquise pelos códigos e encontre as peças.

Para encontrar peças que não estão listadas aqui, pesquise pelo nome de peças listadas semelhantes, assim você provavelmente vai achar.

![Lista de peças](/imagens/pieces.png)
![Lista de peças](/imagens/pieces_2.png)
![Lista de peças](/imagens/pieces_3.png)
![Lista de peças](/imagens/pieces_4.png)
![Lista de peças](/imagens/pieces_5.png)


***

```
TODO:
- Shortcuts
- Steps
- Instruções
```