# Machine Learning from Human Preferences
### Sang Truong and Sanmi Koyejo

This book is available online at: ai.stanford.edu/~sttruong/mlhp

## How to build the book
1. Install Quarto:
  -  MacOS and Windows: https://quarto.org/docs/get-started/
  -  If you are using MacOS and having HomeBrew: `brew install quarto`
2. Clone the repo:
  ```bash
  git clone https://github.com/sangttruong/mlhp
  ```
3. Go to the repo:
  ```bash
  cd mlhp
  ```
4.[One-time action]: Install required plugins.
  - Open `R` shell:
  ```bash
  R
  ```
  - Restore dependencies:
  ```R
  renv::restore()
  ```
5. Preview the book:
  - If you only want to preview the book (prior to publish it): 
  ```bash
  quarto preview
  ```
  - Using your browser to go to http://localhost:4200/ to see the book preview
6. Publish the book:
 - After you complete all edits and want to publish the book:
 ```bash
 quarto render --to html
 ```
 - The build website will be stored in folder `_book`.

Note that this book is licensed [CC-BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/).
