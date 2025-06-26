# 🌟 AjudaSolidária

Plataforma digital desenvolvida como projeto extensionista para o curso de Ciência da Computação – Tema Integrador III. O sistema tem como objetivo facilitar doações e solicitações de ajuda, promovendo a solidariedade e o bem coletivo.

---

## ✅ Funcionalidades

### 👨‍👩‍👧‍👦 Público (usuários)
- Visualiza todos os itens disponíveis para doação.
- Dados atualizados automaticamente com o painel de administração.
- Design leve, responsivo e acessível.

🔗 Acesse o site público:  
👉 **[AjudaSolidária - Doações](https://leonardorobert.github.io/Ajuda.Solidaria/)**

---

### 🔧 Administração (Admin)
- Cadastro de novos itens.
- Edição de itens existentes.
- Exclusão de itens (com atualização imediata).
- Dados armazenados com `localStorage` (simulando banco de dados).

🔗 Acesse o painel administrativo:  
👉 **[AjudaSolidária - Admin](https://leonardorobert.github.io/Ajuda.Solidaria/admin/admin.html)**

---

## 🧱 Estrutura do Projeto

📁 admin/ → Painel CRUD (admin.html, admin.js, admin.css)
📁 backend/ → Arquivo JSON inicial (dados.json - base de dados simulada)
📁 docs/ → Requisitos, regras de negócio, diagramas
📄 index.html → Página inicial (usuário)
📄 style.css → Estilo da página pública
📄 script.js → Lógica da página pública (com localStorage)
📄 dados.json → Backup inicial dos dados (usado se localStorage estiver vazio)


---

## 🧩 Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript (ES6+)
- GitHub Pages (deploy)
- JSON como simulação de banco
- `localStorage` (salvamento no navegador)

---

## 📄 Requisitos Atendidos (PDF Oficial)

### ✅ Requisitos Funcionais:
- Cadastro, listagem, edição e exclusão de doações.
- Visualização de itens públicos.
- Armazenamento simulado via JSON/localStorage.

### ✅ Requisitos Não Funcionais:
- Interface leve, intuitiva e acessível.
- Compatível com navegadores modernos.
- Testável via GitHub Pages (funcionando 100%).

### ✅ ODS Trabalhado:
- **ODS 17 – Parcerias e Meios de Implementação**

---

## 📌 Regras de Negócio

- Todo item doado deve estar vinculado a um doador.
- Só é possível editar ou excluir itens pelo painel administrativo.
- Os dados são atualizados em tempo real no navegador do usuário (via localStorage).
- Itens "Entregues" podem ser removidos do sistema.
- O sistema inicia com um conjunto de dados padrão do arquivo `dados.json`.

---

## 🧪 Como usar

1. Acesse o painel admin:
   👉 [Admin](https://leonardorobert.github.io/Ajuda.Solidaria/admin/admin.html)
2. Cadastre, edite ou exclua os itens.
3. Acesse a visualização pública:
   👉 [Usuário](https://leonardorobert.github.io/Ajuda.Solidaria/)
4. Os dados serão sincronizados automaticamente no navegador!

---

## 📌 Observações Finais

- Este projeto é uma simulação completa de uma aplicação real.
- Utiliza apenas tecnologias do lado do cliente, sem necessidade de servidor backend.
- Cumpre integralmente os critérios do roteiro extensionista.
- Ideal para ser evoluído futuramente com banco de dados real e autenticação.

---

### 👨‍💻 Desenvolvido por:
**Leonardo Robert**  
Curso de Ciência da Computação – 3º Período  
Projeto Extensionista 2025 – Tema Integrador III
