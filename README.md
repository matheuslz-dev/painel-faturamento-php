# Sistema de Gestão e Faturamento Automotivo

Plataforma web completa desenvolvida para o gerenciamento de serviços automotivos, controle financeiro de clientes e integração de dados de despachante/lojas.

## 💻 Telas do Sistema

*(Arraste e solte o print da tela da tabela de faturamentos aqui)*
*(Arraste e solte o print da tela de pagamento/dar baixa aqui)*

## 🛠️ Tecnologias e Ferramentas
* **Back-end:** PHP estruturado utilizando PDO para maior segurança nas consultas.
* **Banco de Dados:** MySQL/MariaDB com modelagem relacional (tabelas de clientes, pedidos, faturamentos e pagamentos).
* **Front-end:** HTML5, CSS3 (Bootstrap) e JavaScript (jQuery/DataTables).
* **Comunicação Assíncrona:** Uso intenso de AJAX para recarregar tabelas e processar filtros de datas em tempo real, sem recarregar a página.

## ⚙️ Principais Desafios e Soluções
* **Motor de Faturamento Complexo:** Desenvolvimento de lógica em PHP para cruzar dados de pedidos realizados versus pagamentos efetuados, calculando saldo devedor histórico e dívidas mensais com precisão.
* **Tabelas Dinâmicas:** Criação de relatórios de fechamento em que as colunas de meses se adaptam dinamicamente baseadas no status de pagamento do cliente.
* **Gestão de Serviços:** Catalogação de taxas variadas (Vistoria, Placas, ATPV, Renave, Honorários) consolidadas em relatórios de impressão para cobrança.
