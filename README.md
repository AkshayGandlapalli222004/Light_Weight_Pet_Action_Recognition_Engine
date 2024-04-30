# Light_Weight_Pet_Action_Recognition_Engine
A collection of tools for the discrete classification of animal behaviors using low-dimensional representations of videos (such as skeletons provided by tracking algorithms). Our approach combines strong supervision, weak supervision, and self-supervision to improve model performance. 
This repo currently supports fitting the following types of base models on behavioral time series data:

Dense MLP network with initial 1D convolutional layer
RNNs - both LSTMs and GRUs
Temporal Convolutional Networks (TCNs)
See the documentation to get started!
@inproceedings{whiteway2021semi,
  title={Semi-supervised sequence modeling for improved behavioral segmentation},
  author={Whiteway, Matthew R and Schaffer, Evan S and Wu, Anqi and Buchanan, E Kelly and Onder, Omer F and Mishra, Neeli and Paninski, Liam},
  journal={bioRxiv},
  year={2021},
  publisher={Cold Spring Harbor Laboratory}
}
