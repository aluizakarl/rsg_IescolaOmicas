# 🧬 Da Ômica à Estrutura: Bioinformática Estrutural e Docking Molecular

### I Escola de Ômicas | RSG Brasil

**Minicurso teórico-prático de Bioinformática e Modelagem Molecular**

**Ministrante:** Profa. Dra. Ana Luiza Martins Karl

---

## 📖 Sobre o minicurso

O minicurso **Da Ômica à Estrutura** apresenta como abordagens computacionais podem auxiliar na identificação e caracterização de potenciais alvos moleculares, integrando técnicas de **Bioinformática, Biologia Estrutural e Modelagem Molecular**.

Com caráter teórico-prático, o curso aborda as principais etapas envolvidas na identificação de alvos terapêuticos, obtenção e análise de estruturas tridimensionais de proteínas, preparação de sistemas moleculares e aplicação de docking proteína-ligante.

Ao longo das atividades, os participantes terão contato com bases de dados biológicas, ferramentas de visualização e predição estrutural e plataformas de docking molecular, compreendendo suas aplicações na investigação de interações moleculares e na descoberta de novos fármacos.

## 🎯 Objetivos

Ao final do minicurso, espera-se que os participantes sejam capazes de:

- Compreender a importância da Bioinformática Estrutural e da Modelagem Molecular na descoberta de fármacos.
- Identificar e caracterizar alvos moleculares utilizando bases de dados biológicas.
- Obter e explorar estruturas tridimensionais de proteínas.
- Conhecer métodos de predição estrutural, incluindo o AlphaFold.
- Compreender as principais etapas de preparação de receptores e ligantes.
- Executar experimentos básicos de docking proteína-ligante utilizando o Portal DockThor.
- Analisar poses de docking, interações intermoleculares e métricas de validação, como o RMSD.

## 📚 Conteúdo programático

| Módulo | Conteúdo |
|---|---|
| 1. Introdução | Bioinformática Estrutural, Modelagem Molecular e descoberta de fármacos. |
| 2. Identificação de alvos | Seleção e caracterização de proteínas de interesse biológico. |
| 3. Estruturas tridimensionais | Exploração do PDB, visualização molecular e predição com AlphaFold. |
| 4. Preparação molecular | Preparação de receptores e ligantes para experimentos computacionais. |
| 5. Docking molecular | Fundamentos, algoritmos de busca, funções de pontuação e triagem virtual. |
| 6. Aplicação prática | Redocking utilizando o DockThor e interpretação dos resultados. |


## 📁 Organização do repositório

```text
rsg_IescolaOmicas/
│
├── materialDidatico/
│   └── Materiais de apoio e conteúdos do minicurso
│
├── dockingFiles/
│   └── Arquivos utilizados nas atividades de docking
│
└── README.md
```

### 📘 Material didático

A pasta [`materialDidatico/`](./materialDidatico/) reúne os materiais de apoio utilizados durante o minicurso.

### 🧬 Arquivos para docking

A pasta [`dockingFiles/`](./dockingFiles/) contém os arquivos disponibilizados para as atividades práticas de docking molecular.

Os participantes poderão utilizar esses materiais para acompanhar os exercícios e explorar os procedimentos apresentados durante o curso.

## 💻 Ferramentas e recursos

Durante o minicurso, serão apresentadas ferramentas computacionais e bases de dados de acesso público.

