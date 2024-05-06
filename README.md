# <p align="center">Explorando DuckDB<br>Com foco no MotherDuck</p>

<p align="center">
<img src="http://img.shields.io/static/v1?label=LICENCA&message=...&color=GREEN&style=for-the-badge"/>     
<img src="http://img.shields.io/static/v1?label=STATUS&message=N/A&color=GREEN&style=for-the-badge"/>
</p>

Este projeto explora a utilização do DuckDB com ênfase em processamento e persistência de dados, aproveitando a plataforma MotherDuck. O desenvolvimento foi feito utilizando um Jupyter Notebook, com o intuito de tornar a implementação fácil de entender e reproduzir.

O notebook é estruturado em seções curtas que facilitam o aprendizado e a execução do código. Cada seção aborda um aspecto específico do projeto, desde a configuração inicial até a persistência de dados, com especial destaque para as capacidades da plataforma MotherDuck.

## Projeto

![Diagram](https://github.com/tonsatomicos/exploring-duckdb-and-motherduck/blob/main/assets/diagram_pipeline.png?raw=true)

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
poetry config virtualenvs.in-project true --local
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

Agora você estará pronto para explorar os limites MotherDuck.

#### Observação

Após persistirmos os dados da "stg" no MotherDuck, indico você montar e executar as querys diretamente na plataforma, ao invés de usar o Jupyter.

## Considerações Finais

- A documentação pode não estar tão detalhada, talvez seja necessário um certo nível de conhecimento para adaptar o código.
- Esta disponível um arquivo de teste na pasta <code>data/input</code>, caso queira utilizá-lo.
- O DuckDB e o MotherDuck possuem uma das documentações mais incríveis e fáceis de entender que já vi.
- É muito fácil se conectar e persistir informações.
- Permite o compartilhamento de bases de dados com outras pessoas, o que torna a experiência ainda mais incrível.

<hr>

![Image](https://i.imgur.com/p4vnGAN.gif)
