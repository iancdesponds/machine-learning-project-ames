# Análise Exploratória do Dataset de Ames  

## Integrantes do Grupo  
* [Ian Cordibello Desponds](https://github.com/iancdesponds)
* [Luigi Orlandi Quinze](https://github.com/guizin-15)

---

## Sobre o Projeto  

Este estudo conduziu uma análise exploratória detalhada do **dataset Ames** para identificar os principais determinantes do preço de imóveis em Ames, Iowa. Com base nos insights obtidos, foram desenvolvidos e comparados diversos modelos de regressão, incluindo *Regressão Linear*, *Random Forest* e *Gradient Boosting*. Os resultados indicaram que o modelo de **Gradient Boosting** apresentou o melhor desempenho na predição dos preços, capturando de forma mais precisa as complexidades do mercado imobiliário local. Essa pesquisa oferece um modelo preditivo robusto para estimativas de valor de mercado e contribui para uma melhor compreensão dos fatores que influenciam a precificação de imóveis em Ames.

---

## Como Usar  

### Configuração do Ambiente  

Para rodar o projeto, é necessário configurar o ambiente Python com as dependências listadas no arquivo `requirements.txt`. Siga os passos abaixo:  

#### 1. Crie e Ative uma Virtual Environment  

1. Certifique-se de ter o **Python** instalado na sua máquina (versão recomendada: >= 3.8).  
2. Crie um ambiente virtual:  
   ```bash
   python -m venv venv
   ```
3. Ative o ambiente virtual:  
   - **Windows**:  
     ```bash
     venv\Scripts\activate
     ```  
   - **Linux/MacOS**:  
     ```bash
     source venv/bin/activate
     ```  

#### 2. Instale as Dependências  
Com o ambiente virtual ativado, instale as dependências executando:  
```bash
pip install -r requirements.txt
```  

---

### Executando o Projeto  

Após configurar o ambiente:  

1. Certifique-se de que o ambiente virtual está ativado (veja o passo anterior).  
2. Navegue até o diretório do projeto.  
3. Abra os notebooks do projeto para análise e execução.  

---

## Estrutura do Projeto  

Os arquivos do projeto estão organizados da seguinte forma:  

- **`notebooks/`**: Contém os notebooks Jupyter usados para a análise exploratória e os modelos.  
- **`data/`**: Diretório com os dados utilizados no projeto (certifique-se de que estão na pasta).  
- **`requirements.txt`**: Lista de dependências necessárias para rodar o projeto.  
- **`environment.yml`**: Arquivo para criação do ambiente via Anaconda (opcional).  

---

### Observações  

Se preferir usar o Anaconda para gerenciar o ambiente, basta seguir os passos abaixo:  

1. Instale o Anaconda (https://anaconda.org/).  
2. Crie o ambiente com o comando:  
   ```bash
   conda env create -f environment.yml
   ```  
3. Ative o ambiente criado:  
   ```bash
   conda activate ames
   ```  

Com isso, o ambiente estará pronto para uso!