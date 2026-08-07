# Resumo da Aula — Introdução aos Servidores Web

## 📚 Tema

**Fundamentos de servidores e segurança — Introdução aos servidores web**

A aula apresenta o funcionamento dos **servidores web**, seus principais tipos, configuração básica, segurança e desempenho.

## 🌐 O que é um servidor web?

Um **servidor web** é um software responsável por receber solicitações **HTTP** de navegadores ou outros clientes, processá-las e enviar uma resposta.

### Funcionamento

```text
Cliente
   ↓
Request (solicitação HTTP)
   ↓
Servidor Web
   ↓
Processamento
   ↓
Response (resposta)
   ↓
Cliente
```

A resposta pode conter:

* Página HTML
* Arquivos
* Dados em JSON

## 🖥️ Tipos de servidores

| Tipo                      | Função                                               |
| ------------------------- | ---------------------------------------------------- |
| **Servidor HTTP**         | Processa solicitações e respostas HTTP               |
| **Servidor de aplicação** | Executa códigos no servidor e gera conteúdo dinâmico |
| **Servidor de arquivos**  | Armazena e distribui arquivos                        |

## ⚙️ Principais servidores web

### Apache

* Popular e amplamente utilizado.
* Possui alta compatibilidade.
* Indicado para projetos que exigem compatibilidade.

### Nginx

* Focado em **alta performance**.
* Possui boa **escalabilidade**.
* Indicado para servidores com grande volume de tráfego.

## 🔧 Configuração básica

### 1. Instalação do Apache

```bash
sudo apt update
sudo apt install apache2
```

### 2. Instalação do Nginx

```bash
sudo apt update
sudo apt install nginx
```

## 🔌 Configuração das portas

As principais portas utilizadas são:

* **80 → HTTP**
* **443 → HTTPS**

Exemplo:

```bash
sudo ufw allow 80
sudo ufw allow 443
```

## 🔒 Segurança

Os **certificados SSL** são utilizados para proteger os dados transmitidos entre o cliente e o servidor.

A aula apresenta o **Let's Encrypt** com o Certbot:

```bash
sudo apt install certbot python3-certbot-nginx
sudo certbot --nginx
```

## 🟢 Nginx + Node.js

O Nginx pode ser utilizado para direcionar as requisições para uma aplicação **Node.js**.

Instalação:

```bash
sudo apt install nodejs
sudo apt install npm
```

A aplicação Node.js pode funcionar, por exemplo, na porta `3000`, enquanto o Nginx recebe as requisições e encaminha o tráfego para ela.

## 🚨 Desempenho e alta demanda

Quando existe grande quantidade de usuários, o servidor pode ficar **sobrecarregado**, causando lentidão e problemas de acesso.

É importante:

* Monitorar o desempenho.
* Otimizar a configuração do servidor.
* Escolher um servidor adequado.
* Preparar o sistema para grandes volumes de tráfego.
* Garantir a escalabilidade da aplicação.

## 📝 O que foi aprendido?

1. Como funciona um **servidor web**.
2. Como são processadas as **requisições HTTP**.
3. Como configurar **Apache e Nginx**.
4. A importância da **segurança e dos certificados SSL**.
5. Como preparar servidores para grandes volumes de tráfego.
6. A importância do **desempenho e da escalabilidade**.

## 🎯 Resumo final

> Um **servidor web** recebe requisições dos clientes, processa essas solicitações e devolve respostas. Para uma aplicação funcionar corretamente, o servidor precisa ser configurado considerando **desempenho, segurança, estabilidade e escalabilidade**.
