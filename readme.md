This repo has a simple GitHub action that watches the master branch. On every change to the Master branch, GitHub Actions will parse the diagrams in the `diagrams` folder, create PNG files for each diagram, and commit them in the output folder.

While it is an anti-pattern to store build artifacts in git, I took that approach this time for the sake of simplicity. 
