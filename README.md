# Collection of geospatial data science projects


## Change detection in the amazon forest

This project utilizes Sentinel-2 satellite imagery to detect deforestation in the Amazon rainforest by analyzing changes in vegetation between 2017 and 2023.

### Description

This project includes two main Python notebooks:

1. **sentinel2_download.ipynb**: Downloads Sentinel-2 satellite images of a specified region within the Amazon rainforest and saves them to a tif file.
   
2. **change_detection.ipynb**: Analyzes the changes in NDVI over time to detect areas where deforestation might have occurred. It outputs visualizations of these changes.

### Installation

To set up the environment for this project, you need to install the required Python libraries. You can install them using the following command:

```bash
pip install -r requirements.txt
```

### Outputs

The satellite images over time:

![alt tag](https://github.com/ale93111/geospatial-projects/blob/main/changedetection_amazonforest/assets/images.gif)

The change maps over time:

![alt tag](https://github.com/ale93111/geospatial-projects/blob/main/changedetection_amazonforest/assets/changes.gif)

### License

This project is licensed under the MIT License - see the LICENSE file for details.

### Acknowledgements

This project uses data from the Sentinel-2 satellite mission provided by the European Space Agency (ESA).