# Contributing to Legendary_OSINT

Thanks for your interest in contributing! 🎉  
This project is a curated knowledge base of OSINT tools and resources. To keep it consistent and useful for everyone, please follow these guidelines.

***If you are a commercial organization that wants to be added for community purposes, please contact me first.***

---

## 📝 Style Rules

- **One-line descriptions**: Each link must have a short, neutral description (max. 1 sentence).
- **Emoji usage**:  
  - Emoji are **only used** in top-level `##` headers (e.g., `## ✈️ Aviation Movements & Flight Tracking`).  
  - **No emoji** in `###` subheadings or in bullet points.  
- **Formatting**:  
  - Links use Markdown format: `[Name](https://example.com) — Description`  
  - Use `###` for subcategories, without emoji.  
- **Language**: English, concise, and neutral. No marketing or promotional language.
- **Deduplication**: Always check if the resource already exists in another section before adding.  
- **Placement**: Add tools to the correct `docs/*.md` file (not the root README). Each topic has its own file.  

---

## 📂 Repository Structure

- All OSINT categories live in `docs/` (e.g., `docs/aviation.md`, `docs/darkweb-leaks.md`).  
- The root `README.md` is an index only — **do not add content there directly**.  
- Each `docs/*.md` file starts with:
  ```markdown
  ## ✈️ Example Title

  [← Back to Index](../README.md)

🔍 Contribution Workflow

- Fork the repository and create a new branch.
- Add your changes in the correct docs/*.md file.
- Ensure your links are working, unique, and placed in the correct subcategory.
- Run a spell-check and keep descriptions concise.
- Submit a pull request with a short explanation of the resource(s) you added.

❌ What NOT to add

- Broken links or sites requiring paid access without clear free features.
- General news/blog posts (unless they are structured OSINT guides).
- Tools unrelated to OSINT, CTI, or investigation workflows.
- Duplicates of already listed resources.