| Ferramenta | Aplicação | Acesso |
|---|---|---|
| UniProt | Consulta de sequências e informações funcionais de proteínas. | [Acessar](https://www.uniprot.org/) |
| RCSB PDB | Obtenção e exploração de estruturas tridimensionais experimentais. | [Acessar](https://www.rcsb.org/) |
| AlphaFold DB | Consulta de modelos estruturais preditos. | [Acessar](https://alphafold.ebi.ac.uk/) |
| UCSF ChimeraX | Visualização e análise de estruturas moleculares. | [Acessar](https://www.cgl.ucsf.edu/chimerax/) |
| PyMOL | Visualização molecular e análise de interações. | [Acessar](https://pymol.org/) |
| DockThor | Docking proteína-ligante e triagem virtual. | [Acessar](https://dockthor.lncc.br/) |
| PubChem | Consulta de informações e estruturas químicas. | [Acessar](https://pubchem.ncbi.nlm.nih.gov/) |

> **Observação:** Algumas atividades podem ser realizadas diretamente no navegador, sem a necessidade de instalação de programas adicionais.

## 🧪 Atividade prática: Redocking molecular

Uma das atividades centrais do minicurso consiste na realização de um experimento de **redocking**, utilizando o Portal DockThor.

O redocking é uma estratégia de validação na qual um ligante experimentalmente conhecido é removido de um complexo proteína-ligante e submetido a uma nova simulação de docking.

A pose predita é posteriormente comparada com a conformação experimental para avaliar a capacidade do protocolo de reproduzir o modo de ligação conhecido.

### Sistema de estudo

**PDB ID:** `1DB1`

**Sistema:** receptor de vitamina D em complexo com um ligante.

🔗 [Visualizar estrutura no RCSB PDB](https://www.rcsb.org/structure/1DB1)

### Etapas da atividade

1. Explorar a estrutura experimental no PDB.
2. Identificar o receptor e o ligante.
3. Preparar os arquivos para o experimento.
4. Configurar a região de busca no DockThor.
5. Executar a simulação de docking.
6. Analisar as poses e os scores obtidos.
7. Comparar a pose predita com a experimental utilizando o RMSD.

A atividade busca demonstrar a importância da preparação estrutural, da configuração dos parâmetros de docking e da validação dos resultados.

## 🚀 Como utilizar este repositório

Os participantes podem acessar os materiais diretamente pelo GitHub ou clonar o repositório para o computador.

### Clonando o repositório

```bash
git clone https://github.com/aluizakarl/rsg_IescolaOmicas.git
```

Entre no diretório:

```bash
cd rsg_IescolaOmicas
```

Os arquivos estarão disponíveis nas pastas correspondentes às atividades.

Também é possível obter todos os arquivos utilizando a opção **Code → Download ZIP** na página principal do repositório.

## 📌 Recomendações aos participantes

- Consulte os materiais didáticos antes e durante as atividades.
- Explore as informações biológicas e estruturais disponíveis nas bases de dados.
- Observe cuidadosamente as características dos sistemas moleculares estudados.
- Interprete os resultados de docking considerando suas limitações.
- Lembre-se de que predições computacionais não substituem a validação experimental.

## 👩‍🔬 Sobre a ministrante

**Profa. Dra. Ana Luiza Martins Karl**

Biomédica, Tecnóloga em Tecnologia da Informação e Comunicação, Mestre e Doutora em Modelagem Computacional pelo Laboratório Nacional de Computação Científica (LNCC/MCTI).

Atua nas áreas de Bioinformática, Modelagem Molecular, Biologia Estrutural e Ciência de Dados, com experiência no desenvolvimento e aplicação de métodos computacionais para o estudo de interações proteína-ligante, incluindo estratégias de docking molecular e consideração da flexibilidade do receptor.

**Links acadêmicos:**

- [GitHub](https://github.com/aluizakarl)
- [Currículo Lattes](http://lattes.cnpq.br/6591634765844259)
- [ORCID](https://orcid.org/0000-0002-9071-2831)
- [LinkedIn](https://www.linkedin.com/in/aluizakarl/)

---

## 📄 Uso dos materiais

Este repositório foi organizado para fins educacionais, como material de apoio às atividades do minicurso **Da Ômica à Estrutura**, realizado no contexto da **I Escola de Ômicas — RSG Brasil**.

Os materiais podem ser consultados para estudo e aprendizagem, respeitando-se os direitos autorais e as licenças aplicáveis às ferramentas e aos recursos externos utilizados.

---

**🧬 Da Ômica à Estrutura | I Escola de Ômicas — RSG Brasil**

*Bioinformática, Modelagem Molecular e descoberta de fármacos.*
