# MotoTrack 🚀

Sistema de Rastreamento de Motos com RFID desenvolvido em ASP.NET Core 8.0 + EF Core + Oracle.

## 🎯 Visão do Projeto

**MotoTrack** é uma solução IoT para rastreamento inteligente de motocicletas, integrando leitores RFID a uma API RESTful. O objetivo é proporcionar visibilidade em tempo real da localização das motos, permitindo controle, segurança e eficiência em operações logísticas ou de transporte.

## 🧩 Problema

Empresas e usuários que dependem de motocicletas para logística enfrentam desafios como:

- Falta de rastreabilidade em tempo real;
- Dificuldade em associar motos a locais e eventos;
- Processos manuais e falhos na coleta de dados operacionais.

## 💡 Solução

O **MotoTrack** propõe:

- Leitura automatizada via sensores RFID;
- API centralizada para registrar e consultar leituras;
- Visualização estruturada dos dados de rastreamento;
- Escalabilidade para múltiplos leitores e veículos.

---

## 🏗️ Arquitetura da Solução (TOGAF + ArchiMate)

### 🔭 Visão da Arquitetura

Estrutura modular baseada em camadas lógicas: negócio, aplicação e tecnologia. Usa ArchiMate para representar a integração dos componentes.

### 🧱 Arquitetura de Negócio

- Entidades: Moto, Leitor RFID, Registro de Leitura.
- Processos: Cadastro de veículos, leituras automáticas, consulta de histórico.

### ⚙️ Arquitetura de Sistema

- API RESTful em ASP.NET Core 8.0
- Camada de persistência com EF Core
- Endpoints para Motos, Leitores e Registros
- Swagger/OpenAPI para documentação

### 💾 Arquitetura de Tecnologia

- Banco de Dados Oracle (via EF Core)
- Hospedagem em ambiente .NET
- Integração com sensores RFID
- Suporte a HTTPS e autenticação futura

---

## 🛠️ Tecnologias Utilizadas

- ASP.NET Core 8.0
- Entity Framework Core
- Oracle Database
- Swagger / OpenAPI
- C#
- Archi (para modelagem ArchiMate)

---

## 📌 Como Rodar

```bash
dotnet restore
dotnet build
dotnet run
```

> Configure a string de conexão Oracle em `appsettings.json`.

---

## Video pitch

https://studio.youtube.com/video/3k1S9CXILw8/edit

---

## Equipe do Projeto

| **Angello Turano** **RM: 556511** | **Cauã Sanches** **RM:558317** | **Leonardo Bianchi** **RM:558576** |

---
