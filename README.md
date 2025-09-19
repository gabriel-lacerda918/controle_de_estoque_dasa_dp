# controle_de_estoque_dasa_dp
challenge_sprint-3_dynamic_programming

# Dynamic Programming – Sprint 3

**INTEGRANTES**
- Fernanda Menon RM 554673
- Gabriel Lacerda RM 556714
- Luiza Macena RM 556237
- Roger Cardoso RM 557230

2ESPW

 Este notebook implementa **estruturas de dados e algoritmos clássicos** aplicados ao consumo de insumos hospitalares.

### Objetivos:
- Registrar consumo em ordem cronológica (**Fila / Queue**).
- Consultar em ordem inversa (**Pilha / Stack**).
- Localizar insumos usando busca **Sequencial** e **Binária**.
- Organizar dados por quantidade (**Merge Sort**) e validade (**Quick Sort**).
- Gerar relatório final.

<br /><br />

# **Explicação das Estruturas e Algoritmos Utilizados**

Para resolver o problema da falta de precisão no registro de consumo de insumos nas unidades de diagnóstico, foram aplicadas diferentes estruturas de dados e algoritmos clássicos, cada um com um papel específico:

1. Fila (Queue)
A fila foi utilizada para registrar o consumo diário de insumos na ordem cronológica em que ocorreram. Essa estrutura reflete o processo real de registro, onde os insumos consumidos em um determinado dia são adicionados ao final da fila e retirados na mesma ordem em que foram registrados (FIFO – First In, First Out). Isso permite acompanhar a evolução do consumo ao longo do tempo.

2. Pilha (Stack)
A pilha foi implementada para simular consultas em ordem inversa, ou seja, começando pelos insumos mais recentemente consumidos. Essa abordagem (LIFO – Last In, First Out) é útil em situações em que se deseja analisar rapidamente os últimos registros de consumo, por exemplo, para verificar um erro recente ou para auditoria imediata.

3. Busca Sequencial e Binária
Para localizar um insumo específico no registro, foram aplicadas duas estratégias:

- Busca Sequencial percorre toda a lista até encontrar o item desejado, sendo adequada para conjuntos de dados pequenos ou não ordenados.

- Busca Binária exige que os dados estejam previamente ordenados, mas permite encontrar rapidamente um insumo específico dividindo repetidamente a lista ao meio, reduzindo significativamente o tempo de busca em registros maiores.

4. Algoritmos de Ordenação (Merge Sort e Quick Sort)
Para organizar os insumos por quantidade consumida ou por data de validade, foram aplicados dois algoritmos de ordenação clássicos:

- Merge Sort, que divide os dados em sublistas menores e depois as combina ordenadas, garantindo eficiência mesmo em grandes conjuntos de dados.

- Quick Sort, que utiliza a técnica de partição em torno de um pivô, proporcionando rapidez na prática para organizar os registros.

Essas técnicas em conjunto permitem não apenas registrar e consultar o consumo diário de forma mais eficiente, mas também manter os dados organizados, possibilitando maior controle de estoque e previsão mais precisa da reposição de insumos.
