# Desafio Back-end RevPay

Primeiramente, obrigado pelo seu interesse em trabalhar conosco.

## Avisos antes de começar

- Crie um repositório no seu GitHub **sem citar nada relacionado a RevPay**.
- Faça seus commits no seu repositório.
- Envie o link do seu repositório para o email: renan.almeida@revpay.com.br e carlos.eduardo@revpay.com.br
- Você poderá consultar o Google, Stackoverflow ou algum projeto particular na sua máquina.
- Fique à vontade para perguntar qualquer dúvida aos recrutadores.

*Corpo do Email com o link do repositório do desafio*

>Seu Nome
>
>Link do repositório

### Sobre o ambiente da aplicação:

- Escolha o NodeJs ou qualquer biblioteca de NPM que se sinta **confortável** em trabalhar. Esse teste **não faz** nenhuma preferência, portanto decida por aquele com o qual estará mais seguro em apresentar e conversar com a gente na entrevista.

- Ainda assim, se optar por alguma biblioteca, sabemos que essas facilidades aumentam a produtividade no dia-a-dia mas aqui queremos ver o **seu** código e a sua forma de resolver problemas, é interessante pra gente ver a sua capacidade de criar uma solução.

## Para o dia da entrevista técnica
Na data marcada pelo recrutador tenha sua aplicação rodando na sua máquina local para execução dos testes e para nos mostrar os pontos desenvolvidos e possíveis questionamentos.
Faremos um code review junto contigo como se você já fosse do nosso time, você poderá explicar o que você pensou, como arquitetou e como pode evoluir o projeto.

## Objetivo: Atores e seus ambientes

Temos 2 tipos de usuários, os clientes final(revendedor) e lojistas, ambos têm carteira com dinheiro e realizam transferências entre eles. Vamos nos atentar **somente** ao fluxo de transferência entre dois usuários.

Requisitos:

- Para ambos tipos de usuário, precisamos do Nome Completo, CPF, e-mail e Senha. CPF/CNPJ e e-mails devem ser únicos no sistema. Sendo assim, seu sistema deve permitir apenas um cadastro com o mesmo CPF ou endereço de e-mail.

- Revendedores podem enviar dinheiro para lojistas. 

- Lojistas **só recebem** transferências, não enviam dinheiro para ninguém.

- Validar se o usuário tem saldo antes da transferência.

- A operação de transferência deve ser uma transação (ou seja, revertida em qualquer caso de inconsistência) e o dinheiro deve voltar para a carteira do usuário que envia. 

- Este serviço deve ser RESTFul.

# Avaliação

Apresente sua solução utilizando a biblioteca que você desejar, justificando a escolha.
Atente-se a cumprir a maioria dos requisitos, pois você pode cumprir-los parcialmente e durante a avaliação vamos bater um papo a respeito do que faltou.

## O que será avaliado e valorizamos.
- Documentação
- Código limpo e organizado (nomenclatura, etc)
- Conhecimento de padrões (design patterns, SOLID)
- Ser consistente e saber argumentar suas escolhas
- Apresentar soluções que domina
- Manutenibilidade do Código
- Arquitetura (estruturar o pensamento antes de escrever)

De acordo com os critérios acima, iremos avaliar seu teste para avançarmos para a entrevista técnica.
Caso não tenha atingido aceitavelmente o que estamos propondo acima, não iremos prosseguir com o processo.

## O que NÃO será avaliado
- Fluxo de cadastro de usuários e lojistas
- Frontend (só avaliaremos a API Restful)

## O que será um Diferencial
- Documentação
- Uso de JWT para autenticação