# CANDLE
This repository consists CANDLE: An Image Dataset for Causal ANalysis in DisentangLed rEpresentations.

# Sample images
![CANDLE grid](./sample_images/grid.png)
The code used to simulate the dataset can be found at [the candle-simulator repository](https://github.com/causal-disentanglement/candle-simulator).

# Downloading the dataset
The dataset is available at [gdrive](https://drive.google.com/drive/folders/11w267LWI8tbWhf1SR8kd-l6fP9WbJwNL).

# Factors of Variation
The dataset contains 12546 `png` images and corresponding `json`s with the ground truth information.

| Generative Values | Factor |
| --- | --- |
| Object | Cube, Sphere, Cylinder, Cone, Torus |
| Color | Red, Blue, Yellow, Purple, Orange |
| Size | Small, Medium, Large |
| Rotation | 0◦, 15◦, 30◦, 45◦, 60◦, 90◦ |
Light | Left, Middle, Right |
| Scene | Indoor, Playground, Outdoor, Bridge, City Square, Hall,Grassland, Garage, Street, Beach, Station, Tunnel, Moonlit Grass, Dusk City, Skywalk, Garden |

# Scenes
More examples of every scene included in the dataset can be found at `./sample_images/scenes/'`.

# License
This work is licensed under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).