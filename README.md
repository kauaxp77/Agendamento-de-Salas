<h1 align="center"> 
    🗓 Agendamento de Salas (Senai)🗓
</h1>

<p align="center">
  <strong>Sistema Crud e Gerenciador de Ambientes desenvolvido com PHP e MySQL visando atender as demandas de professores e alunos.</strong>
</p>

## 💻 Sobre o Projeto

Um portal construído para resolver um problema real: a gestão de infraestrutura de ambientes educacionais e de laboratórios do Senai.
Desenvolvido em PHP utilizando bibliotecas do lado cliente (Bootstrap) e MySQLi, ele oferece tanto interface Web completa para interações dos Professores, quanto um painel robusto para o encarregado da administração (Administrador).

Sua construção me permitiu aplicar de maneira muito firme conhecimentos fundamentais com Sessões, rotas validadas de autorização e criação de um portal responsivo clássico.

## 🚀 Tecnologias e Implementações
- **Front-End:** HTML5, CSS3, e JS utilizando Boostrap para os grid layouts e Modais interativos.
- **Back-End:** PHP utilizando modelagens nativas e `Sessions` para controle sensível de autenticação.
- **Banco de Dados:** Servidor MySQL (Tratativas com PDO/MySQLi diretas, queries complexas e relacionalidade).

## 📊 Módulos / Perfils

### Módulo do Professor (Usuário Geral)
- Acesso à Home Page para visualizar quais salas o Senai dispõe e suas lotações.
- Possibilidade de verificar o status da sala e alavancar o "Agendar Sala".
- Modificação interna dos dados de perfil.

### Módulo Admin
- Adicionar/Remover ou desativar Salas / Andares / Blocos pelo painel gerencial.
- Analisar todos os usuários cadastrados e verificar pedidos de contas que demandam a ação para utilização.
- Cancelar reservas e remanejar ambientes.
 
## ✍🏾 Testar localmente

1. Tenha o ambiente XAMPP (ou Apache + MySQL) em seu computador.
2. Clone este repositório no seu `htdocs`.
3. Suba o arquivo SQL presente no código para o `phpMyAdmin` garantindo que o banco está vivo, ele deve criar um database para conectar nas credenciais padrões `root`.
4. Entre no navegador e acesse a página index para logar no sistema!
