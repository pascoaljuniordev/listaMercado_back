# Sistema Lista de Mercado
## Requisitos
  - Ser capaz de gerenciar várias listas de mercado (e marcar o seu status de concluído ou não)
  - Ser capaz de cadastrar produtos e consultá-los
  - Ser capaz de incluir pordutos nas listas e especificar suas quantidades, bem como marcar se
o item já foi comprado ou não
  - Ser capaz de atribuir valores aos itens comprados para depois ter uma gestão dos custos da
lista
  - Ser capaz de adicionar quantidades (Kg, unidades, litors, etc..).


## Casos de uso - Produto
### Cadastrar produtos
   -Informar o nome de um detrminado produto e o sistema o armazena no banco

### Consultar Produtos
   -Informar palavras-chave para consultar ou mesmo buscar produtos a partir de uma lista

### Alterar dados de produtos
   -Basicamente alterar o nome do produto e ter sua efectivação no banco


## Casos de uso - Lista
### Criação de listas
   - Criar uma nova lista inserindo a data e o local onde foi feita a compra(nome do mercado/feira, etc)

### Apagar uma lista
  - Remover uma lista que foi criada por engano e remover todos os seus itens que foram criados

### Inserção de itens na lista
   - Criar um item associnado a uma lista e a um produto, bem como deixar disponível a possibilidade
de modificar a quantidade e preço que foi pago

### Alteração de itens da lista
   - Alterar apenas quantidade, preço pago e status

### Remoção de itens da lista
   - Poder remover um item que foi cadastrado na lista

### Fechamento da lista
   - Concluir a lista como sendo completa e gerar seu custo total a partir dos itens comprados
