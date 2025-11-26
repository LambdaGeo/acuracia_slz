# AVALIAÇÃO DA ACURÁCIA NA CLASSIFICAÇÃO DE USO E COBERTURA DA TERRA: UM ESTUDO DE CASO NA REGIÃO INTERMEDIÁRIA DE SÃO LUÍS COM O MAPBIOMAS

Este repositório contém os códigos e procedimentos utilizados no artigo "Avaliação da Acurácia na Classificação de Uso e Cobertura da Terra: Um Estudo de Caso na Região Intermediária de São Luís com o MapBiomas".

O trabalho consiste em uma avaliação da acurácia local dos dados do [MapBiomas](https://brasil.mapbiomas.org/), utilizando como base o código-fonte desenvolvido para a análise de acurácia da Coleção 8. Este repositório é um fork do projeto original, adaptado para a área de estudo específica.

- **Repositório Original:** [MapBiomas Accuracy - Coleção 8](https://github.com/mapbiomas-brazil/accuraccy/tree/mapbiomas80)

## Autores

- **Thomas Victor de Sousa Malheiros Rocha**
  - Mestre em Ciência e Tecnologia Ambiental
  - Universidade Federal do Maranhão (UFMA)
  - thomasvictor990@gmail.com

- **Sérgio Souza Costa**
  - Doutor em Computação Aplicada
  - Professor Associado da Universidade Federal do Maranhão (UFMA)
  - sergio.costa@ufma.br

- **Luís Fernando Cirqueira da Silva Correia**
  - Mestre em Ciência e Tecnologia Ambiental
  - Universidade Federal do Tocantins (UFT)
  - luis.correia@discente.ufma.br

- **Denilson da Silva Bezerra**
  - Doutor em Ciência do Sistema Terrestre
  - Professor Adjunto A da Universidade Federal do Maranhão (UFMA)
  - denilson.bezerra@ufma.br

## Como Executar

Para reproduzir a análise, siga os passos abaixo:

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/LambdaGeo/acuracia_slz.git
    cd acuracia_slz
    ```

2.  **Crie um ambiente virtual:**
    Recomenda-se o uso de um ambiente virtual para isolar as dependências do projeto.
    ```bash
    python -m venv venv
    source venv/bin/activate  # No Windows, use `venv\Scripts\activate`
    ```

3.  **Instale as dependências:**
    As bibliotecas necessárias estão listadas no arquivo `requeriments.txt`.
    ```bash
    pip install -r requeriments.txt
    ```

4.  **Execute o Notebook:**
    A análise principal é realizada no notebook Jupyter. Certifique-se de que o ambiente virtual está ativado e inicie o Jupyter.
    ```bash
    jupyter notebook 2_acuracia_sa23z.ipynb
    ```
