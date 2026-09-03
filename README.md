# 🗺️ Cartografia no Gesso: Sequência Didática Digital

> **Aprender Cartografia conhecendo e representando o lugar onde vivemos.**

Recurso Educacional Aberto (REA) voltado ao Ensino de Geografia na Educação Básica. O aplicativo guia os estudantes por uma sequência didática contextualizada no semiárido e no Polo Gesseiro, integrando conceitos fundamentais de altimetria à modelagem tátil de relevo tridimensional em placas de gesso.

---

## 🎯 Proposta Pedagógica

A sequência didática foi desenhada para superar a abstração bidimensional dos mapas convencionais por meio de uma abordagem prática, ativa e tátil. 

Ao utilizar o **gesso** (recurso mineral de grande relevância socioeconômica regional), o projeto conecta:
* Noções espaciais e alfabetização cartográfica (*curvas de nível, escala, declividade e hipsometria*).
* Reconhecimento do espaço vivido, relevo semiárido (*inselbergs, chapadas e vales*) e pertencimento territorial.
* A metodologia de fatiamento topográfico e culminância em oficinas manuais.

---

## 📚 Estrutura da Trilha (11 Módulos)

1. **🧠 O que eu já sei?** — Diagnóstico prévio de noções espaciais e relevo local.
2. **📍 Onde estamos?** — Localização geográfica, coordenadas e limites municipais.
3. **📖 Aprendendo Cartografia** — Fundamentos técnicos, elementos do mapa e curvas de nível.
4. **🪨 Conhecendo o Polo Gesseiro** — Gênese da gipsita e relevância geoeconômica.
5. **🌵 Cartografia e Caatinga** — Morfologia do semiárido e sua relação com a paisagem.
6. **🛰️ Analisando imagens** — Sensoriamento remoto básico e modelos digitais de elevação.
7. **🔎 Investigando o território** — Recorte espacial e problematização de encostas.
8. **✏️ Construindo o mapa** — Fatiamento das cotas e geração de gabaritos em folha A4.
9. **🧱 Mapa na placa de gesso** — Culminância: calculadora de dosagem e cronômetro de cura.
10. **🎤 Apresentando meu mapa** — Diário de bordo, envio de evidências fotográficas e síntese reflexiva.
11. **✅ Avaliação** — Autoavaliação, consolidação de saberes e emissão de relatório.

---

## 🛠️ Tecnologias Utilizadas

O projeto foi inteiramente concebido sob a filosofia de **arquitetura estática e leve**, garantindo compatibilidade com redes móveis e dispositivos escolares modestos:

* **HTML5 Semântico:** Estruturação acessível e nativa.
* **Tailwind CSS (via CDN):** Interface responsiva otimizada para smartphones e desktops.
* **JavaScript Puro (Vanilla JS):**
  * Manipulação dinâmica de gráficos vetoriais (`SVG`).
  * Persistência de progresso local via `localStorage`.
  * Síntese de alertas sonoros de bancada via `Web Audio API`.
  * Redimensionamento e compressão de imagens via `HTML5 Canvas`.
  * Mecanismo de impressão em folhas A4 com folhas de estilo `@media print`.

---

## 📂 Organização dos Arquivos

```text
├── index.html        # Menu principal, barra de progresso e leitor da trilha
├── oficina.html      # Módulo 9: Calculadora de gesso/água e cronômetro sonoro
├── passo2.html       # Módulo 8: Biblioteca de relevo e gabarito de fatiamento (PDF)
├── passo3.html       # Módulo 3: Simulador de cores hipsométricas e elementos do mapa
├── passo4.html       # Módulo 10: Diário de bordo fotográfico e relatório técnico
└── README.md         # Documentação do projeto
