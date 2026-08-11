<h1 align="center">
  🗓 Agendamento de Salas (SENAI) 🗓
</h1>

<p align="center">
  <a href="#-sobre-o-projeto">Sobre</a> &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-tecnologias">Tecnologias</a> &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-funcionalidades">Funcionalidades</a> &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-visual-do-projeto">Visuais</a> &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-como-executar">Como Executar</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP">
  <img src="https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
  <img src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
</p>

<br>

## 💻 Sobre o Projeto

O **Agendamento de Salas** é um portal completo e intuitivo desenvolvido para solucionar desafios reais na gestão da infraestrutura de ambientes educacionais e laboratórios da rede SENAI. 

Construído em PHP com banco de dados MySQL, o sistema fornece uma interface web dinâmica e responsiva (utilizando o Bootstrap) para que professores possam reservar salas e administrar suas disciplinas em laboratórios práticos. Além disso, a aplicação conta com um **painel gerencial robusto** focado na administração, permitindo controle total sobre os usuários, loteamentos e criação de novos ambientes de ensino.

O projeto representou uma oportunidade incrível para a aplicação de conceitos sólidos de back-end: **CRUD completo, relacionamento entre tabelas, sessões para mecanismos de autenticação (Login protegido e Rotas fechadas), além de modelagens nativas do PHP**.

---

## 🚀 Tecnologias e Ferramentas

Esse sistema foi construído e padronizado utilizando as seguintes tecnologias:

- **Front-end**:
  - `HTML5` e `CSS3`
  - `JavaScript` (Manipulação de modais interativos)
  - `Bootstrap` (Responsividade e Grid Layouts)
- **Back-end**:
  - `PHP` (Lógica de negócios e controle de Sessions em rotas bloqueadas)
- **Banco de Dados**:
  - `MySQL` (Integrações com PDO/MySQLi diretas, relacionamentos base e deletes em cascata para exclusão de andares/blocos)
- **Infraestrutura e Ferramentas**:
  - `XAMPP` (Apache e ambiente MySQL local)
  - `phpMyAdmin`

---

## ✨ Funcionalidades

O sistema foi arquitetado com base em rotas condicionais e níveis de acesso, entregando visões específicas:

### 👨‍🏫 Acesso Professor (Usuário Geral)
- **Visão Funcional**: Acesso à página inicial (Landing Interface) para visualizar em blocos todas as salas cadastradas e suas informações correspondentes (Andar, Capacidade e Descrição).
- **Agendamentos**: Verificação de status na lista e possibilidade de enviar uma nova solicitação de laboratório em data e hora.
- **Perfil**: Área logada para alteração dos próprios dados e informações do sistema.

### 🛡️ Acesso Administrador (Gestão Total)
- **Gestão de Infraestrutura e Espaços**: Painéis de criação, edição e remoção completa para:
  - Salas / Laboratórios
  - Andares
  - Blocos
- **Central de Contas**: Sistema de moderação no qual cada usuário recém cadastrado fica "pendente", aguardando a liberação (aprovar conta) ou negação pelo Administrador Geral da Unidade.
- **Controle Administrativo das Reservas**: Acesso à cancelamentos remotos de reservas ou remanejamento forçados devido a manutenções repentinas em laboratórios.

---

## 📸 Visual do Projeto

Aqui estão algumas das telas e interações centrais do sistema, que comprovam o UI e funcionamento na prática:

<p align="center">
  <img src="ImagensGit/Sistemas Agenda (1).png" width="48%" alt="Apresentação 1">
  <img src="ImagensGit/Sistemas Agenda (2).png" width="48%" alt="Apresentação 2">
</p>

<p align="center">
  <img src="ImagensGit/Sistemas Agenda (3).png" width="48%" alt="Apresentação 3">
  <img src="ImagensGit/Sistemas Agenda (4).png" width="48%" alt="Apresentação 4">
</p>

> *Na pasta interna `ImagensGit` constam as demais impressões das outras páginas de navegação, relativas aos diferentes perfis.*

---

## ⚙️ Como Executar Localmente

Basta seguir os passos abaixo para testar este projeto em sua própria máquina:

### 1. Pré-Requisitos
Você necessita de um ambiente como **XAMPP**, **WAMP** ou **Laragon** (Que suba um servidor Apache unificado com MySQL).

### 2. Instalando
1. Faça o clone deste repositório para o diretório local do servidor (Exemplo com XAMPP: pasta interna do `htdocs`).
   ```bash
   git clone https://github.com/seugithub/agendamento-de-salas.git
   ```
2. Abra o painel gerenciador da sua ferramenta (XAMPP Panel) e inicie os serviços **Apache** e **MySQL**.
3. Acesse em seu navegador a dashboard do seu banco: `http://localhost/phpmyadmin/`.
4. Crie um novo banco de dados vazio e **importe o script `ambientes.sql`**, localizado na raiz deste repositório para recriar as tabelas base e popular os dados de teste.

### 3. Acessando a Plataforma
Pronto! Com o Apache rodando, acesse a pasta raiz onde o repositório foi clonado no navegador:
`http://localhost/Agendamento-de-Salas/agendamento/login.php`

> **Credenciais de Teste Administrativo:**
> * **E-mail**: `adm@gmail.com`
> * **Senha**: `123`
> *(Ou você pode criar e aprovar seus próprios usuários!)*

---

<p align="center">
  Desenvolvido com 💼 para fins educacionais e de portfólio.
</p>
