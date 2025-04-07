1. Simular o comportamento de pilhas dinâmicas para os algoritmos abaixo (A simulação deve
deixar evidente a pilha que sobrou na memória):

a)
Para (i = 0 ; i < 10 ; i++) {
  Se (i % 2 == 0) {
    Push(i * i);
  } Senão {
  Se (i <= 5) {
    Push(i);
  } Senão {
    Imprimir(Pop());
  }
}
  Imprimir(Top());
}
  Imprimir(Size());

b)
Para (i = 100 ; i < 115 ; i++) {
  Se (isEmpty()) {
    Push(i + 100);
  } Senão {
    Se (Size() <= 4) {
    Push(i + 50);
  } Senão {
      Imprimir(Pop());
  }
  }
    Imprimir(Top());
  }
    Imprimir(Size());
