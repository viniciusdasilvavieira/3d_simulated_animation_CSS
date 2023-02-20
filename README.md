# 3d_simulated_animation_CSS

![3d_animation_css](https://i.imgur.com/xFEVUYt.png)

Primeiro eu havia feito uma versão mais simples sem javascript, porém o HTML ficou imenso, o que me fez decidir usar Javascript para gerar divs em um loop.

Como passei a usar Javascript, aproveitei para tornar o projeto um pouco mais dinâmico.

Poderia ter sido bem mais fácil se eu apenas adicionasse "camadas" de cubos externas, envolvendo as já criadas, porém a ordem de adição dos cubos precisa ser do topo para a base sempre (o que não é possível fazer com a forma citada), ou eu precisaria adicionar mais complexidade com o manuzeio dinânico do z-index de cada elemento.

Acabou sendo um ótimo exercício de lógica, e ajudou bastante eu ter construído uma versão grande funcional manualmente para aprender como funciona e identificar 'patterns' para automatizar.

Foi um desafio organizar os valores das paddings colocadas dinamicamente. Como é provavelmente evidente no código.

Os cubos em si foram feitos com CSS clip path, que é nativo de CSS.

Rascunhos

![scrap](https://i.imgur.com/2MFqdfR.png)
