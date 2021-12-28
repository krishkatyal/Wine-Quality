
# Wine Quality Predicition

According to experts, the wine is differentiated according to its smell, flavor, and color, but we are not a wine expert to say that wine is good or bad. What will we do then?
We will use ML to predict it's quality

## Installation

Libraries to be installed

```bash
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
from sklearn.ensemble import RandomForestClassifier
from sklearn.svm import SVC
from sklearn.linear_model import SGDClassifier
from sklearn.metrics import confusion_matrix, classification_report
from sklearn.preprocessing import StandardScaler, LabelEncoder
from sklearn.model_selection import train_test_split, GridSearchCV, cross_val_score
from sklearn.neighbors import KNeighborsClassifier
from sklearn.metrics import accuracy_score
```

## Description of Dataset:


**volatile acidity** :   Volatile acidity is the gaseous acids present in wine.

**fixed acidity** :   Primary fixed acids found in wine are tartaric, succinic, citric, and malic

**residual sugar** :   Amount of sugar left after fermentation.

**citric acid** :    It is weak organic acid, found in citrus fruits naturally.

**chlorides** :   Amount of salt present in wine.

**free sulfur dioxide** :   So2 is used for prevention of wine by oxidation and microbial spoilage.

**total sulfur dioxide** 

**pH** :   In wine pH is used for checking acidity

**density** 

**sulphates** :    Added sulfites preserve freshness and protect wine from oxidation, and bacteria.

**alcohol** :   Percent of alcohol present in wine.

