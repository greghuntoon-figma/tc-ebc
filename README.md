# TC-EBC Prompt Framework

**Created by Greg Huntoon**  
A lightweight, reliable structure for writing high-clarity prompts for LLM-driven design tools (like **Figma Make**).  
TC-EBC turns vague instructions into predictable outputs by breaking intent into five simple parts:

**Task • Context • Elements • Behavior • Constraints**

---

## Why TC-EBC exists
LLMs respond best to prompts that separate *what* you want from *where it lives* and *how it should act*.  
TC-EBC provides a repeatable structure that:

- Reduces ambiguity  
- Produces more accurate builds  
- Keeps prompts short and scannable  
- Works for ideas, screenshots, revisions, or multi-step flows  

This repo serves as the canonical reference for TC-EBC.

---

## The TC-EBC Format

Task: [One line describing what the prototype or screen should do]
Context: [Where this fits in the product or flow]
Elements: [Literal UI components present — keep this a short list]
Behavior: [How users interact with those components]
Constraints: [Device, layout rules, visual constraints — concise]


### Notes  
- Each line should be as short as possible.  
- Include only what the model *must* know.  
- TC-EBC is not verbose documentation — it is a prompt skeleton.

---

## Example: Idea → TC-EBC Prompt


Task: Create a mobile onboarding screen with email signup
Context: First step of account creation for a wellness app
Elements: Logo, headline, email input, “Continue” button, privacy note
Behavior: Button stays disabled until email is valid; keyboard pushes content up
Constraints: iOS mobile layout, 8pt grid, 16px corner radius


---

## Example: Screenshot → TC-EBC Prompt


Task: Recreate this dashboard layout
Context: Post-login home screen for a productivity app
Elements: Top bar, search field, 3 statistic cards, task list, add-task button
Behavior: Scrolling reveals full list; tapping a card expands details
Constraints: Desktop layout, 12-column grid, cards use subtle elevation


---

## When to Use TC-EBC
Use TC-EBC whenever you need the model to understand:

- *What* you want built  
- *Where* it belongs  
- *What UI pieces exist*  
- *How interactions work*  
- *What constraints must not change*

TC-EBC is ideal for:
- New builds (idea → screen)  
- Screenshot recreations  
- Structured instructions for Figma Make  
- Communicating expectations across design & engineering  

---

## Tips for Writing Strong TC-EBC Prompts

- Keep each line **single-thought and essential**  
- Avoid long narratives — the model only needs what affects output  
- Don’t over-specify visuals unless they are **product constraints**  
- Let the model fill in defaults unless they would break the design  
- For revisions, pair TC-EBC with a **Target / Change / Maintain** block  

---

## Attribution

TC-EBC is an original prompt-structuring method created by **[Your Name]**.  
If you use TC-EBC in your work, tools, articles, workshops, or repos, please credit the creator.

---

## License

You may include one of the following (choose based on your intent):

- **MIT License (Attribution encouraged)**
- **CC BY 4.0 (Attribution required)**
- **Custom license (Use allowed, ownership cannot be claimed)**

---

Want me to revise this to match your tone, add branding, or generate repo scaffolding?  
Just say **“Refine the README”** or **“Add repo structure.”**
