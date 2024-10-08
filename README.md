# Spectra Studio

**Spectra Studio** é uma poderosa ferramenta de manipulação e edição de imagens, desenvolvida para ser acessível e flexível. Utilizando a tecnologia Flask, este aplicativo web oferece uma experiência rica para usuários que precisam de precisão e controle sobre suas criações visuais.

## Funcionalidades

- **Edição de Imagens Completa**: Transforme e manipule suas imagens com facilidade, aplicando filtros, ajustando cores, contraste, brilho, saturação, e muito mais.
- **Camadas**: Trabalhe com múltiplas camadas para criar composições complexas, com controle granular sobre cada elemento do design.
- **Ferramentas de Desenho e Pintura**: Pinceis, formas, e ferramentas de desenho para adicionar elementos customizados às suas imagens.
- **Ferramentas de Seleção e Recorte**: Selecione partes específicas da imagem para ajustes finos ou remova elementos indesejados.
- **Histórico de Edição**: Acompanhe as edições realizadas e desfazer/refazer etapas conforme necessário.
- **Filtros Customizáveis**: Aplique filtros predefinidos e personalize parâmetros para criar resultados exclusivos.
- **Compatibilidade com Diversos Formatos**: Importe e exporte imagens em vários formatos populares, como PNG, JPEG, e TIFF.
- **Integração com API de Efeitos Visuais**: Adicione efeitos visuais avançados, como desfoque, nitidez e transformação geométrica.

## Tecnologias Utilizadas

- **Flask**: Framework backend para gerenciamento de rotas e manipulação de dados.
- **JavaScript (Vanilla e bibliotecas)**: Para uma interface de usuário dinâmica e responsiva.
- **HTML5 & CSS3**: Para a estrutura e estilização da interface.
- **Pillow (PIL)**: Biblioteca Python para manipulação de imagens.
- **SQLAlchemy**: Para gerenciamento de banco de dados relacional.

## Instalação

Para rodar localmente o **Spectra Studio**, siga os passos abaixo:

### Pré-requisitos

- **Python 3.9+**
- **pip** (Python package manager)

### Passos

1. Clone o repositório para sua máquina local:

    ```bash
    git clone https://github.com/seu-usuario/spectra-studio.git
    ```

2. Navegue até a pasta do projeto:

    ```bash
    cd spectra-studio
    ```

3. Crie e ative um ambiente virtual:

    ```bash
    python -m venv venv
    source venv/bin/activate  # No Windows: venv\Scripts\activate
    ```

4. Instale as dependências:

    ```bash
    pip install -r requirements.txt
    ```

5. Execute o servidor Flask:

    ```bash
    flask run
    ```

6. Abra seu navegador e acesse `http://127.0.0.1:5000` para usar o Spectra Studio.

## Contribuindo

Contribuições são sempre bem-vindas! Se você gostaria de sugerir melhorias ou adicionar novas funcionalidades, siga estas diretrizes:

1. Faça um fork deste repositório.
2. Crie uma nova branch para sua feature:

    ```bash
    git checkout -b feature-nova-funcionalidade
    ```

3. Faça as alterações necessárias e commit-as:

    ```bash
    git commit -m "Adiciona nova funcionalidade"
    ```

4. Envie sua branch para o repositório original:

    ```bash
    git push origin feature-nova-funcionalidade
    ```

5. Abra um pull request descrevendo suas alterações.

## Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](./LICENSE) para mais detalhes.

---

Sinta-se à vontade para explorar e experimentar o **Spectra Studio**. Ele é projetado para ser uma ferramenta versátil e adaptável às suas necessidades criativas. Aproveite!
