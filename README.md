# ♿ Acess Drivers: Mobilidade Urbana com Dignidade e Inclusão

> **"A tecnologia só é avançada quando é inclusiva."** > O transporte deve ser para todos, sem exceções, desculpas ou cancelamentos.

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/rafaellagidaro/acess-drivers/blob/main/LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/rafaellagidaro/acess-drivers/pulls)
[![Deploy Status](https://img.shields.io/badge/Status-Live-success)](https://rafaellagidaro.github.io/acess-drivers/)

---

## 💡 A Motivação (Storytelling)
O **Acess Drivers** nasce de uma dor real e frequente. A ideia surgiu após sucessivas experiências negativas com minha mãe, usuária de cadeira de rodas. No cenário atual, motoristas de aplicativos convencionais frequentemente cancelam viagens ao visualizarem a cadeira, alegando falta de espaço (devido ao cilindro de gás) ou despreparo técnico.

Essas situações geram exclusão e insegurança. O Acess Drivers propõe um ecossistema onde a **necessidade do passageiro é a prioridade número um**, garantindo que o motorista parceiro já esteja equipado e treinado para oferecer um atendimento digno.

---

## 🚀 Demonstração Online
O projeto é um **PWA (Progressive Web App)** funcional que pode ser testado diretamente no navegador do seu smartphone:
👉 **[Acessar Acess Drivers - Caçapava](https://rafaellagidaro.github.io/acess-drivers/)**

---

## 🛠️ Arquitetura e Funcionalidades Técnicas

O projeto foi construído utilizando **Vanilla JavaScript (ES6+)**, focando em performance e acessibilidade nativa, sem dependências pesadas.

### 1. Camada de Segurança Crítica
* **🚨 Protocolo de Pânico "Press and Hold"**: Implementação de lógica de segurança que exige 3 segundos de pressão contínua para evitar acionamentos acidentais. Inclui feedback tátil (Vibration API) e visual (Flash).
* **🛡️ PIN de Validação Auditiva**: Geração de código de segurança que pode ser ditado pelo app para garantir que o usuário embarque no veículo correto.
* **🔗 Web Share API**: Integração nativa para compartilhamento de trajeto e status de segurança em tempo real via WhatsApp/Telegram.

### 2. Acessibilidade de Alta Engenharia (A11y)
* **🗣️ SpeechSynthesis API**: Interface assistida por voz para usuários com deficiência visual ou baixa visão.
* **🌓 Adaptive UI**: Suporte nativo ao modo escuro (Dark Mode) respeitando as preferências do sistema operacional.
* **♿ Categorização Especializada**: Algoritmo de filtragem que segmenta veículos por requisitos técnicos (Rampa Hidráulica, Cadeira Dobrável ou Cão Guia).

### 3. Resiliência e Monitoramento
* **🔋 Battery Status API**: Monitoramento proativo da bateria do usuário, sugerindo economia de energia ou avisos prioritários ao motorista em caso de carga crítica (<20%).
* **📍 Geolocalização & Mapas**: Renderização dinâmica de trajetos utilizando **Leaflet.js** e OpenStreetMap, com foco em baixo consumo de dados.
* **📊 Estrutura de DataLayer**: Preparado para integração com Google Tag Manager (GTM), permitindo análise de funil de conversão e comportamento do usuário.

---

## 💻 Stack Tecnológica

* **Frontend**: HTML5 Semântico, CSS3 (Custom Properties), JavaScript Puro (ES6).
* **Mapas**: Leaflet.js (Engine de mapas Open Source).
* **Iconografia**: FontAwesome 6.4.
* **Automação**: GitHub Pages para CI/CD (Continuous Deployment).

---

## 📖 Como Executar o Projeto Localmente

1.  Clone este repositório:
    ```bash
    git clone [https://github.com/rafaellagidaro/acess-drivers.git](https://github.com/rafaellagidaro/acess-drivers.git)
    ```
2.  Acesse a pasta do projeto:
    ```bash
    cd acess-drivers
    ```
3.  Abra o arquivo `index.html` em qualquer navegador moderno.

---

## 📈 Próximos Passos (Roadmap)
- [ ] Implementação de Chat com tradução automática para Libras (Vídeo).
- [ ] Integração com APIs de trânsito em tempo real (Google Maps/Waze).
- [ ] Backend em Firebase para persistência de dados de usuários e motoristas.

---

## 👤 Autor
**Rafaella Gidaro** - *Idealização e Desenvolvimento*

---
*Este projeto é dedicado a todos que acreditam que a tecnologia deve ser a ponte, e não o muro.*
