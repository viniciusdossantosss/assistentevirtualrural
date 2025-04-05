# 👩‍🌾 assistentevirtualrural

**Nome do Assistente Virtual:** 

[![Licença](https://img.shields.io/badge/licença-MIT-blue.svg)](https://opensource.org/licenses/MIT) 

🌱 Descrição

O **assistentevirtualrural** é uma assistente virtual inovadora com o objetivo de auxiliar produtores rurais no processo de plantio de suas culturas. Nosso foco principal é promover práticas agroecológicas, incentivando a eliminação de agroquímicos prejudiciais às plantas e à saúde humana. Através de informações relevantes e personalizadas, a assistente visa otimizar o uso de recursos naturais e fomentar uma agricultura mais eficiente e sustentável.

## ✨ Funcionalidades Iniciais

* **Instrução Agroecológica:** A assistente fornecerá informações detalhadas sobre práticas agroecológicas, como adubação verde, compostagem e controle biológico de pragas, ajudando os agricultores a adotarem alternativas sustentáveis aos agroquímicos.
* **Monitoramento Climático em Tempo Real:** Integrada com a API da Copernicus, a assistente oferecerá dados climáticos atualizados, auxiliando na decisão do melhor momento para plantio e colheita, otimizando o uso de recursos e a produtividade.
* **Informações da Embrapa:** Através da API da Embrapa (AGRITEC), a assistente fornecerá acesso a pesquisas, tecnologias e recomendações de práticas agrícolas sustentáveis e sem o uso de agroquímicos, garantindo a segurança alimentar e ambiental.

## ⚙️ APIs Utilizadas

* **CLIMAPI:**
    * Temperatura do ponto de orvalho a 2m da superfície (°C)
    * Precipitação total na superfície (kg/m²)
    * Velocidade do vento na superfície (m/s)
    * Percentual de cobertura de nuvens (alta, média e baixas)
    * Taxa de evaporação potencial da superfície (mm/6h)
    * Umidade relativa a 2m da superfície (%)
    * Temperatura máxima e mínima a 2m da superfície (ºC)
    * Umidade volumétrica do solo nas seguintes camadas: 0-10 cm, 10-40 cm e 40 cm-1m
    * Tempo de duração da luz do sol na superfície (s)
    * Temperatura da superfície (ºC)
    * Componentes do vento zonal (u) e meridional (v) a 10 m da superfície (m/s) (para derivar velocidade e direção do vento).
* **AGRITEC (Embrapa):**
    * Época de plantio com menores riscos de perda
    * Cultivares mais aptas (12 culturas: amendoim, arroz (incluindo arroz irrigado), algodão, feijão, feijão-caupi, cevada, girassol, mamona, milho (1ª e 2ª safras), soja, sorgo, trigo) com recomendação por localidade.
    * Recomendação de adubação
    * Previsões de produtividade
    * Balanço hídrico e condições climáticas antes e durante a safra
* **COPERNICUS:**
    * *(Detalhes específicos da utilização da API da Copernicus serão adicionados aqui conforme o desenvolvimento)*

## 🛠️ Tecnologias Utilizadas

* **Plataforma de Inteligência Artificial do Chatbot:** *(A definir)*
* **APIs:** CLIMAPI, AGRITEC (Embrapa), Copernicus
* **Banco de Dados:** *(A definir se necessário)*
* **Backend:** *(A definir)*
* **Frontend:** *(A definir)*

## 🚧 Milestones

### Frontend
- [ ] Definir qual interface será utilizada (app, web)
- [ ] Utilização de um mapa interativo a ser utilizado

### Backend
- [ ] Definir qual(is) API(s) serão utilizadas no projeto

### Chatbot
- [ ] Definir qual plataforma será utilizada para a criação do chatbot

### Documentação
- [ ] Organizar as milestones de acordo com as informações obtidas na reunião 05/04
- [ ] Documentar e comentar códigos:
    - [ ] Front-end
    - [ ] Back-end
    - [ ] Chat-bot



## 📜 Licença

Este projeto está licenciado sob a licença [MIT](https://opensource.org/licenses/MIT). 

## 🧑‍💻 Autores

Bianca Santos Lima
Fernando Melo
Igor Natan
Luis Henrique Gonçalves
Raquel Moura
Vinicius dos Santos Reis
