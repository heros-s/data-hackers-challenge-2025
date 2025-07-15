### 2.1 Estrutura
Uma série do pandas é uma estrutura de dados unidimensional rotulada, semelhante a um array, lista ou coluna de uma tabela

### 2.2 Índice
Cada elemento da série possui um índice associado, permitindo acesso eficiente por rótulo ou posição.

Ex: `y = pd.Series([1,2,3,4])`

### 2.3 Elementos
Possui 4 elementos principais:
- Valores: Conjunto de dados armazenados na série, que podem ser de qualquer tipo (números, strings, datas, etc.).
- Tipo: - Tipo de dado (dtype) dos valores contidos na série, como int64, float64, object, entre outros.
- Nome: Identificador opcional atribuído à série, útil para rotulá-la em DataFrames ou visualizações.
- Índices: Rótulos associados a cada valor, usados para acessar ou localizar dados na série.