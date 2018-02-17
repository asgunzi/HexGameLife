# Hex Game of Life VBA

O Jogo da Vida, de John Conway (https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life), é um experimento computacional em que cada célula morre de solidão se tiver poucos vizinhos, e nasce se tiver muitos vizinhos. 

![](https://upload.wikimedia.org/wikipedia/commons/9/99/Game_of_life_glider_gun.png)

Baseado no experimento de Conway, fiz uma versão em VBA do mesmo. 

Mas, como o grid retangular é fácil demais, experimentei num grid hexagonal, transformando em Hex Game of Life.

![](https://ferramentasexcelvba.files.wordpress.com/2018/02/hexpainel.jpg?w=656)

No lado direito do painel, 4 parâmetros:

– Tamanho do hexágono em pixels
– Parâmetro de mortalidade (no caso, se uma célula tiver menos do que 2 vizinhos vivos, vai morrer)
– Parâmetro de reprodução (no caso, se uma célula tiver mais do que 3 vizinhos vivos, vai nascer)
– Número de rodadas (vide gif animado abaixo).

![](https://ferramentasexcelvba.files.wordpress.com/2018/02/hexanimated.gif?w=656)

O seed inicial é aleatório. Quanto mais verde, menos vizinhos, quanto mais amarelo, mais vizinhos. Técnicas deste tipo, chamadas de autômato celular, podem ser utilizar para modelagem de transmissão de epidemia, por exemplo.  Para rodar na planilha (download no Github https://github.com/asgunzi/HexGameLife), basta habilitar macros e mudar os parâmetros. Alguns padrões que surgiram:


![](https://ferramentasexcelvba.files.wordpress.com/2018/02/hex4.jpg?w=546&h=337)

![](https://ferramentasexcelvba.files.wordpress.com/2018/02/hex3.jpg?w=542&h=335)

![](https://ferramentasexcelvba.files.wordpress.com/2018/02/hex2.jpg?w=536&h=332)

![](https://ferramentasexcelvba.files.wordpress.com/2018/02/hex1.gif?w=542&h=335)


Post do Blog: https://ferramentasexcelvba.wordpress.com/2018/02/17/hex-game-of-life/

Patrocinado por: https://ideiasesquecidas.com/
