# 💰 Financial Control SaaS  
*Gerenciador financeiro pessoal com design premium e análises avançadas*

<div align="center">

![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![D3.js](https://img.shields.io/badge/D3.js-F9A03C?style=for-the-badge&logo=d3.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)

**Angular 18+ • Zoneless • Signals • Soft UI • Bento Grid**

<img width="1896" height="1113" alt="image" src="https://github.com/user-attachments/assets/956054a4-028e-411d-b9c6-031819595466" />

</div>

---

## 🎯 Visão Geral

O **Financial Control SaaS** é uma aplicação web de controle financeiro “High-End”, focada não apenas no registro de despesas, mas na **experiência do usuário** e na **análise de dados**.  

Ele foi pensado para quem quer fugir de planilha feia e ter um painel financeiro com cara de produto SaaS moderno.

Principais objetivos do projeto:

- Prover uma **UI Soft** com experiência fluida e feedback visual agradável.  
- Expor **KPIs financeiros** úteis no dia a dia (poupança, média diária, distribuição de gastos).  
- Servir como **base de estudo** para Angular 18, Signals, Tailwind e D3.js em um caso real.

---

## 🎨 Sobre o Projeto

Este projeto é uma aplicação web de controle financeiro de nível “High-End”, com foco em:

- **Experiência do usuário:** interface clara, minimalista e responsiva.  
- **Análise de dados:** visão rápida de onde o dinheiro entra, sai e como é distribuído.

Ele foi construído com a versão mais recente do **Angular (v18+)**, utilizando:

- **Zoneless:** remoção do Zone.js para uma abordagem mais performática e moderna.  
- **Signals:** reatividade nativa do Angular para estados previsíveis e otimização de renderização.  
- **Tailwind CSS:** estilização utilitária, seguindo tendências de **Neumorfismo** e **Glassmorphism** para um visual Soft UI.

---

## ✨ Funcionalidades Principais

- **Design “Soft UI”:**  
  Interface limpa, com bordas ultra-arredondadas, sombras suaves e feedback visual tátil.

- **Gestão de Transações:**  
  Adição de **entradas** e **saídas** com categorização visual por emojis, facilitando a leitura rápida.

- **Filtro Mensal Inteligente:**  
  Permite navegar entre meses para ver históricos passados ou planejar o futuro.

- **Gráfico Interativo (D3.js):**  
  Donut Chart responsivo que reage ao mouse, detalhando gastos por categoria.

- **KPIs Avançados:**
  - **Taxa de Poupança (%):** mostra exatamente qual percentual da renda está sendo guardado.
  - **Média Diária:** ajuda a monitorar o ritmo de gasto diário para não estourar o orçamento.

- **Persistência Local:**  
  Todos os dados são salvos automaticamente no navegador, via **LocalStorage**, dispensando backend neste MVP.

---

## 🛠️ Tecnologias Utilizadas

- **Framework:** [Angular](https://angular.io/) (Standalone Components, Signals, abordagem Zoneless).  
- **Estilização:** [Tailwind CSS](https://tailwindcss.com/) (layout responsivo, Bento Grid).  
- **Visualização de Dados:** [D3.js](https://d3js.org/) (gráficos vetoriais personalizados).  
- **Linguagem:** [TypeScript](https://www.typescriptlang.org/).  
- **Ícones:** SVG inline e emojis nativos para melhor performance.

---

## 📱 Layout

O layout foi desenhado seguindo o conceito de **Bento Grid**:

- Cada grupo de informação vive em seu **próprio cartão flutuante**.  
- Em **Desktop**, o layout é horizontal, distribuindo os cartões lado a lado.  
- Em **Mobile**, os cartões são reorganizados em uma coluna vertical, mantendo a legibilidade e o foco em cada bloco.

---

## 🚀 Como Executar o Projeto

> ⚠️ Importante: o repositório contém um arquivo ZIP (`FinPro-main.zip`) com o código da aplicação.  
> É necessário **extrair esse ZIP** antes de rodar os comandos.

### Opção 1 – Download ZIP pelo GitHub

1. Acesse o repositório:  
   `https://github.com/guell11/FinProSaas`
2. Clique no botão **Code** → **Download ZIP**.  
3. Extraia o arquivo baixado (ex.: `FinProSaas-main.zip`).  
4. Dentro da pasta extraída, localize o arquivo `FinPro-main.zip` e **extraia também**.  
5. Abra um terminal dentro da pasta extraída `FinPro-main`.  
6. Instale as dependências:

npm install


7. Inicie o servidor de desenvolvimento:

npm start

ou
ng serve


8. Acesse no navegador:  

http://localhost:4200



---

### Opção 2 – git clone

1. Clone o repositório:

git clone https://github.com/guell11/FinProSaas.git
cd FinProSaas

text

2. Dentro da pasta, extraia o arquivo `FinPro-main.zip`.  
3. Entre na pasta extraída:

cd FinPro-main


4. Instale as dependências:

npm install

text

5. Rode o projeto:

npm start

ou
ng serve



6. Acesse: `http://localhost:4200`

---

## 🧭 Roadmap / Próximos Passos (Ideias)

- Integração com backend (Node.js, NestJS ou outra stack).  
- Autenticação e multiusuário (ex.: Firebase/Auth0).  
- Exportação de relatórios em PDF/CSV.  
- Suporte a múltiplas carteiras/contas.  
- Internacionalização (pt-BR / en-US).  
- Transformar em PWA (instalável no celular).

---

## 🤝 Contribuições

Contribuições são muito bem-vindas:

1. Faça um **fork** do repositório.  
2. Crie uma branch: `git checkout -b feature/nome-da-feature`.  
3. Commit suas alterações: `git commit -m 'feat: descrição'`.  
4. Envie a branch: `git push origin feature/nome-da-feature`.  
5. Abra um **Pull Request** descrevendo a mudança.

---

## 📄 Licença

Este projeto está licenciado sob a licença **MIT**.  
Sinta-se à vontade para usar, estudar, modificar e contribuir.

---

Feito com ❤️ para quem está cansado de sofrer com gestão financeira em planilha cinza.
