# Sistema de Gestão Comercial (SGC)

Projeto acadêmico para disciplina de Análise e Desenvolvimento de Sistemas.  
Gerencia clientes, produtos, vendas e relatórios para pequenos negócios.

## Tecnologias
- Java 21
- Spring Boot 3.2.5
- Spring Data JPA
- Spring Security + JWT (jjwt 0.9.1)
- MySQL 8
- Maven
- Swing (futura integração)

## Arquitetura
Sistema em cinco camadas: Apresentação → Controller → Serviço → Domínio → Persistência.  
Padrões de projeto utilizados: Repository, DTO, Builder.  
Documentação completa em `docs/Entrega1-Arquitetura.pdf`.

## Como executar (backend)

1. **Pré-requisitos:** JDK 21, Maven 3.9+, MySQL 8+.
2. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/sgc.git
   cd sgc/backend
