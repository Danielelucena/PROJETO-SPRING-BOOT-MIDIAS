# Media Upload System

Este é um sistema de upload de arquivos simples desenvolvido com **Spring Boot**. O projeto permite o upload, listagem e download de arquivos, com suporte a diferentes tipos MIME como PDF, imagens (JPG, PNG), vídeos (MP4, AVI) e documentos do Microsoft Office (Excel, Word).

## Tecnologias Usadas

- **Spring Boot 3+**
- **Spring Web**
- **Spring Data JPA**
- **H2 Database (em memória)**
- **Thymeleaf** para renderização de templates HTML
- **Lombok** (opcional, para simplificar a geração de getters e setters)

## Funcionalidades

- **Upload de Arquivos**: Permite fazer upload de arquivos de vários tipos MIME (PDF, TXT, CSV, Imagens, Vídeos, etc.).
- **Listagem de Arquivos**: Exibe todos os arquivos enviados, junto com seus tipos MIME.
- **Download de Arquivos**: Permite fazer download dos arquivos armazenados.
- **Suporte a Tipos MIME**: Suporta os seguintes tipos de mídia:
  - `application/*`: Ex: PDF, JSON
  - `text/*`: Ex: TXT, CSV
  - `image/*`: Ex: JPG, PNG
  - `video/*`: Ex: MP4, AVI
  - `application/vnd.*`: Ex: Excel, Word

## Como Rodar o Projeto

### Pré-requisitos

Certifique-se de ter o **Java 17+** instalado na sua máquina. O projeto utiliza **Maven** para gerenciar as dependências.

### Passos para Executar

1. **Clone o repositório**:

```bash
git clone[ https://github.com/seu-usuario/media-upload-system.git](https://github.com/Danielelucena/PROJETO-SPRING-BOOT-MIDIAS.git)
