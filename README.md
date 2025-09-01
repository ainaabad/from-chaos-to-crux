# From Chaos to Crux — Climbing Route Search Engine

**One-liner:** From 12k+ climbing blog posts to a structured dataset of 4k multi-pitch routes enriched with attributes, maps, and recommendations.

## Context
This project was developed during the **Data Science Bootcamp at CodeOp** together with Maria <surname>.  
Motivation: climbers often rely on fragmented blog posts for route information. Our goal was to centralize this knowledge into a structured, searchable dataset.

## Dataset
- 12,000+ blog posts scraped  
- 4,000 unique routes identified  
- 15+ attributes per route (grade, length, pitches, wall, zone, orientation, equipment, etc.)  
- 4 sentiment scores extracted from blog content (enjoyment, difficulty perception, quality, risk)

## Prototype
- Search engine with filters: max grade, obligatory grade, orientation, length, number of pitches, equipment  
- Integrated geolocation search: enter a place, define a radius → get routes nearby  
- Results show route attributes + direct links to original blog posts (to keep context and credibility)

## Tools & Methods
- **Scraping:** BeautifulSoup  
- **NLP:** spaCy (NER), fuzzy matching  
- **Unsupervised ML:** clustering for cleaning and unifying route names/walls  
- **Visualization:** Folium maps  
- **Environment:** Google Colab, Python

## Demo
- 📊 Presentation slides: [FromChaosToCrux.pdf](docs/FromChaosToCrux.pdf)  
- (Optional) add screenshots or a short GIF of the prototype
