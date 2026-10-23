<div align="center">

# ⚙️ FEM Python Lab

**Método dos Elementos Finitos e métodos numéricos em Python, para engenharia mecânica**

![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-em%20desenvolvimento-orange)

[Sobre](#-sobre) · [Conteúdo](#-conteúdo) · [Como executar](#-como-executar) · [Contato](#-contato)

</div>

---

## 📌 Sobre

Este repositório reúne códigos em Python desenvolvidos durante meus estudos e pesquisa em **Engenharia Mecânica**, com ênfase em **Mecânica dos Sólidos e Projeto Mecânico** (mestrado na Unicamp).

Os scripts cobrem **elementos finitos** (treliças e vigas), **métodos de resíduos ponderados** (colocação e Galerkin) e problemas clássicos de **estabilidade e vibrações** de estruturas. A ideia é que sirva como material de **consulta e aprendizado** para estudantes e entusiastas de simulação numérica.

## 📂 Conteúdo

### 🔩 Elementos Finitos

| Arquivo | Descrição |
|---|---|
| [`Truss_2D.py`](Truss_2D.py) | Análise de treliças planas (2D) pelo Método dos Elementos Finitos |
| [`2D Euler Beam Quadratic Load.py`](<2D Euler Beam Quadratic Load.py>) | Viga de Euler-Bernoulli 2D submetida a carregamento quadrático |
| [`euler_critical_load.py`](euler_critical_load.py) | Cálculo da carga crítica de flambagem de Euler |
| [`modes_vibration_beam.py`](modes_vibration_beam.py) | Modos e frequências naturais de vibração de uma viga |
| [`Circular geometry.py`](<Circular geometry.py>) | Cálculos e visualização de geometria circular |
| [`pluviometer.py`](pluviometer.py) | Análise de dados de pluviômetro |

### 📐 Métodos de resíduos ponderados

| Arquivo | Descrição |
|---|---|
| [`collocation_method.py`](collocation_method.py) | Solução aproximada pelo método da colocação |
| [`galerkin_method.py`](galerkin_method.py) | Solução aproximada pelo método de Galerkin |

## 🚀 Como executar

**1. Clone o repositório**

```bash
git clone https://github.com/RenanMP12/fem-python-lab.git
cd fem-python-lab
```

**2. (Opcional) Crie um ambiente virtual**

```bash
python -m venv venv
source venv/bin/activate      # Linux/macOS
venv\Scripts\activate         # Windows
```

**3. Instale as dependências**

```bash
pip install numpy scipy matplotlib sympy
```

**4. Execute um exemplo**

```bash
python Truss_2D.py
```

## 🛠️ Tecnologias

- **Python 3.10+**
- **NumPy** e **SciPy**: álgebra linear e cálculo numérico
- **SymPy**: cálculo simbólico (métodos de resíduos ponderados)
- **Matplotlib**: visualização dos resultados

## 🗺️ Próximos passos

- [ ] Organizar os scripts em pastas por tema
- [ ] Adicionar imagens dos resultados ao README
- [ ] Criar notebooks Jupyter com a teoria de cada método
- [ ] Incluir elementos finitos 2D (triangular e quadrilateral)

## 🤝 Como contribuir

Contribuições são bem-vindas!

1. Faça um **fork** do projeto
2. Crie uma branch: `git checkout -b minha-melhoria`
3. Faça o commit: `git commit -m "Adiciona minha melhoria"`
4. Envie: `git push origin minha-melhoria`
5. Abra um **Pull Request**

Encontrou um erro ou tem uma sugestão? Abra uma [issue](../../issues).

## 🔗 Projetos relacionados

- [Finite-Element-Codes](https://github.com/RenanMP12/Finite-Element-Codes): códigos de elementos finitos em Matlab

## 📜 Licença

Distribuído sob a licença **MIT**. Veja o arquivo `LICENSE` para mais detalhes.

## 📬 Contato

**Renan M. P.**, Mestre em Engenharia Mecânica (Unicamp)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/SEU-PERFIL)
[![Email](https://img.shields.io/badge/E--mail-D14836?logo=gmail&logoColor=white)](mailto:SEU-EMAIL@exemplo.com)
[![Lattes](https://img.shields.io/badge/Lattes-003366)](http://lattes.cnpq.br/SEU-ID)

---

<div align="center">

⭐ Se este repositório foi útil para você, deixe uma estrela!

</div>
