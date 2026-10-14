# 🧸 EcommerceToys — E-commerce Especializado em Brinquedos & Colecionáveis

> 🚧 **Status do Projeto: EM INÍCIO DE DESENVOLVIMENTO**  
> Este projeto está em estágio inicial de concepção e modelagem, com arquitetura baseada no ecossistema moderno do Next.js e Prisma ORM.

---

## 🎯 Proposta

O **EcommerceToys** foi idealizado para ser uma plataforma moderna e imersiva de comércio eletrônico focada no nicho de brinquedos infantis, jogos educativos e colecionáveis.

### 🧩 Objetivos & Arquitetura Inicial

- **Frontend & Server Components:** Next.js 15 (App Router), React 19 e Tailwind CSS.
- **Autenticação:** Auth.js (NextAuth) com suporte a sessões protegidas para clientes e painel administrativo.
- **Modelagem de Dados:** Prisma ORM com schemas para catálogo de produtos, categorias infantis, carrinho de compras e controle de pedidos.
- **Estrutura Modular:**
  - `app/cadastro` e `app/login`: Fluxo de onboarding de clientes.
  - `app/carrinho` e `app/checkout`: Funil de compra simplificado.
  - `app/admin`: Painel inicial para gestão de estoque e produtos.

---

## 🚀 Como Executar Localmente

```bash
# Clone o repositório
git clone https://github.com/OtavioFFarina/EcommerceToys.git
cd EcommerceToys/ecotoys

# Instale as dependências
npm install

# Configure o ambiente
cp .env.example .env

# Sincronize o banco com o Prisma
npx prisma generate
npx prisma db push

# Inicie o servidor de desenvolvimento
npm run dev
```

Acesse em: **[http://localhost:3000](http://localhost:3000)**

---

## 👨‍💻 Autor
Desenvolvido por **[Otávio Farina](https://github.com/OtavioFFarina)**.
