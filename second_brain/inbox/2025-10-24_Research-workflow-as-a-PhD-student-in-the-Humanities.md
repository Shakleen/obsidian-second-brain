--- 
created at: 2025-10-24
tags:
  - productivity
hubs:
  - "[[productivity]]"
urls:
  - https://martinezponciano.es/2021/04/05/research-workflow-as-a-phd-student-in-the-humanities/
  - https://martinezponciano.es/2021/04/05/from-references-to-fleeting-notes-zotero-and-zotero-plug-ins/
  - https://martinezponciano.es/2021/04/05/from-fleeting-notes-to-literature-notes-obsidian/
  - https://martinezponciano.es/2021/04/05/from-literature-notes-to-permanent-notes-obsidian/
---

# Research workflow as a PhD student in the Humanities

Follows [[2025-10-25_The-Zettelkasten-Method|The zettelkasten Method]] for keeping track of all information.

## [Tools used][1]
1. **Obsidian**: For note taking in markdown
2. **Zotero** and plugins: For reference management.
3. **PanDoc**: Document conversion.

## [Workflow Steps][1]
1. From references to fleeting notes: Zotero and Zotero plug-ins
2. From fleeting notes to literature notes: Obsidian
3. From literature notes to permanent notes: Obsidian
4. From permanent notes to a manuscript: Pandoc

## [Step 1: References to Fleeting Notes][2]

### Add reference in zotero 
1. Physical book: Scan barcode
2. Online resource: Zotero connector plugin 
3. PDF
  1. With meta data: Drag and drop into Zotero 
  2. Without: Lookup .bibtex on Google scholar
4. ISBN or DOI: [Add item by identifier](https://www.zotero.org/support/adding_items_to_zotero)
5. Manually fill in

### Taking fleeting notes 
1. Read PDF using PDF viewer, highlight, and add comments. In the comments,
  * **Double square brackets**: Wiki-links for Obsidian 
  * **Single square brackets**: Cite keys for PanDoc
2. Use Zotero-browser-connector plug in for web articles.

## [Step 2: From fleeting notes to literature ntoes][3]

1. Use [Zotfiles](https://github.com/argenos/zotero-mdnotes) to manage attachments and annotations.
2. Use [Obsidian](https://obsidian.md/) Zotero-integration plug-in to import zotero annotations.
3. Create a note to summarize the findings from the article or paper or book. Where the note references items from zotero annotations.

Example:
1. Template:
   ![[Pasted image 20251026140010.png]]
2. Meta data section
   ![[Pasted image 20251026140043.png]]
3. Summary section
   ![[Pasted image 20251026140057.png]]
4. Key idea section
   ![[Pasted image 20251026140133.png]]

## [Step 3: From literature notes to permanent notes][4]

1. Make sure to insert cite keys to acknowledge the source of these ideas whenever relevant.
  * A permanent note which begins with “Scholars have long argued that…” needs reference
  * A blanket statement such as “Oscar Wilde’s short fiction have been frequently anthologized” does not need references
2. Embed individual paragraphs using `![[File^]]`
3. Embed individual sections using `![[File#]]`

Example:
1. In edit mode: 
  ![[Pasted image 20251026135728.png]]
2. In preview mode:
  ![[Pasted image 20251026135747.png]]


## References 
[1]: https://martinezponciano.es/2021/04/05/research-workflow-as-a-phd-student-in-the-humanities/
[2]: https://martinezponciano.es/2021/04/05/from-references-to-fleeting-notes-zotero-and-zotero-plug-ins/
[3]: https://martinezponciano.es/2021/04/05/from-fleeting-notes-to-literature-notes-obsidian/
[4]: https://martinezponciano.es/2021/04/05/from-literature-notes-to-permanent-notes-obsidian/
