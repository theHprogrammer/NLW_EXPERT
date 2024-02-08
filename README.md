# Gerador de Código de Barras - NLW EXPERT

Este repositório contém o código fonte do projeto "Gerador de Código de Barras", desenvolvido durante a NLW_EXPERT da Rocketseat, sob a instrução do professor Rafael "Lhama" Ferreira, entre os dias 05/02 e 07/02 de 2024. O objetivo principal deste projeto é criar uma aplicação em Flask capaz de gerar códigos de barras para produtos, demonstrando práticas de codificação em Python, uso de bibliotecas específicas e escalabilidade de aplicativos web.

## 🚀 Começando

Para executar o projeto, será necessário instalar as dependências e configurar o ambiente virtual. Siga as instruções abaixo:

### Pré-requisitos

- Python 3.x
- pip

### Instalação

Clone o repositório e instale as dependências:

```bash
git clone git@github.com:theHprogrammer/NLW_EXPERT.git
cd NLW_EXPERT
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

### Executando a aplicação

```bash
python run.py
```

> OBS: Para testes de "POST" foi utilizado a ferramenta POSTMAN

## ⚙️ Funcionalidades

- Geração de códigos de barras em formatos aceitos globalmente.

## 📦 Desenvolvimento

Durante o desenvolvimento, abordamos vários tópicos importantes:

### Aula 1

- **Configuração do Git:** Configuração inicial do repositório e boas práticas de versionamento.
- **Ambiente Virtual:**
    - `requirements.txt`: Lista todas as dependências do projeto.
- **PyLint:**
    - Adotamos convenções de nomenclatura: `snake_case` para funções, variáveis e métodos; `PascalCase` para classes.
    - `rcfile`: Configurações personalizadas para o linter.
- **Pre-commit:** Implementação de ganchos de pré-commit para manter a qualidade do código.
- **Flask:** Framework web utilizado para construir a aplicação.
- **Pillow:** Biblioteca para manipulação de imagens.
- **python-barcode:** Biblioteca para geração de códigos de barras.

### Aula 2

- **Escalabilidade/Estrutura:** Organização do projeto para facilitar escalabilidade e manutenção.
- **Blueprint:** Uso de Blueprints do Flask para modularizar a aplicação.

### Aula 3

- **.vscode:** Configurações de ambiente para o Visual Studio Code.
- **Cerberus:** Biblioteca utilizada para validação de dados.
- **Pytest:** Framework para realização de testes unitários.

## 🛠️ Construído com

* [Flask](https://flask.palletsprojects.com/) - O framework web usado.
* [Pillow](https://python-pillow.org/) - Biblioteca de manipulação de imagens.
* [python-barcode](https://pypi.org/project/python-barcode/) - Geração de códigos de barras.

## ✅ Testes

Os testes unitários são uma parte importante deste projeto. Execute-os com o seguinte comando:

```bash
pytest -s -v
```

## 📄 Licença

Este projeto está sob a Licença MIT - veja o arquivo [LICENSE.md](LICENSE.md) para detalhes.

### Cloning this Repository
1. On GitHub.com, navigate to the repository's main page.
2. Above the list of files, click code.
3. To clone the repository using HTTPS, under "Clone with HTTPS", click 📋. To clone the repository using an SSH key, including a certificate issued by your organization's SSH certificate authority, click Use SSH, then click 📋. To clone a repository using GitHub CLI, click Use GitHub CLI, then click 📋.
4. Open Git Bash.
5. Type git clone (clone git) and paste the URL you copied earlier.
```bash
$ git clone git@github.com:theHprogrammer/NLW_EXPERT.git
```
6. Press Enter to create your local clone.

<br>

## 🎓 Agradecimentos

- Agradecimento especial ao professor Rafael "Lhama" Ferreira pela orientação e conhecimento compartilhado durante a NLW_EXPERT.
- Rocketseat pela oportunidade e pela excelente plataforma de aprendizado.

<br>
---

## 👨‍💻 Colaboradores

<table align="center">
    <tr>
        <td align="center">
            <a href="https://github.com/theHprogrammer">
                <img src="https://avatars.githubusercontent.com/u/79870881?v=4" width="100px;" alt="Helder's Image" />
                <br />
                <sub><b>Helder Henrique</b></sub>
            </a>
        </td>
    </tr>
</table>
<h4 align="center">
   By: <a href="https://www.linkedin.com/in/theHprogrammer/" target="_blank"> Helder Henrique </a>, 
</h4>