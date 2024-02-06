
Documentação sobre Position no CSS

Bem-vindo ao guia completo sobre a propriedade position no CSS! Aqui, vamos explorar os diferentes valores dessa propriedade e entender como eles afetam o posicionamento dos elementos na página.


position: static (Padrão)

Descrição: Não aceita valores de top, bottom, right e left.

Comportamento: O elemento permanece no fluxo normal do documento.

.element {
  position: static;
}


position: fixed (Fixo na Tela)

Descrição: Fixa o elemento na tela, sempre no mesmo lugar.

Comportamento: O elemento permanece fixo em relação à janela de visualização.

.element {
  position: fixed;
  top: 0;
  left: 0;
}


position: sticky (Adesivo)

Descrição: Age como um adesivo, fixando o elemento na tela em um ponto determinado.

Comportamento: O elemento fica fixo até atingir um determinado ponto durante o rolar da página.

.element {
  position: sticky;
  top: 20px; /* Ponto de referência durante o scroll */
}


position: relative (Relativo ao Início)

Descrição: O elemento é posicionado em relação à sua posição inicial.

Comportamento: Mantém o espaço original do elemento no fluxo do documento.

.element {
  position: relative;
  top: 10px; /* Move o elemento 10 pixels para baixo em relação à sua posição inicial */
}


position: absolute (Absoluto)

Descrição: Fica absoluto (fixo) a algum elemento ou à página.

Comportamento: Posiciona-se em relação ao elemento pai (se não for static) ou à página.

.element {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%); /* Centraliza o elemento na tela */
}

Lembre-se das propriedades adicionais top, bottom, left e right que podem ser usadas para ajustar a posição dos elementos conforme necessário.

Esperamos que este guia tenha esclarecido suas dúvidas sobre a propriedade position no CSS. Explore essas técnicas para criar layouts dinâmicos e responsivos em seus projetos!