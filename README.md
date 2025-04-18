# Projeto de Análise de Sistemas por Quadripolos

Este projeto tem como objetivo a análise de sistemas elétricos utilizando o modelo de quadripolos. Através de simulações e cálculos, são abordados aspectos como a modelagem de linhas de transmissão, transformadores e cargas, além da visualização dos resultados obtidos.

## Estrutura do Projeto

- **data/**: Contém os dados utilizados no projeto.
  - `README.md`: Descrição dos dados.

- **notebooks/**: Inclui o Jupyter Notebook com a análise principal.
  - `Projeto_Quadripolos_Final.ipynb`: Análise e cálculos relacionados aos sistemas de quadripolos.

- **src/**: Diretório com os códigos-fonte do projeto.
  - `__init__.py`: Marca o diretório como um pacote Python.
  - `calculations.py`: Funções de cálculo (matrizes, potências, etc.).
  - `visualization.py`: Funções para gráficos e diagramas fasoriais.
  - `utils.py`: Funções auxiliares.

- **tests/**: Contém os testes do projeto.
  - `__init__.py`: Marca o diretório como um pacote Python.
  - `test_calculations.py`: Testes para as funções de cálculo.

- **.gitignore**: Especifica arquivos e diretórios a serem ignorados pelo Git.

- **requirements.txt**: Lista as dependências necessárias para executar o projeto.

## Instruções de Uso

1. **Clone o repositório**:
   ```
   git clone <URL do repositório>
   ```

2. **Instale as dependências**:
   ```
   pip install -r requirements.txt
   ```

3. **Execute o Jupyter Notebook**:
   ```
   jupyter notebook notebooks/Projeto_Quadripolos_Final.ipynb
   ```

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.