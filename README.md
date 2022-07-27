# data12022
import pandas as pd
import numpy as np
data=pd.read_csv(r"C:\Users\Asus\Documents\PythonData1200\Data Analytics Tool Analytics\youtube_dataset.csv", encoding='cp1252')
data.head()
data.groupby('channeltype')['channeltype'].count()
