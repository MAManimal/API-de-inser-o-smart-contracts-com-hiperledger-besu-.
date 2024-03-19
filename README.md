Procedimento da API passo a passo:

1. **Conexão com o nó Hyperledger Besu**: A API se conecta a um nó Hyperledger Besu em execução localmente, utilizando o endereço HTTP fornecido (http://localhost:8545).

2. **Execução do Protocolo ERC-404**: Antes de interagir com o contrato inteligente, a API executa o protocolo ERC-404. Isso pode incluir qualquer lógica ou processamento necessário para garantir que as condições do protocolo sejam atendidas antes da execução do contrato.

3. **Carga das Credenciais da Carteira**: As credenciais da carteira são carregadas usando a chave pública fornecida na API.

4. **Carregamento do Contrato Inteligente**: O contrato inteligente é carregado utilizando o endereço do contrato, o Web3j, as credenciais da carteira e o provedor de gás padrão.

5. **Chamada da Função do Contrato Inteligente**: Uma função específica do contrato inteligente é chamada. Isso pode incluir qualquer operação desejada no contrato, como transferência de tokens, execução de lógica de negócios, entre outras.

6. **Impressão do Hash da Transação**: O hash da transação resultante é impresso no console para fornecer feedback sobre o sucesso da execução da transação.

Este procedimento demonstra como a API interage com o Hyperledger Besu, executa um protocolo específico (ERC-404) antes de executar uma transação em um contrato inteligente, e fornece um exemplo básico de como isso pode ser implementado em Java com a biblioteca Web3j.
