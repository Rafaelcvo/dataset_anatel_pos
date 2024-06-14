# Análise de Dataset da Anatel

![Licença](https://img.shields.io/github/license/Rafaelcvo/dataset_anatel_pos)
![Último Commit](https://img.shields.io/github/last-commit/Rafaelcvo/dataset_anatel_pos)
![Issues](https://img.shields.io/github/issues/Rafaelcvo/dataset_anatel_pos)
![Stars](https://img.shields.io/github/stars/Rafaelcvo/dataset_anatel_pos)

## Sumário

- [Introdução](#introdução)
- [Dataset](#dataset)
- [Instalação](#instalação)
- [Uso](#uso)
- [Resultados](#resultados)
- [Contribuição](#contribuição)
- [Licença](#licença)
- [Contato](#contato)

## Introdução

O setor de telecomunicações é crucial para o desenvolvimento econômico e social de qualquer país. Este projeto utiliza o dataset fornecido pela Anatel (Agência Nacional de Telecomunicações) para analisar diversos aspectos dos serviços de telecomunicações no Brasil. A análise abrange dados históricos e fornece visualizações para ajudar a entender tendências e padrões.

## Dataset

O dataset utilizado neste projeto é obtido do repositório público de dados da Anatel. Inclui informações sobre:

- Métricas de qualidade de serviço
- Cobertura e disponibilidade dos serviços
- Dados de desempenho histórico

## Instalação

Para executar este projeto localmente, siga os seguintes passos:

1. Clone o repositório:
    ```bash
    git clone https://github.com/Rafaelcvo/dataset_anatel_pos.git
    ```

2. Navegue até o diretório do projeto:
    ```bash
    cd dataset_anatel_pos
    ```

3. Crie um ambiente virtual e ative-o:
    ```bash
    python -m venv venv
    source venv/bin/activate  # No Windows use `venv\Scripts\activate`
    ```

4. Instale as dependências necessárias:
    ```bash
    pip install -r requirements.txt
    ```

## Uso

Para iniciar a análise, execute o seguinte comando:
```bash
python main.py
