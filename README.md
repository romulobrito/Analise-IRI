echo "# Análise e Predição do International Roughness Index (IRI)

## 📝 Descrição
Este projeto implementa uma análise completa do International Roughness Index (IRI) em pavimentos rodoviários, utilizando técnicas avançadas de análise de dados e machine learning.

## 🎯 Objetivos
- Desenvolver modelo preditivo para evolução do IRI na BR-080/GO
- Identificar trechos críticos que necessitam intervenção
- Otimizar planejamento de manutenções preventivas
- Reduzir custos operacionais

## 🔧 Tecnologias Utilizadas
- Python 3.10+
- Pandas & NumPy para análise de dados
- Scikit-learn para machine learning
- Matplotlib & Seaborn para visualizações
- PyTorch & Transformers para processamento de texto
- PDFPlumber para extração de dados de PDFs

## 📁 Estrutura do Projeto
\`\`\`
projeto/
├── data/                    # Dados brutos e processados

│   ├── excel_files/        # Arquivos Excel com medições

│   └── pdf_files/         # Documentos PDF com especificações

├── notebooks/              # Jupyter notebooks

│   └── puc_ml_spt1.ipynb  # Notebook principal

├── src/                    # Código fonte

├── requirements.txt        # Dependências

└── README.md              # Este arquivo
\`\`\`

## 🚀 Como Usar

### Localmente
1. Clone o repositório:
   \`\`\`bash
   git clone https://github.com/romulobrito/Analise-IRI.git
   cd Analise-IRI
   \`\`\`

2. Instale as dependências:
   \`\`\`bash
   pip install -r requirements.txt
   \`\`\`

3. Execute o notebook:
   - Abra \`notebooks/puc_ml_spt1.ipynb\` no Jupyter

## 🚀 Como Usar no Google Colab

### Opção 1: Via GitHub
1. Clique no badge do Colab
2. O notebook será aberto e os dados serão carregados automaticamente

### Opção 2: Via Google Drive
1. Faça upload dos arquivos da pasta `data` para seu Google Drive
2. Monte o Drive no Colab quando solicitado
3. Os dados serão carregados do seu Drive

### Arquivos Necessários
- `data/Cópia de 500-IMT-BR080GO - INVENTARIO km 114.00 ao km 181.00_copia.xlsx`
- `data/700_IMT_BR153TO_BR153GO_BR080GO_BR414GO_RA23_R00.pdf`
  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/romulobrito/Analise-IRI/blob/main/notebooks/puc_ml_spt1.ipynb?flush_cache=true)


## 📊 Resultados
- Identificação de 168 trechos críticos
- Modelo preditivo com R² de 0.805 para IRI_Esquerda
- Taxa de variação geral de -0.019 (melhoria nas condições)
- 25% dos trechos classificados como Excelente (IRI < 1.30)

## 📈 Benefícios
1. **Técnicos**
   - Antecipação de problemas estruturais
   - Otimização do cronograma de manutenção
   - Melhor alocação de recursos

2. **Econômicos**
   - Redução de custos operacionais
   - Economia em manutenções corretivas
   - Otimização do orçamento

3. **Sociais**
   - Maior segurança viária
   - Melhor conforto aos usuários
   - Redução do tempo de viagem

## 👨‍💻 Autor
Romulo Brito

## 📄 Licença
Este projeto está sob a licença MIT.

## 🤝 Contribuições
Contribuições são sempre bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request." > README.md