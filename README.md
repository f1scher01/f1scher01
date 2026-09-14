# Olá, sou o Lucas Fischer Paez 👋

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lucasfischerpaez)
[![Email](https://img.shields.io/badge/Email-fischer.paez%40gmail.com-red?logo=gmail&logoColor=white)](mailto:fischer.paez@gmail.com)
[![Portfólio](https://img.shields.io/badge/Portf%C3%B3lio-PT%20%C2%B7%20EN%20%C2%B7%20FR%20%C2%B7%20ES-f29d3d)](https://lucasfischer-portfolio.vercel.app)
[![Web App](https://img.shields.io/badge/Web%20App-notas--cr--maua.vercel.app-blueviolet)](https://notas-cr-maua.vercel.app)

Estudante do 2º ano de **Engenharia Mecânica** no **Instituto Mauá de Tecnologia (IMT)**, com
coeficiente de rendimento 8,23 e certificação **Lean Six Sigma Green Belt**.

Trabalho na fronteira entre **engenharia física, aquisição de dados e desenvolvimento de
software**: modelar um fenômeno, simular, medir o que de fato acontece e usar o resultado para
melhorar o projeto.

---

### 🛠️ Competências

* **Programação e análise numérica:** Python (NumPy, Pandas, Matplotlib), TypeScript, JavaScript,
  MATLAB, Minitab. Métodos iterativos, interpolação polinomial e ajuste por mínimos quadrados.
* **Simulação estrutural:** Ansys Workbench e Mechanical — elementos finitos, geração de malha,
  condições de contorno, tensão de von Mises. Formação complementar pelo Instituto ESSS.
* **CAD:** CATIA / 3DEXPERIENCE, Siemens NX, SolidWorks, AutoCAD.
* **Seleção de materiais:** Ansys Granta EduPack — constrições, índices de mérito, análise de custo.
* **Dados e observabilidade:** Grafana, InfluxDB, Docker, séries temporais.
* **Geoespacial:** NetCDF-4 de satélite (GOES-19 ABI) com GDAL, reprojeção de grade
  geoestacionária, filtragem por flag de qualidade, GeoTIFF, GeoJSON e GeoPackage, SIRGAS 2000 /
  UTM 23S, PyQGIS (simbologia e layouts gerados por script).
* **Qualidade e processo:** Lean Six Sigma Green Belt, ciclo DMAIC.
* **Idiomas:** Português nativo · Espanhol avançado · Inglês avançado · Francês intermediário
  (TCF Tout Public: **B1 global, compreensão oral e escrita em B2**).

---

### 🚀 Projetos

#### 🛰️ [Poluição do ar e saúde na RMSP: GOES-19 × CETESB × SIH/SUS × QGIS](https://github.com/f1scher01/cetesb-air-quality-sp) · `dados reais`
Pipeline que liga AOD de satélite, rede de superfície, internações do SUS e limites oficiais na
Região Metropolitana de São Paulo, rodando no Python do QGIS.
* Ingestão de NetCDF-4 do GOES-19 (AOD 550 nm), reprojeção da grade geoestacionária com GDAL e
  descarte de pixels por flag de qualidade.
* Coleta automatizada da rede CETESB pelo serviço público do QUALAR, com inversão do índice de
  qualidade do ar para µg/m³ e pontos de quebra verificados nos próprios dados.
* Leitura direta dos arquivos DBC do SIH/SUS: 230 mil internações respiratórias e circulatórias de
  residentes da RMSP em 12 meses, agregadas por município e integradas à população do IBGE e ao
  satélite numa camada GeoPackage.
* Mapas montados por PyQGIS, sem abrir a interface. Os READMEs registram o que o dado sustenta e o
  que ainda não: sem correlação satélite × estação num único scan (r = 0,09) e taxas brutas que
  refletem dependência do SUS, não poluição.
* **Stack:** Python, GDAL, PyQGIS, NumPy, Pandas, SciPy.

#### 🏎️ [Simulador de Telemetria e Stack de Séries Temporais](https://github.com/f1scher01/telemetria-veicular-grafana) · `dados simulados` · [![Painel](https://img.shields.io/badge/Grafana%20Cloud-painel%20público-F46800?style=flat-square&logo=grafana&logoColor=white)](https://fischerpaez.grafana.net/public-dashboards/5ea12a828dd1478eb54041c8624531d0)
Pipeline completo de geração, ingestão, persistência e visualização de séries temporais.
* Modelo físico a 10 Hz: avanço por distância percorrida, G lateral por v²/R e térmica de primeira
  ordem; o tempo de volta sai do modelo, não de uma constante.
* Ingestão via InfluxDB Line Protocol, persistência em InfluxDB 2.7, orquestração em Docker.
* Dashboard Grafana com consultas Flux provisionado automaticamente e cockpit web autônomo.
* **A telemetria é gerada por simulação.** Não há veículo instrumentado.
* **Stack:** Python, InfluxDB, Grafana, Docker, séries temporais.

#### 📱 [PWA de Acompanhamento Acadêmico](https://github.com/f1scher01/notas-cr-maua-pwa) · `em produção`
Aplicação web que modela as regras de avaliação de oito disciplinas e projeta médias e
coeficiente de rendimento em tempo real.
* Implementa as regras de prova substitutiva de cada disciplina a partir dos planos de ensino.
* **Em uso real por colegas de curso.**
* **Stack:** HTML, CSS e JavaScript sem framework, Service Worker, Vercel.

---

### 🎓 Formação e distinções

* **Bacharelado em Engenharia Mecânica** — Instituto Mauá de Tecnologia (conclusão prevista em
  12/2029). Coeficiente de rendimento 8,23.
* **Défi InterAlliances 2026** — 1º lugar na etapa local (Alliance Française Grande ABC) e **4º
  lugar na final nacional brasileira**, com a maior taxa de acerto da final.
* **Lean Six Sigma Green Belt** — projeto DMAIC aplicado ao sistema de inscrição em atividades
  do IMT; a proposta foi entregue e o sistema reformulado no ano seguinte.
* **TCF Tout Public** — France Éducation International, 2026.
