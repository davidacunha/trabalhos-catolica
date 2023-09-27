Nomes: David Jonathan Misael da Cunha e Victor Hugo Baggio Alves.

a)
Uma história de usuário é uma breve descrição das necessidades do usuário em relação a um produto ou recurso, escrita da perspectiva do usuário final. É usado no desenvolvimento ágil de software para documentar os requisitos do produto e garantir que o produto atenda aos requisitos do usuário.
Exemplos de finalidade:

Comunicar os requisitos do produto à equipe de desenvolvimento e aos usuários.
Certifique-se de que o produto atenda às suas necessidades.
Promover a colaboração entre equipes de desenvolvimento e usuários.
b)

Como um cliente, eu quero pesquisar produtos por nome. O cliente poderia inserir o nome do produto na barra de pesquisa na página inicial do e-commerce. O cliente poderia clicar no botão "Pesquisar" para executar a pesquisa. Os resultados da pesquisa poderiam ser exibidos em uma lista, com cada resultado contendo o nome do produto, uma imagem, o preço e uma breve descrição.

c)

História de usuário 1:

Como um cliente, eu quero pesquisar produtos por categoria para encontrar produtos relacionados ao meu interesse.

Critérios de aceitação:

O cliente deve ser capaz de selecionar uma categoria de produto na barra de pesquisa. Os resultados da pesquisa devem ser exibidos em uma lista, ordenada por relevância. O cliente deve ser capaz de clicar em um resultado para visualizar mais informações sobre o produto.

História de usuário 2:

Como um cliente, eu quero pesquisar produtos por faixa de preço para encontrar produtos que cabem no meu orçamento.

Critérios de aceitação:

O cliente deve ser capaz de selecionar uma faixa de preço na barra de pesquisa. Os resultados da pesquisa devem ser exibidos em uma lista, ordenada por preço. O cliente deve ser capaz de clicar em um resultado para visualizar mais informações sobre o produto. Essas duas histórias de usuário adicionam funcionalidade adicional à funcionalidade básica de pesquisa por nome. A primeira história de usuário permite que os clientes pesquisem produtos por categoria, o que pode ser útil para encontrar produtos relacionados ao seu interesse. A segunda história de usuário permite que os clientes pesquisem produtos por faixa de preço, o que pode ser útil para encontrar produtos que cabem no seu orçamento.

História de usuário 1:

Como um cliente do e-commerce, desejo a capacidade de pesquisar produtos por categoria na página inicial do site. Isso me permitirá encontrar rapidamente produtos relacionados a uma categoria específica que estou interessado em explorar.

História de usuário 2:

Como um cliente do e-commerce, desejo a capacidade de pesquisar produtos por uma faixa de preço na página inicial do site. Isso me permitirá encontrar produtos que se encaixam no meu orçamento e atendem às minhas necessidades financeiras.

d)

O relatório poderia ser gerado usando uma ferramenta de análise de dados. Os dados de vendas poderiam ser coletados de uma base de dados de vendas. O relatório poderia ser personalizado para atender às necessidades específicas do gerente de vendas. O relatório deve ser fácil de entender e interpretar. O relatório deve ser visualmente atraente. O relatório deve ser protegido contra acesso não autorizado.

a) def test_string_empty(): s = "" expected = "" actual = string_invert(s) assert expected == actual

b) def test_single_character_string(): s = "a" expected = "a" actual = string_invert(s) assert expected == actual

c) def test_multiple_character_string(): s = "hello" expected = "olleh" actual = string_invert(s) assert expected == actual

a) def contar_caracteres(str): quantidade_de_caracteres = 0 for caractere in str: quantidade_de_caracteres += 1 return quantidade_de_caracteres

b) def test_conta_caracteres(): str = "campeaodacopadobrasil" resultado = contar_caracteres(str) assert resultado == 21

Esse teste verifica se a função retorna 0 para uma string vazia.

1.1) A abordagem correta do Test Driven Development (TDD) é:

C. Escrever o teste, executar o teste, escrever o código, executar o teste novamente, refatorar e, por fim, integrar o código ao repositório principal.

Justificação:

No TDD, comece escrevendo o teste antes do código real. Execute o teste, ele deve falhar. Escreva o código para fazê-lo passar. Rode o teste novamente para confirmação. Se passar, refatore o código e, por fim, integre-o no repositório principal.

2.1) Epics podem ser quebradas em User Stories com base em critérios como funcionalidade, tamanho, complexidade ou prioridade, facilitando o desenvolvimento incremental.

2.2) Critérios de aceitação em User Stories definem requisitos específicos, evitam ambiguidades e servem como base para testes de aceitação, garantindo compreensão mútua.

3.1) Testes unitários focam em unidades de código individuais, como funções, para detectar e corrigir erros de forma eficaz.

3.2) "Mocking" em testes unitários envolve substituir partes do sistema por objetos simulados (mocks) para isolar o código em teste.

4.1) Refatoração melhora a estrutura do código sem alterar seu comportamento, mantendo-o legível e eficiente.

4.2) Programação em pares envolve dois programadores trabalhando juntos, promovendo colaboração e qualidade do código.

4.3) No TDD, os desenvolvedores escrevem testes antes do código, criando funcionalidades orientadas por testes.

5.1) Métricas para avaliar Scrum ou XP incluem velocidade da equipe, qualidade do código, satisfação do cliente e entrega pontual de User Stories.

5.2) User Stories e Epics facilitam a comunicação entre equipes técnicas e não técnicas, alinhando expectativas de desenvolvimento.