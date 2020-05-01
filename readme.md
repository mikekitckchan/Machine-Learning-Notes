# Content
- [Basic Machine Learning](#basicml)
    - [Basic Data Exploration](#dataexploration)


<a name ="basicml"></a>
# Basic Machine Learning


<a name="dataexploration"></a>
### Basic Data Exploration

To extract data and show it in a table, an example of code is as per below:

```python
import panda as pd

# save filepath to variable for easier access
file_path = '../../data.csv'
# read the data and store data in DataFrame titled data
data = pd.read_csv(file_path) 
# print a summary of the data in data
data.describe()

```
