How-To:

Prerequirements:

1. Create personal Github Page: https://pages.github.com/

2. Install command line tool of JSONResume:

  npm install -g resume-cli
  
3. Install arbitrary theme:

  npm install -g jsonresume-theme-<theme_name>
  
4. Create JSON file: resume.json

5. Fill JSON according to your needs (see https://jsonresume.org/schema/).
  
Export resume using command line tool:

  resume export -t <theme_name> index.html
