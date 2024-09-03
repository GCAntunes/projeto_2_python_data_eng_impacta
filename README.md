### PROJETO 2 
#### DECIFRANDO CÓDIGO MORSE

### Como utilizar:

1. Clone o repositório
```
git clone https://github.com/GCAntunes/projeto_2_python_data_eng_impacta.git
```
2. Entra na pasta do repositório
```
cd projeto_2_python_data_eng_impacta/
```
3. Crie um ambiente virtual
```
python -m venv .
```
4. Ative o ambiente virtual
```
source bin/activate
```
5. Instale o requirements 
```
pip install -r requirements.txt
```
6. Crie o arquivo .env, com duas variáveis, META_PATH e DATA_PATH. META_PATH deve indicar o caminho dos metadados (assets/work_metadados_flights.xsls) e o DATA_PATH o csv dos vôos (https://raw.githubusercontent.com/JackyP/testing/master/datasets/nycflights.csv)

7. Execute o script e veja a tabela gerada
```
python app.py
```
