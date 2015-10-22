# Puzzle Solver Presentation

### Standalone Setup
> Normally will install as a submodule in Puzzle-Solver repository.

1. Install [Node.js](http://nodejs.org/)

2. Install [Grunt](http://gruntjs.com/getting-started#installing-the-cli)

4. Clone the presentation repository
   ```sh
   $ git clone https://github.com/ThoseGrapefruits/Puzzle-Solver-Presentation.git
   ```

5. Navigate to the presentation folder
   ```sh
   $ cd Puzzle-Solver-Presentation
   ```

6. Install dependencies
   ```sh
   $ npm install
   ```

7. Install MathJax via Git Submodule
   ```sh
   $ git pull --recurse-submodules && git module update
   ```

8. Serve the presentation and monitor source files for changes
   ```sh
   $ grunt serve
   ```

9. Open <http://localhost:8000> to view your presentation

   You can change the port by using `grunt serve --port 8001`.


## License
###reveal.js
- MIT licensed
- reveal.js copyright (C) 2015 Hakim El Hattab, http://hakim.se
