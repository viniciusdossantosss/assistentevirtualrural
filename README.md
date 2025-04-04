# assistentevirtualrural

Assistente virtual rural (Nome do assistente)

O objetivo do nosso projeto é uma assistente virtual que auxilie produtores no processo de plantio das suas devidas culturas.

Funcionalidades iniciais
•	Instruir o público rural: A assistente visa ajudar agricultores a adotar práticas agroecológicas, com ênfase na eliminação de agroquímicos, que prejudicam tanto as plantas quanto a saúde humana. Isso é feito por meio de explicações sobre técnicas alternativas como adubação verde, compostagem e controle biológico de pragas. 
•	Monitoramento climático: Integrando com a API da Copernicus, a assistente será capaz de fornecer informações sobre o clima em tempo real, ajudando a determinar a melhor época para o plantio e a colheita, otimizando assim o uso de recursos naturais e promovendo uma agricultura mais eficiente e sustentável.
•	Integração com a API da Embrapa: A assistente utilizará a API da Embrapa para acessar informações sobre práticas agrícolas sustentáveis, pesquisas e tecnologias voltadas para a agricultura sem o uso de agroquímicos, assegurando a segurança alimentar e ambiental. 

APIs a serem utilizadas e suas funções.
CLIMAPI
•	Temperatura do ponto de orvalho a 2m da superfície (°C) 
•	Precipitação total na superfície (kg/m2) 
•	Velocidade do vento na superfície (m/s)
•	Percentual de cobertura de nuvens (alta, média e baixas) 
•	Taxa de evaporação potencial da superfície (mm/6h)
•	Umidade relativa a 2m da superfície (%) 
•	Temperatura máxima e mínima a 2m da superfície (ºC) 
•	Umidade volumétrica do solo nas seguintes camadas: de 0 a 10 cm, 10 a 40 cm e 40 cm a 1m 
•	Tempo de duração da luz do sol na superfície (s) 
•	Temperatura da superfície (ºC) 
•	Componentes do vento zonal (u) e meridional (v) a 10 m da superfície (m/s), a partir dos quais pode-se derivar a velocidade e direção do vento.
AGRITEC
•	Época de plantio com menores riscos de perda
•	Cultivares mais aptas – 12 culturas de plantio [amendoim, arroz (incluindo arroz irrigado), algodão, feijão, feijão-caupi, cevada, girassol, mamona, milho (1ª e 2ª safras), soja, sorgo, trigo]  com recomendação de acordo com a localidade.)
•	Recomendação de adubação
•	Previsões de produtividade
•	Balanço hídrico e condições climáticas antes e durante a safra
COPERNICUS

Tecnologias utilizadas
Plataforma de inteligência artificial do chatbot:
APIS:
Banco de dados (se necessário):
Backend:
Frontend:
Milestones 

Frontend
- [ ] Definir qual interface será utilizada (app, web)
- [ ] Utilização de um mapa interativo a ser utilizado

Backend
- [ ] Definir qual(is) API(s) serão utilizadas no projeto

Chatbot
- [ ] Definir qual plataforma será utilizada para a criação do chatbot

Documentação
- [ ] Organizar as milestones de acordo com as informações obtidas na reuniâo 05/04
- [ ] Documentar e comentar códigos:
      - [ ] Front-end
      - [ ] Back-end
      - [ ] Chat-bot


