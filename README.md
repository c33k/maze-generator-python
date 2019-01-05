# maze-generator-python
Python implementation algorithms for generating mazes.

#Requirements
Python 3.7.1

##Installing Dependencies

```
pip install -r requirements.txt
```

For generating video with the "--video" option:

On MACOS: Install[mplayer](http://www.mplayerhq.hu) with [homebrew](https://brew.sh/) and than use mencoder to create videos based on the generated frames.

```
brew install mplayer
```

# DFS - Depth First Search

Generate maze using Depth First Search algorithm, as per [Wikipedia](https://en.wikipedia.org/wiki/Maze_generation_algorithm).

![dfs/maze.py example](/dfs/maze.png)

To run the generator, enter in the dfs directory...
```
cd dfs
```

... and then run maze.py with parameters WIDTH, HEIGHT and (optional) "--video" for generate video output.
For example, to generate a .png file of a maze of dimensions 400x400, run:

```
python maze.py 400 400
```