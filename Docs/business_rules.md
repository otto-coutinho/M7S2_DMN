<h1>Regras de Negócio</h1>

<p align="justify">
&emsp;&emsp; As regras de negócio são um conjunto de diretrizes e restrições que definem como um negócio deve operar. Elas são essenciais para garantir a consistência, a integridade e a eficiência das operações de uma empresa. <br>
&emsp;&emsp; As regras de negócio ajudam a definir como os processos devem ser executados, quais são as políticas e procedimentos a serem seguidos, quais são as restrições e validações aplicáveis aos dados e como as decisões devem ser tomadas.
</p>

<h2>Tabela de Regras</h2>

| Setor | Cargos | Tarefas | Regras de Negócio | Dados Manipulados | Tipo de Registro |
|---|---|---|---|---|---|
| Compras | Analista de Compras | Criação de Requisição de Compra | A requisição só pode ser criada se houver aprovação do gestor do departamento solicitante | Item, quantidade, descrição, data de entrega, centro de custo, departamento solicitante | Requisição de Compra |
| Compras | Analista de Compras | Cotação de Fornecedores | A cotação deve considerar o prazo de entrega, condições de pagamento e qualidade do produto/serviço | Fornecedor, item, preço, prazo de entrega, condições de pagamento | Cotação
| Compras | Analista de Compras | Emissão de Ordem de Compra | A ordem de compra só pode ser emitida após a aprovação das cotações | Fornecedor, item, quantidade, preço, prazo de entrega, condições de pagamento | Ordem de Compra
| Compras | Analista de Compras	| Recebimento de Mercadoria	| A mercadoria recebida deve ser conferida com a nota fiscal e a ordem de compra | Item, quantidade, número da nota fiscal, data de recebimento | Nota Fiscal de Entrada
| Compras | Coordenador de Compras | Aprovação de Pagamentos | O pagamento ao fornecedor só pode ser aprovado após o recebimento da mercadoria e a conferência da nota fiscal | Fornecedor, valor do pagamento, data do pagamento, condições de pagamento | Pagamento
