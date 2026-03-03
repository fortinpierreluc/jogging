# Convertisseur de Course

Une application web simple et élégante pour convertir rapidement les données de course.

## Fonctionnalités

### Calculateur Vitesse
Convertit instantanément entre :
- Vitesse (Km/h)
- Allure (Min:sec/km)
- Vitesse (Miles/h)
- Allure (Min:sec/mile)

### Calculateur Distance
Convertit entre :
- Kilomètres
- Miles

## Utilisation

1. Ouvrez `index.html` dans votre navigateur
2. Entrez une valeur dans n'importe quel champ
3. Les autres champs se mettent à jour automatiquement

### Format d'entrée
- Nombres : utilisez la virgule (,) ou le point (.) comme séparateur décimal
- Allure : entrez au format `MM:SS` (ex: 6:30) ou juste les minutes (ex: 6)

## Démarrage rapide

### Serveur local avec Python
```bash
python -m http.server 8000
```
Puis ouvrez http://localhost:8000 dans votre navigateur.

## Structure du projet
```
Jogging/
├── index.html          # Application principale
├── Public/
│   └── Jogging.jpg     # Image décorative
└── README.md           # Documentation
```

## Technologies
- HTML5
- CSS3 (design moderne et responsive)
- JavaScript vanilla (pas de dépendances)

## Design
- Fond bleu apaisant (#0077b6)
- Interface épurée et moderne
- Responsive pour mobile et desktop
