Obsidian recognizes the following file formats right now:

1. Markdown files: `md`;
2. Image files: `png`, `jpg`, `jpeg`;
3. Audio files: `mp3`, `webm`, `wav`, `m4a`, `ogg`, `3gp`, `flac`;
4. PDF files: `pdf`.

Everything except for PDFs can be [[Embed files|embedded]].

---


### HTML Saniization (for Developers)

Obsidian sanitizes html for security reasons. Because it runs locally, scripting vulnerabilities are a more serious problem than they would be in a web applications. Acordingly, we are probably a bit more strict than you may be used to, and you may run into issues if you try to do things like embedding `<script>` tags in a note. However, the vast majority of people will never encounter issues with this. 

