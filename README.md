# 🔍 Lucidworks + Drupal Search Diagrams

This repo contains PlantUML diagrams that illustrate how Lucidworks Fusion integrates with Drupal to enable federated search, query logic, and multi-site indexing architecture.

---

## ✅ Requirements

- macOS (tested on Sonoma and Ventura)
- [Java](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html) (JDK 11 or higher)
- [Graphviz](https://graphviz.org/download/) (for rendering diagrams)
- [PlantUML](https://plantuml.com/) (command line or extension)
- [Visual Studio Code](https://code.visualstudio.com/) + [PlantUML Extension](https://marketplace.visualstudio.com/items?itemName=jebbs.plantuml)

---

## 🚀 Installation Guide (macOS)

### 1. Install Homebrew (if not installed)
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

### 2. Install Graphviz (required for rendering diagrams)
```bash
brew install graphviz
```
### 3. Install Java (if not installed)
```
brew install openjdk@11
```
Add Java to your shell profile (e.g., .zshrc or .bash_profile):
```
export PATH="/opt/homebrew/opt/openjdk@11/bin:$PATH"
```
Then reload your shell:
```
source ~/.zshrc  # or source ~/.bash_profile
```

### 4. (Optional) Install PlantUML CLI
```
brew install plantuml
```


## 🧠 How to Use in Visual Studio Code

 1.	Open this project folder in VS Code.
 2.	Install the PlantUML extension by jebbs:
https://marketplace.visualstudio.com/items?itemName=jebbs.plantuml
 3.	Open any .puml file.
 4.	Press Cmd + P and run > PlantUML: Preview Current Diagram.
 5.	Or right-click and choose “Preview Current Diagram”.

To export:
	•	Right-click the diagram → “Export Current Diagram” → choose PNG/SVG.


## 📚 Official Docs
- PlantUML Docs
- Lucidworks Fusion Docs
- Graphviz Docs
- PlantUML Extension (VSCode)


## 📂 File Structure

```
.
├── diagrams/
│   ├── 01-sequence-user-query-flow.puml
│   ├── 02-ingestion-architecture-overview.puml
│   └── ...
├── assets/
│   └── exports/    # PNG/SVG outputs
└── README.md
```

## 🤝 Contributing

Feel free to open issues or pull requests to suggest improvements or new diagram types (e.g., index pipeline stages, federated query examples, etc.)

## 🧠 Tips

- You can use @startuml and @enduml inside Markdown files and preview them directly in VS Code using the PlantUML extension.
- You can edit UML without forking/cloning just go to https://editor.plantuml.com/uml/JP4v3iCW44NxEGKNI16lKeh8MUj4oWKmfa1om86XyEs36JiP2dZwJupueWieFSRt25CwZJAJj2WUZ6KGT-T0AdHUq3en9hs7taKxI3ylsPan-GAKi-ZTcEzS69ClGLiqEDFC6sFo5GmIPI-3Nh8hO_9rcZ-EMg5nDgJvVoRVm2VggDStFncJRo5jOdVCNSH1l9oWmYmlAD-ACbEIMIioKP6WRYolATywCTDietuDc6opoqsWqtPOlkqB and do your changes on live. 
- Another reference to use on live https://www.plantuml.com/plantuml/uml/SyfFKj2rKt3CoKnELR1Io4ZDoSa70000 which you can share your sequence diagram online.
