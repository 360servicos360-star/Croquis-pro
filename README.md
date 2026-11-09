# Croquis Pro

Ferramenta web em português para preparar croquis de localização com mapa de satélite, ponto de referência, retângulo do terreno, cálculo de área/perímetro, tabela de coordenadas UTM/WGS84 e impressão/guardar como PDF.

## Utilização

1. Abra `index.html` num navegador moderno (ou publique o repositório com GitHub Pages).
2. Preencha os dados do processo e introduza as coordenadas decimais confirmadas do ponto de referência.
3. Informe largura, comprimento e azimute do lado da largura. Por definição, 90° significa orientação Este–Oeste.
4. Confira o polígono, as coordenadas e os cálculos; use **Imprimir / Guardar PDF** para gerar a folha A4.
5. **Guardar projeto** exporta um JSON que pode ser reaberto mais tarde.

A aplicação usa Leaflet e imagens de satélite Esri através da internet. As coordenadas dos vértices são estimativas calculadas a partir do ponto e das dimensões informadas; a ferramenta não substitui levantamento de campo nem valida limites legais. Confirme a posição, orientação e dimensões com o responsável técnico antes de entregar documentos oficiais.
