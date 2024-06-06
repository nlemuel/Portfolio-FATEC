## Projeto Integrador: 2022-1

## Projeto 3º Semestre: ***PowerTech***.

### Introdução ao projeto

A PowerTech fará um sistema de cadastro com os valores de faturas de energia, água e gás, onde o cliente da TecSUS envia suas faturas para a empresa e o digitador trabalhará digitando os campos da fatura que vai ser referente ao serviço contratado com a TecSUS, pois infelizmente as faturas são geradas em PDF/IMG formato que não tem como fazer um tratamento inteligente de dados. Após feito a digitação dos dados de consumo, faremos um Dashboard de alta complexidade que vai mostrar dados para as análises mensais e anuais e médias de consumo para o setor de Gestão contatar os clientes caso seja emitida um alerta de alto consumo.

### Empresa parceira

Tecsus

***

### Visão do Projeto

A TecSUS realiza a coleta e processamento de contas de energia, água e gás para diversas empresas dos setores do atacado e varejo. Cada conta coletada precisa ter todos os seus campos digitados e salvos em banco de dados para eventuais consultas e análises técnicas/financeiras que podem trazer ao cliente oportunidades de redução de custos e alteração de contratos. Cada unidade do cliente pode possuir vários contratos (água, energia ou gás), cada contrato pode possuir uma ou mais contas (faturas de água, energia ou gás) por mês. Todos esses contratos estão ligados a uma concessionária de abastecimento.


### Solução

Criamos uma interface onde o digitar encontre facilidade e agilidade para digitar os arquivos recebidos para os gestores e administradores possam visualizar os dados nas dashboards. 

<img src="https://user-images.githubusercontent.com/37638307/172077554-e3137a58-a906-4c4d-8672-22484776c6c1.gif" width="500px" />
<img src="https://user-images.githubusercontent.com/37638307/172077556-fec5a643-28f5-4459-a2e0-a38bcf147d24.gif" width="500px" />
<img src="https://user-images.githubusercontent.com/37638307/172077557-6211465e-3f3c-40d3-968a-4c99f03d9f2f.gif" width="500px" />

### Lista de Requisitos 

Para a validação das entregas, utilizamos os seguintes critérios 

Requisitos Funcionais: 

<li>Cadastros de Unidades, Concessionárias, Contratos</li>
<li>Cadastro do usuário e seus perfis (administrador, gestor e digitador)</li>
<li>Cadastro (digitação) da conta de água, energia e gás</li>
<li>Registro de log de operações (cadastro e deleção)</li>
<li>Relatório de consumo total de água mensal, anual e média</li>
<li>Relatório de consumo total de energia mensal, anual e média</li>
<li>Relatório de consumo total de gás mensal, anual e média</li>  
<li>Geração de alertas de consumo acima da média (a média pode ser definida no cadastro 
do contrato)</li>

Requisitos Não Funcionais:

<li>Prezar pelo UX da tela de digitação das contas</li>
<li>Incluir atalhos no teclado</li>
<li>Permitir navegação entre campos por TAB ou seta</li>

***

### Link do git
[Acesse o Repositório](https://github.com/luks-ecdc/PowerTech-API-TecSUS)


### Tecnologias adotadas na solução:

- **Banco de Dados:** PostgreSQL;
- **Back-end:** JAva;
- **Front-end:** HTML, CSS, Bootstrap, Angular e Typescript;
- **Ferramentas:** Discord, Visual Studio Code, Figma, Git, Github, Trello e Excel;


### Contribuições pessoais

Desenvolvi as telas de cadastro de contas de água, luz e gás além das telas de upload de PDF/IMG e de visualização das faturas cadastradas. Participei do desenvolvimento do wireframe. Aprendi mais sobre o framework de frontend Angular, foi meu primeiro contato com esta ferramenta e pude aprender muito sobre ele durante as reuniões para tirar minhas dúvidas.

#### Soft skills

Flexibilidade: A capacidade de se adaptar a novas situações e mudanças utilizando novas ferramentas como o Angular e Bootstrap no frontend.

Pensamento crítico: A capacidade de analisar informações de diferentes ângulos para tomar decisões informadas no desenvolvimento das telas.

Criatividade: A capacidade de pensar fora da caixa durante o desenvolvimento do wireframe no figma.

Resolução de problemas: A capacidade de identificar problemas e encontrar soluções eficazes das tasks durante as sprints.

### Aprendizados Efetivos HS

- Desenvolver frontend: Sei desenvolver com autonomia;
- Typescript: Sei com autonomia;
- Angular: Sei com ajuda;
- Bootstrap: Sei utilizar com autonomia;
- Criação do prototipo das telas no figma: Sei com autonomia;
