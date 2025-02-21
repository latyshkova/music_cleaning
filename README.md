# Music Cleaning Project

## Overview

The goal of this project is to clean audio files (voice recordings) from noise (conversations, clinking cups, humming). The data consists of noisy audio files and clean audio files. The idea is to split the audio into music, vocals, and noise, clean all components from noise, and then combine music and vocals.

## Getting Started

This project uses `uv` as the package manager. Currently, the code is located in the `data_creation_test.ipynb` file.

### Prerequisites

Make sure you have `uv` installed. For detailed installation instructions, refer to the [uv installation guide](https://docs.astral.sh/uv/getting-started/installation/).

### Installation

  ```sh
  git clone https://github.com/yourusername/music_cleaning.git
  cd music_cleaning
  ```

### Running the Project

Open the Jupyter notebook:
```sh
  uv run --with jupyter jupyter lab
  ```

Or run notebook in vs code, see [doc](https://docs.astral.sh/uv/guides/integration/jupyter/)

## Contributing

Feel free to submit issues or pull requests if you have any improvements or bug fixes.

## License

This project is licensed under the MIT License.
