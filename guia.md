# Guia do Forgiano para o Studio 2.0
Instruções e dicas para utilização do software `Studio 2.0`, da BrickLink.

~RoboForge 2020
***

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
Ferramenta para articulações e engrenagens, abordada aqui.(TODO)

Essa já é uma boa introdução para alguém que caiu de paraquedas no Studio, mas para uma boa utilização e contrução de modelos mais complexos, outras informações também são muito importantes.

## Construindo Além do Caracol
<Imagem aqui>(TODO)

### Ferramentas para construção
#### Câmera
Os controles de câmera são basicamente os abordados no tutorial. 

| Comandos | Função |
|----------|--------|
| Scroll do mouse | Controla o zoom |
| Botão direito + Arrastar | Rotaciona a câmera em volta de um ponto fixo |
| Espaço + Clique + Arrastar | Movimenta a câmera |

Além dos controles básicos, as teclas `A`,`W`,`S`,`D`, também podem ser usadas para movimentar a câmera, quando não houver nenhuma parte selecionada.

#### Views
Clicando no ícone da câmera, no canto superior esquerdo da tela de contrução, é possível escolher diferentes vistas do projeto, para vê-lo em diferentes perspectivas: lateral, frontal, de baixo, de cima, ortogonal.

#### Selection tool
A maioria das ferramentas são utilizadas através do mouse no Studio. Para voltar para o cursor normal de seleção padrão, basta apertar `Esc` ou `V`.

Para selecionar uma peça, basta clicar sobre ela.
Para seleção múltipla manual, basta segurar `Ctrl` enquanto seleciona as peças clicando sobre elas.

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

#### Movimentação
Para mover uma peça ou um grupo de peças selecionado, basta arrastar com o mouse.
Outra alternativa é utilizar as teclas `A`, `W`, `S`, `D`, que movem o grupo selecionado.
Para girar o grupo selecionado, basta utilizar as setas no teclado. Cada clique será um giro de 90 graus naquela direção.
`Shift` + Setas giram da mesma forma, mas em giros de 45 graus.
Também é possível mover as peças pelo cursor, clicando na peça e depois em um dos ícones que aparecer próximo a ela. Aí é só arrastar.


#### Hinge tool
É a segunda ferramenta da barra de ferramentas, e também pode ser acessada pela tecla `H`.
Selecione uma peça ou um conjunto de peças para girá-las em qualquer direção arrastando os cursores que aparecerem.
Se a peça ou a seleção de peças estiver conectada a outra peça ou outro conjunto de peças, o giro da seleção terá como centro o ponto de conexão.

#### Clone tool
Terceira ferramenta da barra de ferramentas, também acessada pela tecla `C`.
Selecione uma peça para duplicar. A cópia fica disponível no cursor do mouse.

#### Hide tool
Quarta ferramenta da barra de ferramentas, também acessada pela tecla `L`.
Esconde peças selecionadas clicando nelas. Para voltar a ver as peças escondidas, basta clicar no botão `Show All` que aparecerá no canto superior direiro da tela enquanto houverem peças escondidas.

#### Collision
A ferramenta `Collision` verifica se no modelo existem peças conflitantes, ocupando o mesmo espaço ao mesmo tempo.
Com ela ativada, as peças em conflito ficam destacadas no modelo.
Também pode ser ativada/desativada por `Ctrl` + `Alt` + `C`.

#### Snap, Grid
As ferramentas `Snap` e `Grid` controlam como as peças vão se comportar no modelo virtual, a partir da interação com outras peças.
Com `Snap` ativado, as peças irão se encaixar mais facilmente, enquanto que com ele desativado elas ficam mais livres, com posições menos truncadas. (Para mais versatilidade para conectar peças, fica a dica de utilizar a ferramenta `Connect`, descrita a seguir).
Já o `Grid` controla a disposição geral das peças. Quanto menores os detalhes da grade, mais posições intermediárias as peças poderão ocupar.

#### Connect tool
Ferramenta muito útil para conectar peças, mais versátil e precisa do que a técnica de arrastar peças umas sobre as outras.
Basta selecionar a peça que será conectada, a posição dela que será conectada (em azul) e a posição em que será conectada na segunda peça (também em azul).
Cuidado ao conectar grupos de peças: o primeiro se moverá para a posição de conexão do segundo.
Cilindros azuis representam posições internas das peças, conectam peças uma dentro da outra.
Os cubos azuis representam posições externas das peças, colocam peças lado a lado. Podem também representar posições de peças que só tem uma única posição. Ex: pneus só tem uma posição de conexão com rodas.

#### Stability
Ferramenta utilizada para conferir a estabilidade do modelo.

### Algumas Peças Comuns