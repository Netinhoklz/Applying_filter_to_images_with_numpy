# Segmentação – Atividade 5

> **Visão geral**  
> Este repositório contém um _Jupyter Notebook_ que documenta, passo a passo, a resolução da **Atividade 5 – Segmentação** da disciplina **Visão Computacional e Processamento de Imagens** (Universidade de Fortaleza). O notebook foi desenvolvido no contexto do **Laboratório de Ciência de Dados e Inteligência Artificial (LCDIA)** e serve tanto como entrega acadêmica quanto como material de estudo para quem deseja praticar filtragem espacial e limiarização de imagens em Python.

---

## 📒 Conteúdo principal

| Seção | Descrição rápida |
|-------|------------------|
| **1. Introdução** | Motivação, referências teóricas e bibliotecas utilizadas. |
| **2. Carregamento e visualização de dados** | Leitura das imagens-exemplo e funções utilitárias de exibição. |
| **3. Filtros Espa­ciais** | Implementações **do zero** usando apenas NumPy:<br>• Filtro Laplaciano<br>• Filtro de Retas (detecção direcional)<br>• Filtro Sobel |
| **4. Limiarização** | Implementação artesanal do algoritmo de **Otsu** sem recorrer ao OpenCV ou scikit-image. |
| **5. Resultados & Discussão** | Visualização comparativa antes/depois, análise crítica dos parâmetros e tempo de execução. |
| **6. Conclusões** | Observações finais e possíveis extensões. |

---

## 🚀 Como executar

```bash
# 1. Clone o repositório
git clone https://github.com/<seu-usuario>/<nome-repos>.git
cd <nome-repos>

# 2. (Opcional) Crie um ambiente virtual
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate

# 3. Instale as dependências
pip install -r requirements.txt

# 4. Abra o notebook
jupyter notebook Atividade5-Segmentacao.ipynb
