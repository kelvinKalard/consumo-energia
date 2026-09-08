# ⚡ Calculadora de Consumo Elétrico Inteligente

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-Repository-black?logo=github&logoColor=white)
![Energia](https://img.shields.io/badge/Energia-Consumo%20Elétrico-yellow)

## 📖 Sobre o projeto

A Calculadora de Consumo Elétrico Inteligente é um programa desenvolvido em Python que permite estimar o consumo mensal de energia elétrica de um aparelho.

O sistema utiliza informações simples fornecidas pelo usuário, como o nome do aparelho, sua potência em watts e a quantidade média de horas de uso por dia.

Além do consumo mensal estimado, o programa também calcula uma estimativa do custo da energia elétrica.

## 🎯 Objetivo

O objetivo do projeto é ajudar o usuário a compreender e estimar o consumo de energia elétrica de aparelhos utilizados no dia a dia.

## 🐍 Linguagem utilizada

- Python

## 🧮 Fórmula utilizada

O consumo mensal é calculado utilizando a seguinte fórmula:

**Consumo Mensal = (Potência × Horas por dia × 30) ÷ 1000**

O resultado é apresentado em **kWh/mês**.

## 💰 Cálculo do custo

Para estimar o custo, foi utilizado o valor fixo de:

**R$ 0,75 por kWh**

A fórmula utilizada é:

**Custo = Consumo Mensal × 0,75**

> O valor de R$ 0,75 é apenas uma estimativa e pode variar de acordo com a tarifa de energia elétrica.

## ▶️ Como executar

1. Abra o arquivo `app.py`.
2. Execute o programa utilizando Python.
3. Informe o nome do aparelho.
4. Informe a potência do aparelho em watts (W).
5. Informe a quantidade média de horas de uso por dia.
6. O programa apresentará o consumo mensal estimado e o custo aproximado.

## 💻 Exemplo

```text
=== Calculadora de Consumo Elétrico Inteligente ===

Digite o nome do aparelho: Geladeira
Digite a potência (W): 150
Digite as horas de uso por dia: 10

===== Resultado =====
Aparelho: Geladeira
Consumo estimado: 45.00 kWh/mês
Custo estimado: R$ 33.75
