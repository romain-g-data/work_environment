# MkDocs

- To setup a new MkDocs projec: mkdir a folder, go to directory and do 
       mkdocs new . 

This command creates mkdocs.yml which holds your MkDocs configuration, and docs/index.md which is the Markdown file that is the entry point for your documentation.

- Build documentation with
  	mkdocs serve

This command builds your Markdown files into HTML and starts a development server to browse your documentation.

- Open up http://127.0.0.1:8000/ in your web browser to see your documentation. 
- In a separate window terminal you will be able to create new .md files and fill up index.md in the project's directory and your docs will automatically rebuild and update


*Source*:

*https://docs.readthedocs.io/en/stable/intro/getting-started-with-mkdocs.html*