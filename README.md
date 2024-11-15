import matplotlib.pyplot as plt
import seaborn as sns

sns.set(style="whitegrid")
df = sns.load_dataset("iris")
sns.pairplot(df, hue="species")
plt.show()
