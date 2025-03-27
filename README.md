# LOT: LC2L Optimized Trajectories
This LC2L-Optimized-Trajectories (LOT) GitHub Repository contains the main code and data used for Van Tran's Senior Thesis "Fuel Burn Tradeoffs in Safety-Optimized Trajectories for Uncrewed Aircraft Systems." Code used to preprocess data, visualize data, or run statistical analyses are not included in this repo. 

## Install Necessary Packages

The thesis relies on the aircraft performance model OpenAP[^1] and solver OpenAP.top[^2]. For the user guide and installation instructions please visit OpenAP's [GitHub](https://github.com/junzis/openap)

## Usage
To create your own outage probability and risk cost grids, use the __cost_writer.ipynb__ Jupyter notebook. From there alter the code to meet your specific parameters.

`P_transmit = 40
`

`P_threshold = -95`

`frequency = 5.06`

`sigma = 5`

Given your outage and risk cost grids, you can then use the __main.ipynb__ Jupyter notebook to simulate all of your flights. 

## Restrictions

Unfortunately, because of data storage limitations due to large file sizes, I am unable to upload all data files into the repository. You are welcome to collect your own data but if you would like to have access the large data files, please visit this [Google Drive](https://drive.google.com/drive/folders/1uaLrCkqx-ZbLyhH9rnJE6dOF8E8GZi1J?usp=sharing). For any other questions, please email me at vantran@college.harvard.edu.

[^1]: Junzi Sun, Jacco Hoekstra, and Joost Ellerbroek. Openap: An open-source aircraft performance model for air transportation studies and simulations. Aerospace, 7(8):104, July 2020.
[^2]: Junzi Sun. Openap. top: Open flight trajectory optimization for air transport and
sustainability research. Aerospace, 9(7):383, 2022.
