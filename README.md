# Skifree Game Remake

O projeto consiste em um remake do clássico jogo Skifree porém implementado com tecnologias de programação web, a saber:
Javascript
HTML
CSS
Framework YII2

Observações:
A pontuação do jogador é enviada para actionSave do jogoController por meio ds função 
"registrarPontuacao()" implementada no código javascript do jogo, "javascript.js" na 
pasta web/SkiFree/js.
Esta função executa uma requisição ajax para o url "http://localhost:8888/progweb/yii/advanced/frontend/web/index.php?r=jogo/save",
dependendo do sistema esse url precise ser alterado.

É possível visualizar os usuários cadastrados de acordo com o curso, conforme pedido no exercício 17 do slide 156. Para isso acesse Cursos na barra de menu superior e clique em "Usuários por curso", então você deverá selecionar o curso que deseja pesquisar então será exibida a relação de jogadores cadastrados com o curso escolhido.

Este projeto foi concluído como trabalho acadêmico ofertado à disciplina de Programação Web do curso de Engenharia de Software da UFAM.
