# Wool Ontology Project

This repository contains an **RDF ontology** capturing characters, locations, events, and items from Hugh Howey’s *Wool* series. **Be warned**: The files here include **significant spoilers** for the *Wool* **books**, which also deviates significantly from the events of the Apple TV "Silo" Series. 

## Purpose of This Project

- **World-Building**: Provide a structured knowledge model (ontology) of *Wool* so fans can browse relationships among characters and locations, or build applications on top of this data.  
- **Semantic Web Exploration**: Demonstrate how RDF can be used to capture a fictional universe for educational or fandom purposes.  
- **Collaboration**: Allow contributors to expand or refine the ontology as they parse more chapters or discover new details.

## File Format

All ontology data is stored in **Resource Description Framework** (`.rdf`) format.

- **`Wool.rdf`** – The main file defining classes, properties, individuals, and annotations.  
- Additional `.rdf` files may be present for different sections/chapters (none published so far).

## How to View / Edit

You can open or edit the `.rdf` files in any text editor, but for a more semantic-oriented experience, consider using:

1. **Protégé** – A free and popular ontology editor.  
   - Download from [https://protege.stanford.edu/](https://protege.stanford.edu/)  
   - File → Open → select your `.rdf` file.  
   - Configure “Show imported ontologies” if relevant.
   - You can also open the file in Protege direct using the URL https://raw.githubusercontent.com/turbotas/WoolOntology/refs/heads/main/Wool.rdf but obviously no edits will be saved!

2. **Visual RDF Tools** – E.g., **VOWL** or **GraphDB**.  
   - Some let you visualize classes/properties as a graph.

3. **Command-Line Tools** – If you prefer the console, you can use `riot` (Apache Jena) or `rapper` (Raptor) to parse/validate the Turtle.

## Spoiler Warning

- This ontology **directly references major plot points** from *Wool*.  
- It is **based on the original book series** by Hugh Howey and **not** on the Apple TV adaptation.  
- Many details here **differ from or go beyond** the show.
- If you haven’t read the *Wool* series, you will encounter **major spoilers** in the ontology data.

---

### Contributing

If you’d like to add more details or refine the ontology:
1. Fork this repo,  
2. Make your changes in a branch,  
3. Submit a pull request.

We welcome corrections and expansions—just remember to keep the scope focused on the *Wool* books.
If referencing the TV adaptation or even fanfic, please make sure the origin is clear to avoid mixing details. There is an **extractedSentence** field to include the context from the book: please do not put anything more than a tiny snippet of the book here - we don't want to go beyond fair use.  Please buy the book - it's a classic dystopian future work, thanks Hugh!

**Canon** - We consider the books to be canon, but it's great to enrich this work with details from the TV series or even fan fiction where the details don't contradict.  As example of this: in this work we describe the stairs and stairwell as they appear in the books as the TV series differs considerably.  But where there are details from the Pact that appear in the TV series but are not in the books, we include them here to enrich the work. Same with Fan Fiction as long as it doesn't contract either the books or the TV Series then why not include it?

**Thanks for exploring the Wool Ontology Project!** Feel free to open an issue or pull request with questions or enhancements.
