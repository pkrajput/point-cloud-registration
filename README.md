# point-cloud-registration
Point cloud registration and classification for scene construction

### ICP speedup experiments
run ICP notebook inside isp folder to get the plot for timing

run ICP_Parallel inside isp folder to see our attempt to use cupy

### CNN classifier speedup experiments
run the CNN_classification_main notebook inside cnn_mpi_speedup_experiments with scripts model.py and dist_train.py to get plot for speedup

### experimental setup and dataset
We used MNIST dataset and created plot for a single epoch vs number of workers to show speedup, the aim of the model is not to aim for accuracy. It's like a proof of concept to me implemented in our point cloud pipeline later.
