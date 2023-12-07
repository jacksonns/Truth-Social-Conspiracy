<h1 align="center"> Truth Social Conspiracy </h1>
As a result of the restrictions imposed by Twitter following the January 6 United States Capitol attack, including the banning of former American President Donald Trump's account, Trump Media & Technology Group (TMTG) created a new social network, called Truth Social, which defines itself as “social media platform that encourages an open, free, and honest global conversation without discriminating on the basis of political ideology”. The precepts of total freedom of expression and criticism of censorship make this new platform an conducive environment to sharing conspiracy theories, especially aimed at right wing and pro-Trump groups, such as QAnon, which makes it a promising object of study to understand how the propagation network of these conspiracies works

Truth Social data were provided by the [Truth Social Dataset](https://arxiv.org/abs/2303.11240) and can be downloaded [HERE](https://zenodo.org/record/7531625#:~:text=A%20Truth%20Social%20data%20set%20containing%20a%20network,845%2C060%20Truth%20%28Truth%20Social%E2%80%99s%20term%20for%20post%29%20entries.).


## Notebooks

### Database Setup

The [database](https://github.com/jacksonns/Truth-Social-Conspiracy/blob/main/database.ipynb) notebook constains the SQL commands to create and populate MySQL tables with the data.

### Exploratory Analysis

The [eda](https://github.com/jacksonns/Truth-Social-Conspiracy/blob/main/eda.ipynb) notebook contains initial exploratory analysis of Truth Social content and users, such as frequent words and emojis on most engaged posts using some Natural Language Processing (NLP) techniques, visualization of most engaged users and analysis of posts frequency over time.


### Network Structure Analysis

The [network](https://github.com/jacksonns/Truth-Social-Conspiracy/blob/main/network.ipynb) notebook contains the structural analysis of the Truth Social's graph, modeled by the reposts relationships. The analysis involves node degree distribution, strongly connected components, distance distribution, clustering coefficients, graph resilience and assortativity.


### Conspiracy Analysis

The [conspiracy](https://github.com/jacksonns/Truth-Social-Conspiracy/blob/main/conspiracy.ipynb) notebook analyzes the conspiracy related posts and its connections. The analysed conspiracies involves QAnon, Election Fraud and Climate Change. 


## Results

This work presented some new information regarding the dynamics of conspiracy theories on the Truth Social platform, a pro-Trump social network that has been relatively unexplored in the literature. Through content analysis, it was possible to observe that conspiratorial groups rely on the dissemination of misinformation and fake news, extending their discussions to a wide variety of topics. In the analysis of external links, I observed that QAnon conspirators tend to share more links to the Telegram platform, where they create conspiratorial groups. On the other hand, those related to election fraud choose to share links to news websites known for spreading false information, such as thegatewaypundit, thefederalist, and justthenews. Furthermore, considering the analysis of the connection graph among conspiratorial users, it was noticeable that those users who believe in more than one conspiracy tend to connect more with each other, forming a hub for the dissemination of theories. It was also observed that former President Donald Trump is a central figure and of great importance for the spread of theories involving electoral fraud, as he is the most influential personality on this network.


