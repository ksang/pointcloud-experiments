# pointcloud-experiments
Playground for point cloud 3D data, to have a better understanding of it

### Prerequisites

- [direnv](https://direnv.net/), can be skipped by running commands in [.envrc](.envrc) manually.

- [pyenv](https://github.com/pyenv/pyenv) with [pyenv-virtualenv](https://github.com/pyenv/pyenv-virtualenv) plugin. To install python 3.9.9 and create a virtual env based on it:
    ```
    pyenv install 3.9.9
    pyenv virtualenv 3.9.9 `basename "$PWD"`
    ```

- Install dependencies
    ```
    pip install -r requirements.txt
    ```

### Datasets

- [nuScenes](https://www.nuscenes.org/nuscenes#overview)