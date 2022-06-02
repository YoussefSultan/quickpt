
<!-- ABOUT THE PROJECT -->
## About The Project
This is a small Python Function that allows you to see the variance, percentage of missing values and unique values within a dataset.

`pip install quickpt`
```python
from quickpt.quickpt import quickpt
quickpt(df, graph=None, encode=True, width=800, height=400)
```
### More information on the project

    """
    quickpt
    ---------
    Creates a DataFrame showing the missing values, total unique values, data type, and variance of each feature.

    If the argument graph is passed, then a bar chart of the specified parameter is visualized.

    Parameters
    ----------
    graph : var, null, uniq 
        (default is None)
    
    encode : True, False
        (default is True)
    
    width : int
        (default is 800)

    height : int
        (default is 400)
    
    Description of Parameters
    -------
        - var = variance
        - null = percent of missing values in decimal form
        - uniq = sum of unique values
        - encode --> True = Uses LabelEncoder to encode categorical variables and receive summary statistics
        - encode --> False = Only shows DataFrame/Visualization of original numeric variables of input data
        - width = update graph width
        - height = update graph height

    Use
    ----
    - Used on preprocessed datasets that have only numerical features
    - If data has categorical features set encoder=True to temporarily LabelEncode categorical features
    """

![image](https://user-images.githubusercontent.com/89711840/171681821-a6a79c9e-c466-4150-bbc2-63b963d209e5.png)
<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
