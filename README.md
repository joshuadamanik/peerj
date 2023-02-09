# Source Code for Paper Distributed data aggregation in clustered network of multi-agent systems
Author: Joshua Julian Damanik<br>
Email: joshuajdmk@gmail.com

## Abstract
This paper presents a distributed data aggregation algorithm for clustered network of multi-agent systems. The algorithm is based on the concept of distributed data aggregation.

## How to run
1. Install python 3.10 or above
    - `sudo apt install python3.10`
2. Install pip
    - `sudo apt install python3-pip`
3. Install requirements
    - `pip install -r requirements.txt`
4. Run the program
    - `python3 data_aggregation.py`

## Parameters

To change the parameters, add flags to the command line arguments.
You can check `python3 data_aggregation.py --help` for the list of flags.

- `--n_samples N_SAMPLES`: Number of samples (default: 100)
- `--n_features N_FEATURES`: Number of features (default: 2)
- `--n_clusters N_CLUSTERS`: Number of clusters (default: 4)
- `--max_iter MAX_ITER`: Maximum number of iterations (default: 1000)
- `--n_neighbors N_NEIGHBORS`: Number of neighbors (default: 5)
- `--eps EPS`: Epsilon (default: 1.0)
- `--seed SEED`: Random seed (default: 20)
- `--fig_size_x FIG_SIZE_X`: Figure size x (default: 6)
- `--fig_size_y FIG_SIZE_Y`: Figure size y (default: 4)
- `--save_path SAVE_PATH`: Figure save path (default: result)
- `--save_name SAVE_NAME`: Figure save name (default: None)

## Citation
If you use this code for your research, please cite our paper.

```bibtex
@misc{damanik2021distributed,
      title={Distributed data aggregation in clustered network of multi-agent systems}, 
      author={Joshua Julian Damanik, Han-Lim Choi},
      year={2022},
      journal={PeerJ Computer Science}
}
```