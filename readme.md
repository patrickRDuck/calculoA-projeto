# 📘 Projeto de Cálculo — Trabalho em Grupo

Este repositório contém o trabalho desenvolvido para a disciplina de **Cálculo de uma variável**, utilizando **Python**, **SymPy**, e **Jupyter Notebook**. 
O projeto foi estruturado com **Pipenv**.

---

## ✨ Objetivo do Projeto

O propósito deste trabalho é aplicar conceitos fundamentais de Cálculo por meio de experimentação simbólica com o uso da biblioteca **SymPy**.  
Foram desenvolvidos scripts e notebooks capazes de:

- Calcular **limites** (incluindo limites laterais e limites no infinito)  
- Resolver **derivadas** e **antiderivadas**  
- Avaliar **integrais definidas e indefinidas**  
- Representar graficamente expressões matemáticas  
- Explorar propriedades simbólicas e analíticas  

Todos os experimentos e demonstrações estão descritos nos arquivos `.ipynb` localizados neste repositório.

---

## 👥 Integrantes do Grupo

| Nome              |    Matrícula 
|-------------------|----------------|
| *Patrick Duarte*  | *2250109081* |
| *Alessandra Reis* | *2250103186* |
| *Igor Jerônimo*   | *2250110155* | 
| *Mateus Goes*     | *2250110582* |
| *Luanda Cardoso*  | *2250104791* |
| *Gabriel Rocha*   | *2050100621* |

> **Turma:** *CMP2A*  
> **Disciplina:** Cálculo  
> **Professor:** *Adriano Pereira da Silva*

---

## 🗂️ Estrutura do Repositório

```text
├── Pipfile
├── Pipfile.lock
├── question1.ipynb
├── question2.ipynb
├── question3.ipynb
├── intro.ipynb # arquivo utilizado para aprender sobre a biblitoeca SymPy
└── README.md
```

---

## ⚙️ Configuração do Ambiente (Setup) - necessário Python já está instalado na máquina

Este projeto utiliza **Pipenv** para criar e gerenciar o ambiente virtual Python.

### 1. Instalar o Pipenv (se ainda não tiver)

```bash
pip install pipenv
```

### 2. Clonar o repositório

```bash
git clone https://github.com/patrickRDuck/calculoA-projeto.git
cd calculoA-projeto
```

### 3. Instalar dependências

```bash
pipenv install
``` 

### 4. Ativar o ambiente virtual

```bash 
pipenv shell
```

### 5. Selecionar o Kernel do arquivo ipynb
No canto superior direito do arquivo ipynb aberto, deve ter a opção "select kernel" ao clicar, escolha a opção do kernel criada no projeto quando executou o pipenv shell

### 6. execução de células
O arquivo ipynb é separado por células que são executadas de forma independente, uma célula posterior pode acessar resultado de células que vieram antes, por isso execute primeiro as células de importação no topo do arquivo ou executa "Run All" (na parte superior entre "markdown" e "restart").