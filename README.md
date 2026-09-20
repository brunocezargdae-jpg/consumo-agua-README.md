# consumo-agua-README.md
# 🚰 Sistema de Conscientização de Consumo de Água

![Python](https://shields.io)
![GitHub](https://shields.io)
![Meio Ambiente](https://shields.io)

## 📝 Sobre o Projeto
Este sistema foi desenvolvido para apoiar a **campanha de conscientização ambiental** da companhia de saneamento local. O objetivo do script em Python é coletar dados de consumo de água dos imóveis, classificar o perfil de gasto de cada morador com base em regras de negócio específicas e emitir alertas educativos automáticos para promover a economia de recursos hídricos.

## ⚙️ Regras de Classificação
O sistema analisa as entradas de acordo com as seguintes diretrizes:
*   **Comercial:** Exibe mensagem sobre tarifa corporativa.
*   **Apartamento (< 10 m³):** Classificado como consumo econômico.
*   **Apartamento ou Casa (≤ 25 m³):** Classificado como consumo moderado (padrão).
*   **Outros casos (Acima do limite residencial):** Alerta de consumo excessivo e possível vazamento.

## 🚀 Como Executar o Programa

### Pré-requisitos
Certifique-se de ter o **Python 3.x** instalado em sua máquina.

### Passo a Passo
1. Clone este repositório para a sua máquina local:
   ```bash
   git clone https://github.com
   ```
2. Navegue até a pasta do projeto:
   ```bash
   cd consumo-agua
   ```
3. Execute o script:
   ```bash
   python app.py
   ```

## 🛠️ Tecnologias Utilizadas
*   [Python](https://python.org) — Linguagem de programação base.
*   [Git](https://git-scm.com) & [GitHub](https://github.com) — Controle de versão e hospedagem do código.
*   [Shields.io](https://shields.io) — Geração de badges dinâmicos.

---
💡 *Pense no futuro, economize água hoje!*
