# Documentação do Projeto BreadMate

Esta documentação serve como um ponto de partida e deve ser expandida conforme o projeto evolui.

### Sobre o Projeto

O BreadMate é um sistema de gerenciamento de pedidos e inventário para padarias, focado em otimizar o processo de vendas, desde a escolha do produto pelo cliente até a entrega. Ele usa uma arquitetura de microserviços e é desenvolvido principalmente em Golang e React.

#### Principais Funcionalidades:

- Aplicativo móvel para pedidos de clientes
- Painel administrativo web para gestão de inventário e vendas
- Autenticação via redes sociais e Keycloak
- Pagamento via PIX e outras gateways de pagamento
- Integração com SMS para notificações
- Operações assíncronas para pedidos e pagamentos usando Kafka/RabbitMQ

### Configuração de Ambiente

- Node.js para o frontend
- Golang para o backend
- Docker e docker-compose para contêineres

#### Passos:

1. Clone o repositório
2. Execute `docker-compose up`

### Como Contribuir

Por favor, leia o CONTRIBUTING.md para detalhes.

---

## LICENSE.md

Este projeto está licenciado sob a licença MIT.

---

## SECURITY.md

Para relatar vulnerabilidades de segurança, por favor, contate o mantenedor principal do projeto.

---

## ROADMAP.md

- Integração com outros métodos de pagamento
- Implementação de IA para previsão de inventário
- Notificações em tempo real para atualizações de status do pedido

---

## MAINTAINERS.md

- Nome do Mantenedor: rssantan@gmail.com

---

## Outros Documentos

- **PITCH.md:** O sistema visa resolver os problemas associados com a gestão de pedidos em padarias, tornando o processo mais eficiente e menos propenso a erros.
- **TESTING.md:** Utilizamos Jest para testes no frontend e GoTest para o backend. Execute `npm test` ou `go test` para rodar os testes.
- **CHANGELOG.md:** Todas as mudanças serão documentadas aqui.
