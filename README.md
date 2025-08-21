# SQL Control Flow & AI-Powered Data Analysis Notebook

![Notebook Preview](link-to-your-image-or-screenshot)

## Overview

This project is an interactive **Jupyter Notebook** designed to teach and practice **SQL control flow functions** (`CASE`, `COALESCE`, `NULLIF`, `IF`) and **SQL Views**, using a **story-driven, real-world dataset** of recipes.

Students also learn to leverage **AI tools** (e.g., ChatGPT, Claude) to generate, refine, and debug SQL queries while reflecting critically on AI-assisted solutions.

The notebook emphasizes applied learning, analytical reasoning, and multi-layered problem solving, structured as tasks with **incremental complexity**.

---

## Key Features

- **Task-Based Learning**: 5 tasks, progressing from basic `CASE` statements to complex views with multiple control flow layers.  
- **AI Integration**: Students interact with AI to generate queries and explanations, comparing them with their own solutions.  
- **SQL Practice**: Includes filtering, ranking, null-handling, aggregation, and persistent views.  
- **Interactive Widgets**: Toggle buttons for expected outputs, AI prompts, and query execution.  
- **Realistic Scenarios**: Simulated executive reporting with stakeholders like CEO, CFO, Marketing Director, and Head Chef.  
- **Self-Assessment**: End-of-notebook checklist and MCQ quiz to evaluate understanding.
- ...

---

## Dataset

The notebook uses the `famous_recipes_100.csv` dataset, which contains columns such as:

- `Name` — Recipe name  
- `Description` — Recipe description (may include NULLs)  
- `TotalTime` — Total preparation time in minutes  
- `PrepTime`, `CookTime` — Breakdown of preparation and cooking times  
- `RecipeCategory` — Category of recipe (Breakfast, Beverages, etc.)  
- `AggregatedRating` — Average rating of the recipe  

> The data is loaded into an **in-memory SQLite database** for all queries.

---

## Setup Instructions

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
)

```
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/DesmondMokhali/sql-controlflow-views/main?urlpath=%2Fdoc%2Ftree%2FPython_Functions.ipynb)
