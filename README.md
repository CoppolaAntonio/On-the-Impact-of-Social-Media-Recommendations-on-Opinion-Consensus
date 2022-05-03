# On-the-Impact-of-Social-Media-Recommendations-on-Opinion-Consensus

This repository collects all the experimental results obtained for the paper: https://arxiv.org/abs/2204.03299. 

In the Sync_Update directory, we collected all the results related to the section "General Networks" of the paper. The names of the folders are equal to the name of the Figures in the chapter described above, e.g., in Figure 2 we collected all the experimental results obtained in the setting described for Figure 2 in the paper.
The name of each picture identifies the network model used for the experiment:
i) stochastic_block_model: Stochastic Two-Block Model Graph
ii) random_graph: Random Graph
iii) watts_strogatz_graph: Watts-Strogatz Model
iv) hyperbolic_random_graph: Hyperbolic Random Graph Model
v) ego_facebook: ego-Facebook (SNAP)
vi) lastfm_asia: feather-lastfm-social (SNAP)

In the Async_Update directory, we collected all the results related to the section "Impact on Consensus" of the paper. In this case, the names of the folders are not equal to the name of the Figures in the chapter "Impact on Consensus", but they are equal to the name of the folders in the Sync_Update directory. Specifically, in the folder Aysnc_Update/Figure 2 we collected the results obtained in the same setting of Sync_Update/Figure 2 but with asynchronous dynamics. We did that for making easier the comparison between the results obtained with the two different dynamics, asynchronous and synchronous.
