Programado em Java
Um jogo de xadrez com interface de usuário (UI). Ele usa as classes ChessMatch, ChessPiece, ChessPosition e outras da pasta chess para implementar a lógica do jogo. A classe Programa é responsável por iniciar o jogo e gerenciar as entradas do usuário. Ela possui um loop while que executa o jogo enquanto o jogo não chega ao fim. O fim do jogo é indicado pelo método getCheckMate() da classe ChessMatch. Dentro do loop, o código lê a entrada do usuário para a posição de origem da jogada e depois exibe na tela as possíveis jogadas válidas da peça selecionada. Em seguida, lê a entrada do usuário para a posição de destino e executa a jogada com performChessMove. Se uma peça for capturada na jogada, ela é adicionada à lista de peças capturadas (captured).Se uma peça foi promovida na jogada, o código lê a entrada do usuário para o tipo de peça (B/N/R/Q) e executa a promoção com replacePromotedPiece. Se ocorrer uma exceção ChessException ou InputMismatchException, o código imprime a mensagem de erro e pede ao usuário para inserir novamente a entrada. Após o jogo acabar, o código limpa a tela e imprime o resultado final com UI.printMatch.

Projeto desenvolvido com o curso de Java da UDEMY, professor: Nelio Alves.
