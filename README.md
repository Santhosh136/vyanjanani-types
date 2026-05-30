# Sanskrit Vyanjani Types

An interactive webpage showcasing Sanskrit consonants (Vyanjani) organized by their phonetic classifications.

## Features

- **Organized by Position**: Consonants displayed vertically by their position within each varga (consonant class)
- **Interactive Filters**: Four phonetic classification filters:
  - **Alpa Prana** (Unaspirated): Light/unaspirated consonants
  - **Maha Prana** (Aspirated): Heavy/aspirated consonants
  - **Karkasha** (Hard): Velar and palatal consonants
  - **Mrdu** (Soft): Labial, dental, and retroflex consonants

- **Responsive Design**: Mobile-friendly layout that works on all devices
- **Color Highlighting**: Vibrant colors for each filter with gradient combinations when multiple filters are selected
- **Classical Typography**: Elegant serif fonts (Crimson Text & Lora) for refined presentation

## Consonant Organization

### Vargiya Vyanjani (Grouped Consonants)

| V1 | V2 | V3 | V4 | V5 |
|----|----|----|----|-----|
| क | ख | ग | घ | ङ |
| च | छ | ज | झ | ञ |
| ट | ठ | ड | ढ | ण |
| त | थ | द | ध | न |
| प | फ | ब | भ | म |

### Avargiya Vyanjani (Ungrouped Consonants)

**R1**: य, र, ल, व  
**R2**: श, ष, स, ह

## Filter Mappings

- **Alpa Prana**: V1, V3, V5, R1
- **Maha Prana**: V2, V4, R2
- **Karkasha**: V1, V2, R2 (except ह)
- **Mrdu**: V3, V4, V5, R1, ह

## How to Use

1. Click any filter button to highlight consonants with that property
2. Select multiple filters to see consonants that match all selected properties
3. Unmatched consonants are dimmed for clarity
4. Hover over consonants for interactive feedback

## Built With

- HTML5
- CSS3 (Grid, Flexbox, Responsive Design)
- Vanilla JavaScript
- Google Fonts (Crimson Text, Lora)

## Live Demo

Visit the deployed version on [Vercel](https://vyanjanani-types.vercel.app)
