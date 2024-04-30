# Network Intrusion Detection for IoT Systems

This is an illustrative (toy) example on applying machine learning for network intrusion detection systems (NIDS).

The critical thinking for each step is detailed in the related book chapter.

## Setting up the environment
```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

All the analysis is presented in the Jupyter Notebook [IoT NIDS.ipynb](IoT%20NIDS.ipynb).

You can make changes opening it with the Jupyter Lab:

```bash
python -m ipykernel install --user --name=venv
jupyter lab
```

## Dataset

The dataset in use is the [TON_IoT](https://research.unsw.edu.au/projects/toniot-datasets), specifically the `Train_Test_Network_dataset`. A copy of the dataset is available in the folder `dataset`.
