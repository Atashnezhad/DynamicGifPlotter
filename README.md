
[![Downloads](https://static.pepy.tech/badge/GifPlotter)](https://pepy.tech/project/GifPlotter)
# FlexiPlotter

`FlexiPlotter` is a flexible data visualization library that allows you to create various types of plots (line, scatter, bar) from a pandas DataFrame based on a structured payload. It can handle multiple subplots arranged in a custom layout and can even generate animated GIFs from the plot data over time.

## Features

- Create flexible layouts of subplots for visualizing different types of charts.
- Supports line, scatter, and bar plots.
- Automatically configures axis labels, titles, and colors from payload data.
- Generate animated GIFs showing data evolution over time.
- Save the resulting figure or GIF to disk.

## Installation

### Prerequisites

Make sure you have the following installed:

- Python 3.x
- Pandas (`pip install pandas`)
- NumPy (`pip install numpy`)
- Matplotlib (`pip install matplotlib`)
- ImageIO (`pip install imageio`)

### Clone the repository

```bash
git clone https://github.com/yourusername/flexi-plotter.git
cd flexi-plotter
