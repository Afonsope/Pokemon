# Pokemon
### Resumo do Código: Informações do Pokémon

Este projeto HTML apresenta uma interface interativa que permite aos usuários buscar informações sobre Pokémon através de seu nome ou ID, utilizando a API do Pokémon.

#### Funcionalidades:

1. **Interface do Usuário**:
   - O design é centrado com um fundo escuro e texto em destaque, utilizando cores vibrantes para títulos e botões.
   - O formulário permite ao usuário inserir o nome ou ID do Pokémon.

2. **Busca de Informações**:
   - Ao clicar no botão "Obter Informações do Pokémon", a função `obterInfoPokemon()` é acionada.
   - A função verifica se o campo de entrada não está vazio e, em seguida, faz uma requisição à API do Pokémon (`https://pokeapi.co/api/v2/pokemon/`).

3. **Exibição dos Dados**:
   - Após receber a resposta da API, as informações do Pokémon, incluindo imagem, nome, ID, peso e altura, são exibidas em uma área dedicada da página.
   - O peso e a altura são apresentados em unidades mais amigáveis (KG e M).

4. **Tratamento de Erros**:
   - A função inclui tratamento de erros, que alerta o usuário em caso de falha na busca, assegurando uma melhor experiência de uso.
