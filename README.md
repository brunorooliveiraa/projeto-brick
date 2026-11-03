# 📱 Sistema de Gestão & Dashboard Inteligente - Brick

Um dashboard moderno, responsivo e inteligente para gestão completa de estoque, vendas, fluxo de caixa e faturamento, especialmente desenhado para revenda de celulares, eletrônicos e acessórios.

---

## 🚀 Funcionalidades

### 📊 Dashboard e Métricas Financeiras (KPIs em Tempo Real)
- **Patrimônio Total:** Cálculo automático do patrimônio (Caixa Líquido + Custo do Estoque atual).
- **Caixa Disponível:** Controle do saldo real (`Vendas + Aportes - Retiradas`).
- **Capital Injetado (Aportes):** Registro e histórico de aportes de dinheiro próprio no negócio.
- **Retiradas:** Acompanhamento de retiradas financeiras / pró-labore.
- **Investimento em Estoque:** Montante de capital alocado em aparelhos aguardando venda.
- **Lucro Líquido Realizado:** Lucro líquido acumulado das vendas concretizadas.
- **Lucro Esperado:** Projeção do lucro potencial das unidades atualmente em estoque.
- **Giro de Estoque:** Média de tempo em dias que os aparelhos levam para serem vendidos.

### 📦 Controle de Inventário & Vendas
- Cadastro ágil de itens/aparelhos com nome, custo unitário, preço sugerido de venda, quantidade e data de compra.
- Baixa rápida de vendas com registro da data de venda e cálculo imediato do lucro.
- Edição e exclusão de itens com confirmação segura.
- Tabela interativa com status visual (*Em Estoque* / *Vendido*).

### 📅 Desempenho Mensal
- Visão segmentada mês a mês de Faturamento, Lucro Realizado e Lucro Projetado.
- Gráficos/barras visuais de progresso de metas e vendas do mês vigente.

### ☁️ Sincronização em Nuvem & Backup
- **Nuvem em Tempo Real:** Conexão direta com Firebase Firestore para sincronização contínua.
- **Exportação & Importação JSON:** Backup completo dos dados em formato `.json` a qualquer momento com 1 clique.
- **Resiliência Offline:** Funciona via navegador sem depender de servidores locais complexos.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5 & CSS3:** Interface dark mode elegante, moderna e 100% responsiva (sem frameworks pesados).
- **JavaScript (ES6+):** Lógica reativa para cálculos financeiros e controle de estado.
- **Firebase Firestore:** Persistência de dados em tempo real na nuvem.

---

## 💻 Como Executar o Projeto

Como o projeto é construído como uma aplicação web nativa (*Single Page Application*), não é necessário compilar nem instalar dependências complexas.

1. Clone o repositório:
   ```bash
   git clone https://github.com/brunorooliveiraa/projeto-brick.git
   ```
2. Acesse a pasta do projeto:
   ```bash
   cd projeto-brick
   ```
3. Abra o arquivo `index.html` em qualquer navegador moderno (Chrome, Edge, Firefox, Brave):
   - Dê um duplo clique no arquivo `index.html`, ou
   - Use uma extensão como o *Live Server* do VS Code / Antigravity.

---

## 💾 Estrutura dos Arquivos

```text
├── index.html                     # Aplicação web completa (UI + Lógica + Integração)
├── meu_estoque_ajustado.json       # Dados de estoque de exemplo / backup
├── meu_estoque_backup (1) (1).json # Arquivo de backup auxiliar
├── .gitignore                     # Arquivos ignorados pelo Git
└── README.md                      # Documentação do projeto
```

---

## 📄 Licença

Este projeto é de uso pessoal e privado. Todos os direitos reservados.
