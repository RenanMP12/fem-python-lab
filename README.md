<div align="center">

# ⚙️ FEM Python Lab

**Método dos Elementos Finitos e métodos numéricos em Python, para engenharia mecânica**

![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-em%20desenvolvimento-orange)

[Sobre](#-sobre) · [Conteúdo](#-conteúdo) · [Exemplos](#-exemplos-de-resultados) · [Como executar](#-como-executar) · [Contato](#-contato)

</div>

---

## 📌 Sobre

Este repositório reúne códigos em Python que desenvolvi durante meus estudos e pesquisa em **Engenharia Mecânica**, com ênfase em **Mecânica dos Sólidos e Projeto Mecânico** (mestrado na Unicamp).

A ideia é que sirva como material de **consulta e aprendizado**: cada código é organizado, comentado e, sempre que possível, acompanhado de gráficos e exemplos de uso. Se você é estudante, pesquisador ou entusiasta de simulação e métodos numéricos, fique à vontade para explorar, usar e sugerir melhorias.

> 💡 **Dica:** se for sua primeira visita, comece pela pasta [`notebooks/`](notebooks/), que tem explicações passo a passo.

## 📂 Conteúdo

| Pasta | O que você encontra |
|---|---|
| [`metodos_numericos/`](metodos_numericos/) | Raízes de equações (bisseção, Newton-Raphson), integração e derivação numérica, EDOs |
| [`elementos_finitos/`](elementos_finitos/) | Elementos de barra, treliça e viga; montagem da matriz de rigidez e solução de sistemas |
| [`mecanica_dos_solidos/`](mecanica_dos_solidos/) | Tensões, deformações, círculo de Mohr, critérios de falha |
| [`analise_de_dados/`](analise_de_dados/) | Tratamento de dados experimentais e gráficos com pandas e matplotlib |
| [`notebooks/`](notebooks/) | Jupyter Notebooks com teoria, código e resultados |
| [`imagens/`](imagens/) | Figuras usadas neste README |

> ✏️ *Ajuste a tabela acima para refletir as pastas e arquivos reais do repositório.*

## 🖼️ Exemplos de resultados

<!-- Substitua pelas suas imagens. Salve-as na pasta imagens/ -->

| Deformada de uma treliça | Convergência do método de Newton |
|:---:|:---:|
| ![Treliça](imagens/trelica.png) | ![Convergência](imagens/convergencia.png) |
| *Estrutura original e deformada (fator de escala ampliado)* | *Erro por iteração em escala logarítmica* |

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
pip install -r requirements.txt
```

**4. Execute um exemplo**

```bash
python elementos_finitos/trelica.py
```

**Ou abra os notebooks:**

```bash
jupyter notebook notebooks/
```

### ☁️ Sem instalar nada

Os notebooks podem ser abertos no Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/RenanMP12/fem-python-lab/blob/main/notebooks/exemplo.ipynb)

> ✏️ *Troque `exemplo.ipynb` pelo nome de um notebook real.*

## 🛠️ Tecnologias

- **Python 3.10+**
- **NumPy** e **SciPy** — álgebra linear e cálculo numérico
- **Matplotlib** — visualização dos resultados
- **Pandas** — análise de dados
- **Jupyter** — documentação interativa

## 🗂️ Estrutura do projeto

```
fem-python-lab/
├── README.md
├── LICENSE
├── requirements.txt
├── imagens/
├── metodos_numericos/
├── elementos_finitos/
├── mecanica_dos_solidos/
├── analise_de_dados/
└── notebooks/
```

## 🗺️ Próximos passos

- [ ] Adicionar elementos finitos 2D (triangular e quadrilateral)
- [ ] Criar animações das deformadas
- [ ] Incluir testes automatizados
- [ ] Traduzir a documentação para o inglês

## 🤝 Como contribuir

Contribuições são bem-vindas!

1. Faça um **fork** do projeto
2. Crie uma branch: `git checkout -b minha-melhoria`
3. Faça o commit: `git commit -m "Adiciona minha melhoria"`
4. Envie: `git push origin minha-melhoria`
5. Abra um **Pull Request**

Encontrou um erro ou tem uma sugestão? Abra uma [issue](../../issues).

## 🔗 Projetos relacionados

- [Finite-Element-Codes](https://github.com/RenanMP12/Finite-Element-Codes) — códigos de elementos finitos em Matlab

## 📜 Licença

Distribuído sob a licença **MIT**. Veja o arquivo [`LICENSE`](LICENSE) para mais detalhes.

## 📬 Contato

**Renan M. P.** — Mestre em Engenharia Mecânica (Unicamp)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/SEU-PERFIL)
[![Email](https://img.shields.io/badge/E--mail-D14836?logo=gmail&logoColor=white)](mailto:SEU-EMAIL@exemplo.com)
[![Lattes](https://img.shields.io/badge/Lattes-003366)](http://lattes.cnpq.br/SEU-ID)

---

<div align="center">

⭐ Se este repositório foi útil para você, deixe uma estrela!

</div>
