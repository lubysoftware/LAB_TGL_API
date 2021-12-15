# TGL API

Passos para inicialização do projeto:

1. git clone https://github.com/lubysoftware/LAB_TGL_API
2. yarn
3. configuração do .env de acordo com o arquivo .env.example
4. Executar msql e criar um banco de dados chamado **default (Exemplo de ferrameta => [https://laragon.org/download/]())**
5. node ace migration:run
6. node ace db:seed
7. node ace serve --watch
8. Os endpoints estarão na raiz desse projeto, você deve importá-lo no seu insomnia. O nome do arquivo é **TGL_ENDPOINTS.json**

**ATENÇÃO:** FIQUEM ATENTOS A ABA **_QUERY_ **NO ENPOIT DE **LISTAGEM DE APOSTAS.** ELA CONTÉM A FORMA DE FAZER AS FILTRAGENS
