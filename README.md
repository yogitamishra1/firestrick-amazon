# firestrick-amazon
from matplotlib import figure
plt.figure(figsize= (13,9))
corre=df.corr()
sns.heatmap(corre,annot=True,cmap="gist_heat",linewidths=.9)
