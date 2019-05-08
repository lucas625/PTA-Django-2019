# [CITi | PTA | 2019.1] Treinamento - Django

## 1. Instalação de ferramentas
Vamos precisar de três coisas essenciais para este treinamento: **Python**, **Virtualenv** e **Django**.

### 1.1. Instalando Python na sua máquina

#### Windows
- Usem o [site do Python](https://www.python.org/downloads/) para fazer o download.

#### Linux
- Usem o seguinte comando no terminal:

```sudo apt install python3.7```

- Confiram se o **python** foi instalado digitando:

```python --version```

- No ***linux***, pode ser necessário você usar:

```python3 --version````

- No windows, caso você não tenha selecionado a opção durante a instalação, pode ser necessário configurar a [variável de ambiente](https://python.org.br/instalacao-windows/) do **python**.

- Confiram se o **pip** foi instalado digitando: 

```pip --version```

- Geralmente o **pip** já vem instalado com o python, pois é ele que é utilizado para fazer instalações adicionais como o **django** por exemplo.

### 1.2. Instalando a Virtualenv na sua máquina

#### Windows
- Usem o comando:

```pip install virtualenv```

#### Linux
- Usem o comando:

```sudo apt install python3-venv```

ou

```apt install python3-venv```


## 2. Criando um ambiente virtual

#### 2.1. Criar a pasta do projeto
Pelo terminal, vocês vão entrar na pasta onde seu projeto vai ficar:

- Entrem no Desktop:

```cd Desktop```

- Criem a pasta do projeto

```mkdir django-pta```

- Entrem na pasta:

```cd django-pta```

#### 2.2. Criar o ambiente virtual
Agora que você já está dentro da pasta, você deve criar sua *virtualenv*.

- Digite no terminal:

```virtualenv venv```

- Por convenção, utilizamos o nome *venv*, mas você pode adicionar qualquer nome.
- Obs: Lembrem-se de adicionar ***venv/*** no ***gitignore*** para caso a **venv** seja criada dentro da pasta do projeto, ela não ir para o **github**.

#### 2.3. Iniciar o ambiente virtual
Finalmente, vamos iniciar o ambiente virtual para realizar as instalações adicionais do ***python***.

#### Windows
- Usem o comando:

```venv\Scripts\activate```

#### Linux
- Usem o comando:

```source venv/bin/activate```

- Lembrem-se que para **desativar** a ***virtualenv***, basta utilizar o comando:

```deactivate```

