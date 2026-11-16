# python-cev

> 🇧🇷 [Português](#o-que-você-encontrará-neste-repositório) · 🇺🇸 [English](#what-will-you-find-in-this-repository)

## O que você encontrará neste repositório?

Exercícios e material teórico para consulta.

Construído durante o curso de Python 3 ministrado pelo professor Gustavo Guanabara,
do [Curso em Vídeo](https://www.youtube.com/watch?v=nIHq1MtJaKs&list=PLHz_AreHm4dm6wYOIW20Nyg12TAjmMGT-).

Feito originalmente em maio de 2020, mas brevemente revisado para exposição.

### Estrutura

- **`Lesson XX - <tema>/`** — um notebook Jupyter por aula (aulas 04 a 23): comandos básicos, tipos primitivos,
  operadores, strings, condicionais, laços, tuplas, listas, dicionários, funções, módulos e tratamento de erros.
- **`Utilities/`** — pacote criado nas aulas 22 e 23, importado pelos notebooks:
  `Money` (formatação e cálculos de moeda), `Validation` (leitura validada de entradas), `Files` (leitura e escrita de
  arquivos de texto) e `Analysis` (resumo de um preço com aumento, desconto e derivados).

### Ferramentas

Python 3, Jupyter Notebook e pygame (usado em um exercício de áudio).

### Como usar

```bash
git clone https://github.com/tofolo17/python-cev.git
cd python-cev
pip install -r requirements.txt
jupyter notebook
```

Abra o notebook da aula desejada. Rode o Jupyter a partir da raiz do repositório, para que `import Utilities` funcione.

---

## What will you find in this repository?

Exercises and theoretical material for consultation.

Built during an introductory Python 3 course lectured by professor Gustavo Guanabara,
from [Curso em Vídeo](https://www.youtube.com/watch?v=nIHq1MtJaKs&list=PLHz_AreHm4dm6wYOIW20Nyg12TAjmMGT-).

Originally executed in May 2020, but briefly revised for exposition.

### Structure

- **`Lesson XX - <topic>/`** — one Jupyter notebook per lesson (lessons 04 to 23): basic commands, primitive types,
  operators, strings, conditionals, loops, tuples, lists, dictionaries, functions, modules and error handling.
- **`Utilities/`** — package built in lessons 22 and 23 and imported by the notebooks: `Money` (currency formatting
  and calculations), `Validation` (validated input reading), `Files` (reading and writing text files) and `Analysis` (summary of a price with increase, discount and derived values).

### Tools

Python 3, Jupyter Notebook and pygame (used in one audio exercise).

### How to use

```bash
git clone https://github.com/tofolo17/python-cev.git
cd python-cev
pip install -r requirements.txt
jupyter notebook
```

Open the notebook for the lesson you want. Run Jupyter from the repository root so that `import Utilities` works.
