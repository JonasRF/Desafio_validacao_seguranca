### Desafio Validação e Segurança
Implemente as funcionalidades necessárias para que os testes do projeto abaixo passem 
(assista o vídeo explicativo e baixe o projeto no conteúdo anexo ao vídeo).

Este é um sistema de eventos e cidades com uma relação N-1 entre eles:

![image](https://github.com/JonasRF/Desafio_validacao_seguranca/assets/77034798/53e1c6ba-19df-447a-a9b6-daa408d9608c)

## Regras de controle de acesso:
  - Somente rotas de leitura (GET) de eventos e cidades são públicas (não requer login).
  - Usuários CLIENT e/ou ADMIN podem inserir novos eventos (POST).
  - Os demais acessos são permitidos apenas a usuários ADMIN.

## Regras de validação de City:
  - Nome não pode ser vazio

## Regras de validação de Event:
  - Nome não pode ser vazio
  - Data não pode ser passada
  - Cidade não pode ser nula

