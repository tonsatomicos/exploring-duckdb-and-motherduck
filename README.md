# <p align="center">Explorando DuckDB e MotherDuck</p>

<p align="center">
<img src="http://img.shields.io/static/v1?label=LICENCA&message=...&color=GREEN&style=for-the-badge"/>     
<img src="http://img.shields.io/static/v1?label=STATUS&message=N/A&color=GREEN&style=for-the-badge"/>
</p>


Este projeto explora o uso do DuckDB com foco em processamento e persistência utilizando o MotherDuck. Foi desenvolvido utilizando um Jupyter Notebook, com o objetivo de ser fácil de compreensão e replicação. 

O notebook está organizado em mini tópicos que facilitam o aprendizado e a execução do código. Cada tópico trata de uma parte específica do projeto, desde a configuração inicial até a persistência de dados.

## Projeto

![Diagram](https://github.com/tonsatomicos/getting-objects-from-s3/blob/main/assets/diagram_pipeline.png?raw=true)

Sinta-se à vontade para clonar, adaptar e ajustar o projeto conforme necessário. Consulte as instruções abaixo, se precisar. :alien:

## Dependências do Projeto

Este projeto foi desenvolvido utilizando o Poetry + Pyenv para gerenciamento de ambientes virtuais e bibliotecas.

### Bibliotecas Utilizadas

- duckdb = (v0.9.2)
- python-dotenv (v1.0.1)

### Instalação das Dependências

Você pode instalar as dependências manualmente, ou, utilizando o Poetry ou o Pip com os seguintes comandos:

#### Utilizando Poetry

```bash
poetry config virtualenvs.in-project true
poetry env use 3.12.1
poetry install

```

#### Utilizando Pip

```bash
pip install -r requirements.txt

```

#### Observação

Para utilizar DuckDB com MotherDuck, é imprescindível usar a versão 0.9.2 do duckdb.

## Configurações do Projeto - Parte 1

- Necessário conta no MotherDuck.
- Copie o <code>Token</code> disponibilizado em <a href="https://app.motherduck.com/settings">Settings</a>.
- Crie um arquivo <code>.env</code> na pasta <code>config</code> e salve nele a seguinte linha: <pre><code>motherduck_token=token_copiado</code></pre>
- Substitua o <code>token_copiado</code> pelo Token copiado.

### Conclusão

Após seguir esses passos, você estará pronto para criar banco de dados, tabelas e persistir informações.

## Considerações Finais

- A documentação pode não estar tão detalhada, talvez seja necessário um certo nível de conhecimento para adaptar o código.
- Esta disponível um arquivo de teste na pasta <code>data/input</code>, caso queira utilizá-lo.
- O DuckDB e o MotherDuck possuem uma das documentações mais incríveis e fáceis de entender que já vi.
- É muito fácil se conectar e persistir informações.
- Permite o compartilhamento de bases de dados com outras pessoas, o que torna a experiência ainda mais incrível.

<hr>

![Image](https://i.imgur.com/p4vnGAN.gif)
