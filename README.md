## Global Solution - Plataforma de Upskilling/Reskilling 2030+

## Nomes e RM:
- Matheus Taylor, RM556211
- Henrique Maldonado, Rm557270

## Descrição do Projeto
 A Plataforma de Upskilling/Reskilling 2030+ é uma API RESTful desenvolvida em Java com Spring Boot que visa preparar profissionais para os desafios do futuro do trabalho. Em um cenário onde tecnologias como IA, automação e análise de dados estão transformando o mercado, nossa plataforma oferece trilhas de aprendizagem focadas nas competências essenciais para as carreiras de 2030 e além.
 Este projeto foi desenvolvido como parte da Global Solution 2025 - O Futuro do Trabalho, alinhando-se com os Objetivos de Desenvolvimento Sustentável (ODS) da ONU, especialmente os ODS 4 (Educação de Qualidade), 8 (Trabalho Decente e Crescimento Econômico), 9 (Indústria, Inovação e Infraestrutura) e 10 (Redução das Desigualdades).

## Funcionalidades Principais
# CRUD Completo de Usuários
- Cadastro de profissionais na plataforma
- Gestão de perfis com área de atuação e nível de carreira
- Validação de dados com Bean Validation

# CRUD Completo de Trilhas de Aprendizagem
- Criação de trilhas focadas em competências do futuro
- Classificação por níveis (Iniciante, Intermediário, Avançado)
- Organização por focos principais (IA, Dados, Soft Skills, etc.)

# Recursos Técnicos Implementados
- Arquitetura em Camadas: Controller → Service → Repository
- API RESTful: Endpoints seguindo melhores práticas REST
- Persistência de Dados: Spring Data JPA com H2 Database
- Validação de Dados: Bean Validation com mensagens customizadas
- Tratamento de Exceções: Centralizado com @RestControllerAdvice
- Documentação Completa: README detalhado com exemplos de uso

## Tecnologias Utilizadas
- **Java**: 17
- **Spring Boot**: 3.2.0
- **Spring Data JPA**: Para persistência de dados
- **H2 Database**: Banco de dados em memória
- **Maven**: Gerenciamento de dependências
- **Bean Validation**: Para validação de dados

## Como Executar o Projeto

### Pré-requisitos
- Java 17 instalado
- Maven instalado

### Passos para execução

1. **Clone o repositório**:
   ```bash
   git clone <url-do-repositorio>
   cd upskilling-platform

2. **Instale as dependências**:
   ```bash
   mvn clean install

3. **Execute a aplicação**:
   ```bash
   mvn spring-boot:run

4. **Acesse a aplicação**:
   API: http://localhost:8080
   Console H2: http://localhost:8080/h2-console
   JDBC URL: jdbc:h2:mem:testdb
   User: sa
   Password: (vazio)
