---
layout: default
title: Home
---

# Augmenting Cultural Heritage Data
### Combining SPARQL and LLMs to expand The Bolognese School (Guercino’s and Guido Reni’s paintings Wikidata profiles)

---

[HOME](index.md) | [WIKIDATA](html/wikidata.md) | [SPARQL QUERIES](html/sparql.md) | [LLM PROMPTS](html/llm.md) | [RDF TRIPLES](html/rdf.md)

---

## HOME

### ABOUT THE PROJECT

Our cultural heritage project focuses on enriching Wikidata entries related to the **Bolognese School**, particularly the works of Baroque painters **Guercino** and **Guido Reni**. Such a choice is justified by the fact that their works are well-represented yet incomplete on Wikidata.

---

### METHODOLOGY

**Subjects of Analysis**:

<div style="display: flex; gap: 30px;">
  <div style="width: 45%;">
    <img src="img/query11.jpg" alt="Guercino" style="width:100%;">
    <p><b>Guercino</b> (Q334262), painting <i>Madonna col Bambino in gloria con san Pancrazio e una santa monaca</i> (Q134065073)</p>
  </div>
  <div style="width: 45%;">
    <p><b>Guido Reni</b> (Q109061), painting <i>The Madonna and Sleeping Child</i> (Q119922630)</p>
    <img src="img/query12.jpg" alt="Guido Reni" style="width:100%;">
  </div>
</div>

1. We investigated the **Wikidata** knowledge base to uncover incomplete entries for paintings by Bolognese School artists, focusing on missing details such as location and materials.

2. Using **SPARQL**, we identified missing data — such as painting locations or materials — that could significantly enhance data quality.

3. To fill these gaps, we integrated **Large Language Models** (LLMs), including **Gemini** and **ChatGPT**, then verified the results through trusted external sources like [Wikipedia (IT)](https://it.wikipedia.org/wiki/Pagina_principale) and [ArtUK](https://artuk.org/) to ensure accuracy.

4. Finally, we created **RDF triples** using Wikidata’s ontology to update its data.

💎 This project illustrates how **AI-powered inference**, combined with **SPARQL** and **human validation**, can effectively bridge data gaps in cultural knowledge graphs.

---

### CHALLENGES AND SOLUTIONS

**SPARQL Query Design**  
One of the key challenges was extracting accurate and relevant data from Wikidata. To overcome this, we engaged in iterative testing and refinement of our SPARQL queries, gradually improving both precision and coverage.

**LLM-Generated RDF Errors**  
The RDF triples produced by language models often contained incorrect properties or QIDs. We addressed this by manually verifying the data in Wikidata and reconstructing the triples using correct and validated identifiers.

**Website Development**  
With no prior experience using tools like PyCharm or GitHub, we faced a steep learning curve. Through research, experimentation, and collaboration, we adopted best practices for building a clear and functional website.

By working together and approaching each obstacle with curiosity and persistence, we turned difficulties into meaningful learning opportunities and ultimately delivered a robust and cohesive semantic web project.

---

### CONCLUSION

This project combines automation with expert review to enhance open cultural data. All SPARQL queries, prompts, RDF triples, and results are available throughout this website.

---

### TEAM

- Saida Tynyshbek  
- Gaukhar Serikbay  
- Ekaterina Berezina  
- Dinara Khassenova
