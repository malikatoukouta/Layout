# Notes CSS : Flexbox vs Grid

## Flexbox

Flexbox sert surtout à aligner des éléments sur un seul axe qu'il soit horizontal ou vertical.

### Quand utiliser Flexbox ?

- Pour une navbar
- Pour aligner un logo et des liens
- Pour centrer un élément
- Pour gérer des boutons côte à côte
- Pour organiser une carte en colonne
- Pour aligner des éléments dans un header ou footer

### Exemple

```css
.container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}
```

## Grid

Grid sert surtout à créer des mises en page en deux dimensions : lignes et colonnes.

### Quand utiliser Grid ?

- Pour un layout complet de page
- Pour une galerie de cartes
- Pour un dashboard
- Pour placer header, main, sidebar et footer
- Pour créer des colonnes responsives facilement

### Exemple

```css
.page {
    display: grid;
    grid-template-areas: "header header" "main sidebar" "footer footer";
    grid-template-columns: 3fr 1fr;
    gap: 20px
}
```