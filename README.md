# CTG Classification

The goal of this project is to study the cardiotocography data set found at https://archive.ics.uci.edu/ml/datasets/cardiotocography, consisting of data from roughly 2100 fetal cardiotocograms and build a model to classify the fetal heart health as either normal, suspect, or pathological. The data were classified by obstetricians, using presumably a somewhat clear set of guidelines, but the purpose of this project is to determine whether these guidelines can be learned from the data alone (so was primarily for my own exploration and understanding).

The notebook contains the following sections: Data Preparation, where the data was formatted for study; Exploratory Data Analysis and Feature Selection, where the data was studied, to determine which of the features to include in any models built and which models may be the most appropriate; Model Selection, where various models were experimented with; and Risk Score Experiments, in which I attempted building a model that would return a risk score given the feature data (in such a way that the highest scores indicated the pathological cases, mid-range indicated the suspect cases, and lowest scores indicated the normal cases).
