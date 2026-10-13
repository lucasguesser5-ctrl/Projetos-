# 🛡️ Relatório de Ocorrência Pós-Trauma — Orbenk

Aplicação web desenvolvida para otimizar e padronizar o registo, gerenciamento e a emissão de relatórios técnicos de ocorrências para centrais de monitoramento de segurança patrimonial.

## 🚀 Funcionalidades Principais
- **Layout Adaptativo & Temas:** Alternância dinâmica entre temas (`Noturno`, `Escuro` e `Claro`) voltados para operadores de turno.
- **Integração Geográfica:** Visualização de mapas interativos via **Leaflet (OpenStreetMap, Satélite ESRI e Terreno)** e atalhos diretos para navegação no Google Maps.
- **Formulário Condicional Inteligente:** Exibição dinâmica de campos com base no status do atendimento (presença de vigilante, vítimas, horários de disparo e zonas de alarme).
- **Gestão de Evidências:** Anexo de imagens por *dropzone* com pré-visualização em miniaturas e exclusão dinâmica.
- **Impressão e Exportação Executiva (`@media print`):** Layout otimizado para formato **A4 Paisagem (Landscape)**, ocultando elementos de interface e estruturando um relatório técnico limpo para exportação em PDF.

## 🛠️ Tecnologias Utilizadas
- **HTML5 & CSS3** (Variáveis CSS, CSS Grid, Flexbox, Media Queries avançadas para impressão)
- **JavaScript (Vanilla)** (Manipulação do DOM, leitores de ficheiro, lógica condicional)
- **Leaflet.js** (Mapas interativos e marcação de coordenadas)

## 💻 Como Executar
1. Clone o repositório ou faça o download do ficheiro `index.html`.
2. Abra o ficheiro `index.html` diretamente em qualquer navegador moderno (Chrome, Firefox, Edge).
3. Preencha os campos da ocorrência e clique em **"🖨️ Imprimir / PDF"** para testar a geração do relatório em formato paisagem.
