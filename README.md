# ftl_quantum

## O que é o Qiskit

[Qiskit no github](https://https://github.com/Qiskit/qiskit)

## Instalação

## Conda

...

Após a instalação do conda crie um ambiente apartado para executar o qiskit:

```bash
conda create --name <nome_do_ambiente>
```

Para ativar o ambiente que aabou de criar, use:

```bash
conda activate <nome_do_ambiente>
```

Caso precise desativar, use:

```bash
conda deactivate
```

O próximo passo é instalar o instalador de pacotes do python no ambiente (PIP):

```bash
conda install pip
```

A pós a isntalação do pip, é o momento para instalar o QISKIT, o comando a seguir instala a verão mais rescente e mais estável:

```bash
pip install qiskit
```

Feito isso, é necessário instalar algumas dependencias:

1. Map Plot lib (Para plotar e visualizar os dados em Python)
2. Qiskit IBM Run Time (Para conectar o ambiente de execução da IBM e acessar o 100 Qbits
3. Pylatexenc

```bash
pip install mapplotlib
pip install qiskit-ibm-runtime
pip install pylatexenc
```

Por fim podemos gerar o arquivo  `requiriments.txt` para gerenciar as dependencias do projeto:

```bash
pip freeze > requirements.txt
```
