# Projection-Space-Exploration
Conway's Game of Life is sequential, here high-dimensional states are projected into the two-dimensional space, and connected, furthermore, meta-data is added to create 2-D visualizations.

### Projection Figures
#### t-SNE
![t-SNE](https://github.com/matgege/Projection-Space-Exploration/blob/creation/projection_figures/t-SNE.png)
#### UMAP
![UMAP](https://github.com/matgege/Projection-Space-Exploration/blob/creation/projection_figures/UMAP.png)
#### PCA
![PCA](https://github.com/matgege/Projection-Space-Exploration/blob/creation/projection_figures/PCA.png)

### Data Description
52 random games are created on a 30 by 30 grid, and then they evolve over 300 steps. (300 generations)

[See details in the dataset description](https://github.com/matgege/Projection-Space-Exploration/blob/creation/Dataset%20description.pdf)

The game can never stop evolving as in the picture below.

![Game_0](/game_gifs/game_0.gif)

It could also result in a still life, after some steps.

![Game_22](/game_gifs/game_22.gif)

However, it could also die out.

![Game_51](/game_gifs/game_51.gif)

### Rules of the Game
- **Any live cell with fewer than two live neighbours dies.**
- **Any live cell with two or three live neighbours lives on to the next generation.**
- **Any live cell with more than three live neighbours dies.**
- **Any dead cell with exactly three live neighbours becomes a live cell.**

Details: [Conway's Game of Life - Wikipedia](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life)
