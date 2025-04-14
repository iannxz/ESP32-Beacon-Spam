# 🛰️ Beacon Spam com ESP32 — Redes WiFi Falsas

# 📌 Descrição
Este projeto utiliza o ESP32 para simular centenas de redes WiFi falsas com nomes personalizados, usando a técnica conhecida como WiFi Beacon Spam. É ideal para testes de segurança, palestras educacionais e demonstrações de ataques sem fio, promovendo a conscientização sobre os riscos de redes não confiáveis.

⚠️ Este projeto é de uso estritamente educacional e visa promover boas práticas de segurança digital.

# 🚀 Recursos
📶 Criação de múltiplos SSIDs falsos
O ESP32 emite centenas de nomes de redes WiFi com nomes personalizados, emojis, símbolos e temas.

# 🧠 Código simples e adaptado para ESP32
Utiliza esp_wifi_80211_tx diretamente para enviar pacotes beacon de forma eficiente.

# 🎨 Personalização de nomes de redes
Adicione sua própria lista de SSIDs com temas criativos (tecnologia, humor, segurança etc.).

# ⚙️ Estável mesmo com grandes quantidades
Adaptado para suportar até 500 SSIDs com boa performance.

# 🧰 Requisitos
Placa ESP32 (preferencialmente DevKit)

Arduino IDE com suporte ao ESP32 instalado

Biblioteca esp_wifi.h (inclusa na framework do ESP32)

# 🛠️ Como Usar
Clone o repositório

bash
Copiar
Editar
git clone https://github.com/iannxz/ESP32-Beacon-Spam
Abra no Arduino IDE
Selecione a placa correta (ESP32 Dev Module).

Edite os SSIDs
No código, personalize a lista de SSIDs com nomes chamativos.

Compile e envie para o ESP32

Veja as redes falsas aparecerem
Verifique no seu smartphone ou notebook as redes WiFi emitidas.

# ⚠️ Aviso Legal
Este projeto é fornecido somente para fins educacionais e demonstrações controladas.
Não use em redes públicas, eventos ou ambientes que afetem terceiros sem consentimento.
O uso indevido pode configurar crime segundo as leis locais.

# 🤝 Contribua
Sugestões de melhorias, novas ideias para SSIDs, ou otimizações de código são bem-vindas!
Sinta-se livre para abrir uma issue ou enviar um pull request.

# 📄 Licença
Distribuído sob a licença MIT.
Você pode usar, modificar e compartilhar — com os devidos créditos.

# 🙏 Créditos
Este projeto foi criado por @iannxz e demonstra, de forma educativa, como redes WiFi falsas podem ser geradas usando um ESP32. Adaptado a partir de ideias anteriores voltadas para o ESP8266, o código foi totalmente reescrito e otimizado para o ESP32, com foco em estabilidade e personalização de SSIDs.
