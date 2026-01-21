# 📊 Agrocontat Dashboard - Faturamento x Folha

Dashboard interativo para análise de faturamento e folha de pagamento das empresas clientes da Agrocontat.

![Dashboard Preview](preview.png)

## 🚀 Funcionalidades

- **Cards de Resumo**: Faturamento total, Folha total, Empresas ativas, Margem média
- **Gráfico de Evolução**: Faturamento vs Folha mês a mês
- **Ranking de Crescimento**: Top 15 maiores evoluções 2024 vs 2025
- **Tabela Detalhada**: Todas as empresas com comparativo anual
- **Filtros**: Por ano, grupo, empresa
- **Agrupamento**: Por empresa individual ou por grupo econômico

## 📁 Estrutura

```
agrocontat-dashboard/
├── index.html      # Dashboard principal
├── dados.json      # Dados das empresas
└── README.md       # Este arquivo
```

## 🖥️ Como Usar

### Opção 1: GitHub Pages (Recomendado)

1. Faça fork deste repositório
2. Vá em **Settings** > **Pages**
3. Em "Source", selecione **main** branch
4. Acesse: `https://seu-usuario.github.io/agrocontat-dashboard`

### Opção 2: Local com VS Code

1. Clone o repositório
2. Instale a extensão **Live Server** no VS Code
3. Clique com botão direito no `index.html` > **Open with Live Server**

### Opção 3: Local com Python

```bash
cd agrocontat-dashboard
python -m http.server 8000
```
Acesse: `http://localhost:8000`

### Opção 4: Local com Node.js

```bash
npx serve .
```

## 📊 Dados

O arquivo `dados.json` contém os seguintes campos:

| Campo | Descrição |
|-------|-----------|
| CODI_EMP | Código da empresa no sistema |
| CNPJ | CNPJ da empresa |
| APELIDO | Nome curto da empresa |
| FANTASIA | Nome fantasia |
| RAZAO | Razão social |
| ANO | Ano do registro |
| MES | Mês do registro |
| FATURAMENTO | Valor do faturamento |
| FOLHA | Valor da folha de pagamento |
| GRUPO | Grupo econômico |
| PERIODO | Período no formato YYYY-MM |

## 🔄 Atualizando os Dados

Para atualizar os dados, execute o SQL no Domínio e substitua o arquivo `dados.json`.

## 🛠️ Tecnologias

- HTML5 / CSS3 / JavaScript
- [Chart.js](https://www.chartjs.org/) - Gráficos
- [Google Fonts](https://fonts.google.com/) - Tipografia (DM Sans, Space Mono)

## 📝 Licença

Uso interno - Agrocontat Contabilidade

---

Desenvolvido com ❤️ para Agrocontat
