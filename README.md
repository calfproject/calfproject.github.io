This website is built via the [Forester](https://www.forester-notes.org/index/index.xml) software. 

To build the website locally, please follow these steps:
### Installation Instructions
1. Make sure you have OCaml 5.
2. Install Forester via OPAM:
   ```
   opam install forester
   ```
3. Make sure you have tex live installed on your system.

### Build Locally
1. Run the following command in the root directory of the repository:
   ```
   opam exec -- forester build forest.toml
   ```
2. Run a local server to preview the website:
   ```
   python3 -m http.server 1313 -d output
   ```
3. Open your web browser and navigate to `http://localhost:1313` to view the website.


### Edit
All content are in `trees` directory.