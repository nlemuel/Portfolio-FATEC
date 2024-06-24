## Projeto Integrador: 2024-1

## Projeto 5º Semestre: ***CodeLab***.

### Introdução ao projeto

Na indústria e em embarcações de exploração de petróleo, existem locais de acesso restrito,
denominados redzones. Por segurança, nestas redzones deve haver o monitoramento da
quantidade de acessos. Atualmente utiliza-se câmeras nos locais e guardas realizam o
monitoramento visual e anotam em planilha. Por ser manual, a anotação é falha e a geração de
relatórios trabalhosa. O objetivo é automatizar o processo com o uso de uma inteligência artificial de visão computacional.

### Empresa parceira

Altave

***

### Visão do Projeto

A proposta é o desenvolvimento de um sistema automático para contabilidade do número
de pessoas entrando e saindo de cada redzone. O sistema deve fornecer uma interface que seja possível ver a quantidade pessoas em tempo real
no local, e fazer consulta para um período selecionado pelo usuário. O sistema poderá monitorar
diversas redzones em cada departamento, portanto, será necessário que o acesso seja restrito a
cada um guarda de cada departamento. Apenas o gerente de segurança deverá ter acesso aos
dados de todos os departamentos.

### Solução

Iniciamos o desenvolvimento da inteligência artificial utilizando o modelo Yolo v8 para a detecção de pessoas evoluindo para construção de nosso própio modelo. Desenvolvemos uma lógica de área de interesse para detectar se a pessoa está entrando ou saindo da redzone com python. No desenvolvimento da interface utilizamos o Vue e Java para gerenciamento das redzones e visualização dos relatórios.

## :flags: Gifs de Apresentação da Sprint1

#### Entrega da Sprint 1 (14/04/2024)

https://github.com/CodeLabFatec/ProjetoIA/assets/26208169/b5afeb08-b09b-4299-91e5-d947d4096e13

https://github.com/CodeLabFatec/ProjetoIA/assets/26208169/7c4fe701-741c-4c8f-8cc9-7c89e986cfad


#### Entrega da Sprint 2 (05/05/2024)

https://github.com/CodeLabFatec/ProjetoIA/assets/26208169/1da50ae4-1f56-4504-b656-29433163427d


#### Entrega da Sprint 3 (26/05/2024)

https://github.com/CodeLabFatec/ProjetoIA/assets/26208169/88175ff0-7b3b-4269-8c8b-be6a6094122b

https://github.com/CodeLabFatec/ProjetoIA/assets/26208169/6672e903-b83f-49e7-9f34-249617f92f08


#### Entrega da Sprint 4 (16/06/2024)

https://github.com/CodeLabFatec/ProjetoIA/assets/26208169/4c4bc248-2616-4223-a8d7-1e7209b8bb07

### Você pode acessar o manual do usuário acessando esse [Link](/docs/MANUAL%20DO%20USUÁRIO.pdf)

<br />

### Lista de Requisitos 

Para a validação das entregas, utilizamos os seguintes critérios 

### Requisitos Funcionais:
- RF1 - Desenvolver uma interface web intuitiva, com autenticação;
- RF2 - Desenvolver um Dashboard de indicadores por períodos;
- RF3 - Filtros de período para análise dos dados;
- RF4 - Geração de relatórios para compartilhamento.

### Requisistos Não Funcionais
- RNF1 - Manual do Usuário;
- RNF2 - Documentação do sistema;
- RNF3 - Guia de instalação;
- RNF4 - Acesso a organização do desenvolvimento (kanban, git...)

***

### Link do git
[Acesse o Repositório](https://github.com/CodeLabFatec/ProjetoIA)


### Tecnologias adotadas na solução:

- **Banco de Dados:** MySQL;
- **Back-end:** Java;
- **Front-end:** Vue, Typescript;
- **Ferramentas:** Visual Studio Code, Figma, Git e Github;


### Contribuições pessoais

Desenvolvi habilidades técnicas trabalhando em conjunto com os integrantes da equipe no desenvolvimento da inteligência artificial, frontend e backend da aplicação. Na primeira sprint eu foquei no desenvolvimento da área de interesse e toda lógica de detecção e contagem das pessoas que entravam e saiam das redzones. Na segunda sprint desenvolvi a sidebar para o front e refinei mais algumas coisas na IA. Na terceira sprint realizei o CRUD de áreas e criei a tabela de áreas no banco de dados.

#### Soft skills

Entre soft skills, consegui participar ativamente das reuniões e entrega dos requisitos.

Flexibilidade: A capacidade de se adaptar a novas situações e mudanças apresentadas pelo cliente a cada sprint e participação no desenvolvimento da IA, frontend e backend. 

Resiliência: Encontrei muitas dificuldades durante o desenvolvimento do projeto e precisei desenvolver a habilidade de lidar com a pressão para fazer as entregas em meio a dificuldade técnica encontrada.

Negociação: Habilidade de chegar a acordos mutuamente benéficos durante a distribuição de tasks no início das sprints. 

Inteligência emocional: Durante o projeto tive de reconhecer e gerenciar minhas emoções para que elas não afetassem meu desempenho durante as sprints.

### Aprendizados Efetivos HS

- Desenvolvimento visão computacional: Sei desenvolver com ajuda;
- Desenvolvimento backend com Java: Sei com ajuda;
- Banco de dados: Sei com autonomia;
- Desenvolvimento frontend com Vue: Sei com autonomia.
