# React Pokedex

Uma pokedex feita com React JS e Bootstrap. 
São consumidos dados da API **PokeAPI**.

Existem três componentes principais:
**PokemonList**: Onde os dados da PokeAPI são consumidos para criar diversos cards de bootstrap com os pokemons.
**PokemonCard**: Os cards em si, que são renderizados dentro do component **PokemonList**, onde para cada pokemon é renderizado um card.
**Pokemon**:  Dados específicos sobre cada pokemon, com seus ataques, status, e várias informações legais resgatadas da API.

## Bibliotecas utilizadas:
**axios** para facilitar o consumo dos dados da api PokeAPI
**styled-components** para estilização dos componentes
**react-router-dom** para navegação