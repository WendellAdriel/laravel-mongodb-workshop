# Workshop - Usando MongoDB com Laravel

**Professor:** Wendell Adriel Luiz Silva - [WendellAdriel](https://github.com/WendellAdriel)

## Ementa

- Configuração do ambiente
    - Verificação da versão do PHP e do [MongoDB](https://www.mongodb.org/)
    - Instalação do driver PHP para MongoDB
- Iniciando o projeto
    - Criando o projeto do 0 com o [Composer](https://getcomposer.org/)
    - Instalando o [pacote](https://github.com/jenssegers/laravel-mongodb) para trabalhar com o MongoDB
    - Configurando o BD
- Schemas
    - Suporte do MongoDB ao Schema Builder do Laravel
- Query Builder
    - Retornando todos documentos de uma coleção
    - Procurando dados em uma coleção
        - Where / Or / And
        - Where utilizando arrays
        - Where com between
        - Where com null
        - Order by
        - Offset e Limit
        - Distinct
        - Group By
        - Aggregations
        - Like
        - Utilizando operadores específicos do MongoDB
            - Exists
            - All
            - Size
            - Regex
            - Type
            - Mod
    - Entendendo e usando o Soft deleting
- Inserindo, atualizando e deletando dados
- Trabalhando com datas utilizando o [Carbon](http://carbon.nesbot.com/docs/)
- Relacionamentos entre coleções
    - hasOne
    - hasMany
    - belongsTo
    - belongsToMany
    - embedsOne
    - embedsMany
- Aplicações com BD híbrido (MongoDB e MySQL)
- Operações específicas do MongoDB
    - Upsert
    - Projections
    - Push
    - Pull
    - Unset
    - Cursor timeout
- Log e Cache de Queries
