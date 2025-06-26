# 🚀 Delivery Tech API

Sistema de delivery moderno desenvolvido com Spring Boot 3.2.x e Java 21, utilizando as mais recentes funcionalidades da linguagem.

## 📋 Sobre o Projeto

Este projeto foi desenvolvido como parte da disciplina **Arquitetura de Sistemas** e representa a base de um sistema de delivery completo. A aplicação demonstra o uso de tecnologias modernas e boas práticas de desenvolvimento.

## 🛠️ Tecnologias Utilizadas

### Core
- **Java 21 LTS** - Versão mais recente com recursos modernos
- **Spring Boot 3.2.x** - Framework principal
- **Maven** - Gerenciamento de dependências

### Dependências
- **Spring Web** - APIs REST
- **Spring Data JPA** - Persistência de dados
- **H2 Database** - Banco em memória para desenvolvimento
- **Spring Boot DevTools** - Ferramentas de desenvolvimento#

## ⚡ Recursos Modernos do Java 21

Este projeto aproveita os recursos mais recentes do Java:

- **Records** - Para DTOs imutáveis e type-safe
- **Text Blocks** - Para strings multilinha legíveis
- **Pattern Matching** - Para código mais expressivo
- **Virtual Threads** - Para alta concorrência (preparado para uso futuro)
- **Sealed Classes** - Para hierarquias controladas (quando aplicável)

## 🚀 Como Executar

### Pré-requisitos
- **JDK 21** instalado e configurado
- **Git** para controle de versão
- **IDE** com suporte a Java (VS Code recomendado)

### Passos para execução

1. **Clone o repositório**
   ```bash
   git clone https://github.com/[usuario]/delivery-api-[nome].git
   cd delivery-api-[nome]
   ```

2. **Execute a aplicação**
   ```bash
   # Via Maven Wrapper (recomendado)
   ./mvnw spring-boot:run

   # Ou via Maven (se instalado)
   mvn spring-boot:run
   ```

3. **Acesse a aplicação**
   - API: http://localhost:8080
   - Console H2: http://localhost:8080/h2-console##
