# Wool Ontology Project

This repository contains an **RDF ontology** that captures the characters, locations, events, and items of Hugh Howey’s *Wool* series. Please note: The files include significant spoilers for the *Wool* books and differ from the Apple TV adaptation, *Silo*. 

## Purpose of This Project

- **World-Building**: Provides a structured knowledge model (ontology) of *Wool*, allowing fans to explore relationships among characters and locations, and easily build applications with this rich data.  
- **Semantic Web Exploration**: Demonstrate how RDF can be used to capture a fictional universe for educational or fandom purposes.  
- **Collaboration**: Allow contributors to expand or refine the ontology as they parse more chapters or discover new details.

## File Format

All ontology data is stored in **Resource Description Framework** (`.rdf`) format.

- **[`Wool.rdf`](./Wool.rdf)** – The main file defining classes, properties, individuals, and annotations.  
- Additional `.rdf` files may be present for different sections/chapters (none published so far).

## How to View / Edit

You can open or edit the `.rdf` files in any text editor, but for a more semantic-oriented experience, consider using:

1. **Protégé** – A free and popular ontology editor.  
   - Download from [https://protege.stanford.edu/](https://protege.stanford.edu/)  
   - File → Open → select your `.rdf` file.  
   - Configure “Show imported ontologies” if relevant.
   - You can also open the file directly in Protégé using the URL [Wool.rdf](https://raw.githubusercontent.com/turbotas/WoolOntology/refs/heads/main/Wool.rdf). Note that edits made in this mode will not be saved.

2. **Visual RDF Tools** – Tools such as [VOWL](http://vowl.visualdataweb.org/webvowl.html) or [GraphDB](https://www.ontotext.com/products/graphdb/) can be used to visualize classes and properties as an interactive graph.

3. **Command-Line Tools** – If you prefer the console, you can use `riot` (Apache Jena) or `rapper` (Raptor) to parse/validate the Turtle.

## Spoiler Warning

- This ontology **directly references major plot points** from *Wool*.  
- It is **based on the original book series** by Hugh Howey and **not** on the Apple TV adaptation.  
- Many details here **differ from or go beyond** the show.
- If you haven’t read the *Wool* series, you will encounter **major spoilers** in the ontology data.

---

## Contributing

If you’d like to add more details or refine the ontology:
1. Fork this repo,  
2. Make your changes in a branch,  
3. Submit a pull request.

We welcome contributions and corrections; please maintain focus on the original *Wool* books. If referencing details from the TV adaptation or fan fiction, clearly indicate the source to avoid confusion. Use the `extractedSentence` field to include a brief snippet from the book for context—please keep it minimal to adhere to fair use guidelines. If you enjoy the series, please consider purchasing the book; it is a classic dystopian masterpiece.

**Canon:** We consider the books to be canon. However, it is valuable to enrich this work with details from the TV series or even fan fiction, provided they do not contradict the original narrative. For example, while this project describes stairs and stairwells as depicted in the books, the TV series presents them differently. Additional context from other sources may be included if it enhances the primary narrative.

**Thanks for exploring the Wool Ontology Project!** Feel free to open an [issue](https://github.com/turbotas/WoolOntology/issues) or [pull request](https://github.com/turbotas/WoolOntology/pulls) with questions or enhancements.

## Examples

Below is an example command using Apache Jena's riot tool to validate your RDF file:

```bash
riot Wool.rdf
```

