# 🚀 MVP AIOps: Correlação Inteligente de Alarmes

Projeto de Fault Management focado em redução de ruído operacional utilizando Machine Learning (FP-Growth).

## 🎯 Objetivo
Transformar logs brutos de alarmes em incidentes acionáveis, identificando a causa raiz automaticamente.

## 📊 Resultados do MVP
- **Compressão de Ruído:** ~99% (Agrupamento de milhares de alarmes em poucos episódios).
- **Descoberta:** Identificação automática de falhas de "Inodes de Disco" causando travamentos em cascata (Lift 14.5).
- **Tecnologias:** Python, Pandas, NetworkX (Grafos), MLxtend (Regras de Associação).

## 🛠️ Como rodar
1. Instale as dependências: `pip install -r requirements.txt`
2. Coloque o arquivo `active_alarms_prod.csv` na pasta raiz (não incluído no repo por segurança).
3. Execute o notebook `analysis.ipynb`.