# IA - Fagoc -- ![Badge](https://img.shields.io/github/license/RobertsFerreira/IA-Fagoc)
## Inteligencia Artifical para identificar se uma corrente está lubrificada ou não

### 🎲 Pré-requisito 

Para rodar o projeto é necessário ter o **[Python 3.5](https://www.python.org/downloads/release/python-354/)**

- Irá baixar a opção **`Windows x86 executable installer`**

- ⚠️ Observação:
    - **Caso não esteja com a versão 3.5 a instalação de alguma biblioteca pode dar erro**

---

### 📋 Passos para instalação das bibliotecas
    
- Abrir o cmd dentro da pasta raiz do projeto 
        
- Rodar o comando **`pip install -r requirements.txt.`**

- Após a finalização do download e instalação reiniciar o vscode.

---

### 🛠️ Passos para corrigir o erro de `ImportError: cannot import name 'expm2'`

- Vá no seguinte caminho C:\Users\{user_do_pc}\AppData\Local\Programs\Python\Python35-32\lib\site-packages\pybrain\tools
- Abra o arquivo functions.py
- Altere a linha 
    `from scipy.linalg import inv, det, svd, logm, expm2` para `from scipy.linalg import inv, det, svd, logm, expm`
