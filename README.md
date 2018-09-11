
# EntidadeMB

  
Decidimos criar esta ferramenta para que os utilizadores do sistema bancário português possam consultar a quem pertence uma determinada entidade de multibanco.
Uma vez que existem entidades utilizadas de forma maliciosa, utilizamos este meio para informar.


# 📗 Base de Dados

A lista de entidades está armazenada na base de dados *mysql*. 
Sempre que houverem sugestões aqui no repositório, será acrescentado na base de dados. 


## 👥 Utilizadores

Não existe a possibilidade de haver sistema de utilizadores nesta aplicação.


## 🔢 Entidades

As entidades são compostas por 5 números.

ex: `entidademb.info/:entidade`

## 🔍 Pesquisas


* `LOCAL` : As pesquisas são armazenadas no dispositivo do utilizador através da funcionalidade *[localStorage](https://medium.com/trainingcenter/simplificando-html5-web-storage-api-4ce0f904e0ee)*.

* `REMOTO` : Armazenado na base de dados, estes dados serão utilizados apenas para efeitos de estatística e nunca será revelado que utilizador pesquisou o veículo X.
* `ENTIDADE` : Quando pesquisado o número da entidade, serão mostradas as empresas correspondentes. 
* `EMPRESA` : Quando pesquisado o nome da empresa, serão mostradas as empresas correspondentes. 


# 📡 API

O acesso é público, porém é necessário requisitar uma chave de acesso *(token)*  através do e-mail:
mail@bluestage.net. No e-mail, especifique para que necessita da API, e indique o domíno/url onde esta irá requisitada.

URL da API
> entidademb.info/api


🤟 Colaborar & Ficha Técnica
-----------------

*Helppppp!*
* `Android e iOS` : A nossa praia 🏖️ é a web... se tens experiência numa destas plataformas e queres ajudar fala connosco.

*Resolvido.*
* `Progressive Web App` : É a maneira ideal que encontrámos para divulgar a aplicação porque quer o Google Chrome, quer o Safari, deixam adicionar o ícone no smartphone e aceder mesmo quando offline..
* `Alojamento` : O **EntidadeMB** está hospedado no nosso servidor interno.
* `Domínio` : Está registado com a [NameCheap.com](http://one.me/ptawsdls)
