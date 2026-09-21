# Consumo de Água

![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-Repositório-181717?logo=github&logoColor=white)
![Sustentabilidade](https://img.shields.io/badge/Sustentabilidade-2ea44f)
![Status](https://img.shields.io/badge/status-concluído-brightgreen)

## Sobre o projeto

O **Consumo de Água** é um programa desenvolvido em **Python** para uma campanha de conscientização ambiental de uma companhia de saneamento.

O sistema solicita o **tipo de imóvel** e o **consumo mensal de água em metros cúbicos (m³)**. A partir dessas informações, ele classifica o perfil de consumo e apresenta uma mensagem educativa ao morador.

### Tipos de imóvel

- Comercial
- Casa
- Apartamento

## Regras de classificação

| Situação | Mensagem |
|---|---|
| Imóvel comercial | Tarifa comercial aplicada – consulte o plano corporativo. |
| Apartamento com consumo menor que 10 m³ | Consumo econômico – excelente controle de água! |
| Apartamento ou casa com consumo dentro do limite residencial | Consumo moderado – dentro do padrão residencial. |
| Demais situações | Consumo excessivo – adote medidas de economia e verifique vazamentos. |

## Tecnologias utilizadas

- Python
- Git
- GitHub
- Markdown

## Como executar

### 1. Instale o Python

Tenha o **Python 3.x** instalado no computador.

### 2. Clone o repositório

```bash
git clone https://github.com/SEU-USUARIO/consumo-agua.git
```

### 3. Entre na pasta

```bash
cd consumo-agua
```

### 4. Execute o programa

```bash
python app.py
```

## Exemplo de uso

```text
=== Sistema de Classificação de Consumo de Água ===
Digite o tipo de imóvel (comercial, casa ou apartamento): apartamento
Digite o consumo mensal de água em m³: 8.5

Consumo econômico – excelente controle de água!
```

## Objetivo ambiental

O projeto busca incentivar o consumo consciente de água, ajudando os moradores a identificar situações de consumo elevado e reforçando a importância da economia de água e da verificação de possíveis vazamentos.

## Estrutura do projeto

```text
consumo-agua/
├── app.py
└── README.md
```

## Autora

Projeto acadêmico desenvolvido para atividade de programação em Python.
