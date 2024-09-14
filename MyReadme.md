
Etapa 1
Feito o download do repositório oficial do Jellyfin no GitHub para pasta local.
Criado o repositório no GitHub, de nome Sistematiza-o_DOUGLAS_TELES
Criado a BRANCH feature/sistematizacao e feito checkout.

Etapa 2 
Criação da pasta Workflows, para criação do arquivo YAML(jellyfin-ci.yml).

Etapa 3 
Configuração do arquivo jellyfin-ci.yml
Nesta etapa de configuração ao ser criada o arquivo jellyfin-ci.yml, deu erro na geração da BUILD, em Restore dependências. Onde foi verificado que a versão do DOTNET, não estava de acordo ao pré-requisito para a preparação do ambiente de desenvolvimento. Ao analisar o README.md do JELLYFIN, foi identificado que era preciso da versão instalada .NET 8.0 SDK.

Etapa 4
Build successfully
