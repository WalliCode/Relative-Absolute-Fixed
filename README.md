# 📍 Posicionamento no CSS: `relative`, `absolute` e `fixed`

Este repositório explora os diferentes tipos de **posicionamento** no CSS: `relative`, `absolute` e `fixed`. Através de exemplos práticos, explicações e comparações visuais, você aprenderá como cada tipo de posicionamento afeta o layout e o comportamento dos elementos na página.

---

## 📂 Conteúdo

- **`relative`**  
  O elemento é posicionado em relação à sua posição original. Ele ainda ocupa o mesmo espaço no fluxo normal do documento.

- **`absolute`**  
  O elemento é posicionado em relação ao seu **elemento pai** mais próximo que tenha um `position` diferente de `static`.

- **`fixed`**  
  O elemento é fixado em uma posição específica da tela, mesmo quando a página é rolada.

---

## 📝 Tabela Comparativa

| **Propriedade**   | **Comportamento**                                                                                      | **Referência de Posição**              |
|-------------------|--------------------------------------------------------------------------------------------------------|----------------------------------------|
| `relative`        | Move o elemento em relação à sua posição original, sem afetar o fluxo do documento.                    | Posição original do elemento.         |
| `absolute`        | Retira o elemento do fluxo e o posiciona em relação ao primeiro elemento pai posicionado.              | Elemento pai com `position` diferente de `static`. |
| `fixed`           | Fixa o elemento em uma posição específica na tela, independentemente do rolar da página.               | Tela (viewport).                       |

---
