# Iniciativas de Computação Física & IoT da UFES no combate ao covid-19

#### [Prof. Roberto Colistete Jr.](mailto:roberto.colistete@gmail.com) - [Dep. de Química e Física - CCENS - UFES-Alegre](http://alegre.ufes.br/ccens/departamento-de-quimica-e-fisica)

## Objetivos :
- entregar a instuições públicas como hospitais, etc, em prazo de (poucas) semanas, dispositivos empregando Computação Física (sensores + atuadores + microcontroladores/computadores de placa única) & IoT (WiFi, Bluetooth, LoRa, etc) úteis para atividades relacionadas com combate ao covid-19, direta ou indiretamente;
- integrar, motivar e coordenar (ex-)alunos da UFES para participar no esforço necessário para combater ao covid-19, fundamental para o futuro da sociedade humana a médio prazo.

## Metodologia :
- direcionar parte dos esforços dos envolvidos em projetos de Computação Científica e IoT da UFES para auxiliar no combate ao covid-19. A contribuição de outros voluntários externos a esses projetos também será bem-vinda;
- uso dual de projetos já envolvidos, com adaptações pequenas para aplicação diversa do que foi planejado;
- criação de novos projetos visando especificamente atividades de combate ao covid-19;
- uso de trabalho à distância colaborativo entre várias pessoas via ferramentas diversas como repositórios, emails, 
videoconferências, redes sociais, etc;
- apresentação/publicação de resultados em repositórios públicos, sites, blogs, redes sociais, conferências, revistas científicas, etc.

## Projetos :

### 1) Instrumentação médica

Uso de sensores e atuadores com qualidade suficiente para uso médico :

1.1) [uPyBodyTempIR - Body Temperature IR Meter with MLX90615 sensor and MicroPython microcontroller](https://github.com/rcolistete/uPyBodyTempIR) : a low cost and open device to detect human body (head) temperature to help detect fever (due to covid-19 or not), using IoT (when available);

1.2) [capnógrafo](https://en.wikipedia.org/wiki/Capnography) usando [sensor I2C SCD30 de gás CO2](https://www.sensirion.com/en/environmental-sensors/carbon-dioxide-sensors/carbon-dioxide-sensors-co2/) ? Esse tipo sensor, NDIR, é usado em [capnógrafos profissionais](https://www.howequipmentworks.com/capnography/), que custam milhares de R$. O dispositivo usaria tela para interface local e IoT (via WiFi ou LoRa) para monitorar e alertar sobre índices anormais; 

### 2) Automação e ferramental hospitalar

Dispositivos diversos para monitorar condições de funcionamento dos ambientes, equipamentos, etc, hospitalares

2.1) dispositivos para monitorar funcionamento de equipamentos mecânicos (p. e., ventiladores respiratórios) via vibração detectada por acelerômetro (e/ou geofone ?), usando IoT (WiFi ou LoRa ou SigFox) para monitorar e alertar sobre não funcionamento, etc;

2.2) nano-micro espectrômetros portáteis para medição de espectros de transmissão de concentração de materiais (de higiene, etc) usados em hospitais, p. e., para obter a concentração correta de água sanitária com água, etc;

2.3) dispositivo com sensor Geiger para medição de radiação em salas com raios-X, para monitorar se as dosagens dos funcionários e pacientes estão dentro dos padrões permitidos. Usando IoT (WiFi ou LoRa ou SigFox) para monitorar e alertar sobre não funcionamento, etc;

2.4) dispositivo com [magnetômetro fluxgate FLC-100](https://www.stefan-mayer.com/en/products/magnetometers-and-sensors/magnetic-field-sensor-flc-100.html) para monitorar se campo magnético está dentro de padrões aceitáveis em ambientes hospitalares (para evitar interferência em equipamentos de UTI, bem como niveis saudáveis para as equipes médicas e pacientes). Versão portátil ou fixa, mas pode também fazer uso de  IoT (WiFi ou LoRa ou SigFox) para monitorar e alertar sobre níveis altos, etc;

### 3) Monitoramento e Vigilância

Dispositivos diversos para monitorar remotamente via IoT Cloud condições ambientais, bem como fazer vigilância de locais, permitindo menor presença humana e distanciamento social. Tais itens abaixo também são aplicáveis na categoria acima.

3.1) monitoramento com sensores de temperatura e umidade de ambientes (datacenters, hospitais, etc) que precisam dessas grandezas controladas, p. e., que tenham ar-condicionado, frigorífico, etc, funcionando dentro de uma janela de temperatura & umidade aceitáveis. Uso de IoT (WiFi ou LoRa ou SigFox) para monitorar e alertar sobre não funcionamento, etc;

3.2) monitoramento de qualidade do ar com sensores de [VOC (CCS811)](https://ams.com/ccs811) e de [gás CO2 (SCD30)](https://www.sensirion.com/en/environmental-sensors/carbon-dioxide-sensors/carbon-dioxide-sensors-co2/) em ambientes com  presença humana. Uso de IoT (WiFi ou LoRa ou SigFox) para monitorar e alertar sobre índices não saudáveis;

3.3) monitoramento de presença e vigilância de ambientes via sensores de distância IR (detectando abertura de porta, pessoa passando, etc), de luz (acendida ao alguém entrar em sala), PIR (presença infravermelha), etc. Uso de IoT (WiFi ou LoRa ou SigFox) para monitorar e alertar ocorrências;

### 4) Comunicação de longa distância sem infraestrutura convencional

Uso de LoRa ou SigFox em ambientes sem infraestrutura de WiFi, 3G/4G ou mesmo energia elétrica para comunicação de dados de sensores, geolocalização, mensagens curtas de pessoas, etc.

4.1) nó LoRaWan/LoRa-Mac para envio de dados de sensores diversos, com baixo consumo de energia, com alimentação opcional via painel solar;

4.2) nó LoRa-Mac com protocolo optimizado para comunicação ponto-a-ponto (e talvez LoRa Mesh), sem precisar de gateway (concentrador), para enviar/receber mensagens curtas, posicionamento GPS, etc. Capaz de varrer canais, ter teclas para entrada de texto, ser portátil, com baixo consumo de energia, com alimentação opcional via painel solar.

**Mais ideias ???**


