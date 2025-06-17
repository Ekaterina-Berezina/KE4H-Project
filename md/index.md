---
layout: default
title: Home
---

<style>
  h1.title {
    font-family: 'Dosis', sans-serif;
    font-weight: 700;
    color: #1a1a1a;
    text-align: center;
    margin-top: 40px;
  }

  p.subtitle {
    font-size: 18px;
    color: #555;
    text-align: center;
    max-width: 800px;
    margin: 0 auto 40px;
  }

  .menu {
    text-align: center;
    margin-bottom: 30px;
  }

  .menu a {
    display: inline-block;
    margin: 0 10px;
    font-weight: bold;
    color: #0366d6;
    text-decoration: none;
  }

  .image-grid {
    display: flex;
    gap: 20px;
    justify-content: center;
    flex-wrap: wrap;
  }

  .image-grid div {
    flex: 1;
    max-width: 300px;
    text-align: center;
  }

  .image-grid img {
    width: 100%;
    border-radius: 8px;
  }
</style>

<h1 class="title">Augmenting Cultural Heritage Data</h1>
<p class="subtitle">Combining SPARQL and LLMs to expand The Bolognese School (Guercino’s and Guido Reni’s paintings Wikidata profiles)</p>

<div class="menu">
  <a href="index.md">HOME</a>
  <a href="wikidata.md">WIKIDATA</a>
  <a href="sparql.md">SPARQL QUERIES</a>
  <a href="llm.md">LLM PROMPTS</a>
  <a href="rdf.md">RDF TRIPLES</a>
</div>

## About the Project

Our cultural heritage project focuses on enriching **Wikidata** entries related to the **Bolognese School**, particularly the works of **Guercino** and **Guido Reni**.

---

## Methodology

<div class="image-grid">
  <div>
    <img src="img/query11.jpg" alt="Guercino">
    <p><b>Guercino</b> (Q334262)<br><i>Madonna col Bambino...</i></p>
  </div>
  <div>
    <img src="img/query12.jpg" alt="Guido Reni">
    <p><b>Guido Reni</b> (Q109061)<br><i>The Madonna and Sleeping Child</i></p>
  </div>
</div>

1. We investigated the **Wikidata** knowledge base...  
2. Using **SPARQL**, we identified missing data...  
3. To fill these gaps, we integrated **LLMs**...  
4. We created **RDF triples**...

---

## Conclusion

This project illustrates how **AI-powered inference**, **SPARQL**, and **human validation** can enhance open cultural knowledge.

---

## Team

- Saida Tynyshbek  
- Gaukhar Serikbay  
- Ekaterina Berezina  
- Dinara Khassenova
