
# Projeto de Conjunto de Espalhamento

Este projeto contém implementações de conjuntos de espalhamento em Java, incluindo uma versão genérica, juntamente com classes de teste para demonstrar seu uso e funcionalidade.

## Estrutura do Projeto

### Classes Principais

1. **ConjuntoEspalhamento**
   - Implementa um conjunto de espalhamento específico para strings.
   - Métodos principais:
     - `adiciona(String palavra)`: Adiciona uma palavra ao conjunto.
     - `remove(String palavra)`: Remove uma palavra do conjunto.
     - `contem(String palavra)`: Verifica se uma palavra está no conjunto.
     - `pegaTodas()`: Retorna todas as palavras no conjunto.
     - `tamanho()`: Retorna o número de palavras no conjunto.
     - `imprimeTabela()`: Imprime a tabela de espalhamento.

2. **ConjuntoEspalhamentoGenerico**
   - Implementa um conjunto de espalhamento genérico que pode armazenar objetos de qualquer tipo.
   - Métodos principais:
     - `adiciona(Object objeto)`: Adiciona um objeto ao conjunto.
     - `remove(Object objeto)`: Remove um objeto do conjunto.
     - `contem(Object objeto)`: Verifica se um objeto está no conjunto.
     - `pegaTodos()`: Retorna todos os objetos no conjunto.
     - `tamanho()`: Retorna o número de objetos no conjunto.
     - `imprimeTabela()`: Imprime a tabela de espalhamento.

### Classes de Teste

1. **TesteConjuntoEspalhamento**
   - Testa a classe `ConjuntoEspalhamento` com exemplos de strings.
   - Demonstra a adição, remoção, verificação de existência, e impressão das palavras no conjunto.

2. **TesteConjuntoGenerico**
   - Testa a classe `ConjuntoEspalhamentoGenerico` com exemplos de strings.
   - Demonstra a adição e listagem dos objetos no conjunto.

3. **TesteEspalhamento**
   - Testa a classe `ConjuntoEspalhamento` adicionando 100 números e imprimindo a tabela de espalhamento.

4. **TesteHashSet**
   - Testa a classe `HashSet` da biblioteca padrão do Java para comparação com as implementações de espalhamento personalizadas.

## Como Executar

1. Compile todas as classes:
   ```sh
   javac ConjuntoEspalhamento.java ConjuntoEspalhamentoGenerico.java TesteConjuntoEspalhamento.java TesteConjuntoGenerico.java TesteEspalhamento.java TesteHashSet.java
   ```

2. Execute as classes de teste:
   ```sh
   java TesteConjuntoEspalhamento
   java TesteConjuntoGenerico
   java TesteEspalhamento
   java TesteHashSet
   ```
