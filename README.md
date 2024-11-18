# Frontend Mentor - Huddle landing page with single introductory section solution

Esta é uma solução para o [Desafio Página de destino do Huddle com solução de seção introdutória única](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Os desafios do Frontend Mentor ajudam você a melhorar suas habilidades de codificação construindo projetos realistas.


### Screenshot

[<img src="images/preview-desktop-design.gif" alt="Imagem da tela inicial do projeto Página de destino do Huddle com solução de seção introdutória única ">]

[<img src="images/preview-mobile-design.gif" alt="gif da tela inicial do projeto Página de destino do Huddle com solução de seção introdutória única">]


### Link


- URL do site ativo: [link aqui](https://andersonf-dev.github.io/huddle-landing-page-with-single-introductory-section-master/)



### Criado com

- Marcação HTML5 semântica
- Propriedades personalizadas CSS
- grid-template-areas




### O que aprendi

Foi um bom projeto para treinar grid-template-areas

```css
.imag-logo{grid-area: imag-logo;}
.conteiner-image{grid-area: conteiner-image;}
.text-content{grid-area: text-content; }
.redissocias{grid-area: redissocias;}

.conteiner-principal {
    display: grid;
    grid-template-areas: "imag-logo imag-logo"
                         "conteiner-image text-content"
                         "redissocias redissocias";
    
    grid-template-columns: repeat(2, 1fr); 
    display: flex;
    flex-direction: column;
    max-width: 1440px;                    
}

```

### Desenvolvimento contínuo

Este é apenas mais um de muitos dos projetos de front end que fiz. Continuarei fazendo e me desenvolvendo ainda mais. Estou aprendendo cada dia mais, fazendo esses desafios, 
