<h1 align="center"> Truth Social Conspiracy </h1>
As a result of the restrictions imposed by Twitter following the January 6 United States Capitol attack, including the banning of former American President Donald Trump's account, Trump Media & Technology Group (TMTG) created a new social network, called Truth Social, which defines itself as “social media platform that encourages an open, free, and honest global conversation without discriminating on the basis of political ideology”. The precepts of total freedom of expression and criticism of censorship make this new platform an conducive environment to sharing conspiracy theories, especially aimed at right wing and pro-Trump groups, such as QAnon, which makes it a promising object of study to understand how the propagation network of these conspiracies works

Truth Social data were provided by the [Truth Social Dataset](https://arxiv.org/abs/2303.11240) and can be downloaded [HERE](https://zenodo.org/record/7531625#:~:text=A%20Truth%20Social%20data%20set%20containing%20a%20network,845%2C060%20Truth%20%28Truth%20Social%E2%80%99s%20term%20for%20post%29%20entries.).


## Notebooks

### Database Setup

The [database](https://github.com/jacksonns/Truth-Social-Conspiracy/blob/main/database.ipynb) notebook constains the SQL commands to create and populate MySQL tables with the data.

### Exploratory Analysis

The [eda](https://github.com/jacksonns/Truth-Social-Conspiracy/blob/main/eda.ipynb) notebook contains initial exploratory analysis of Truth Social content and users, such as frequent words and emojis on most engaged posts using some Natural Language Processing (NLP) techniques, visualization of most engaged users and analysis of posts frequency over time.

### Conspiracy Analysis

The [conspiracy](https://github.com/jacksonns/Truth-Social-Conspiracy/blob/main/conspiracy.ipynb) notebook analyzes the conspiracy related posts using key terms (such as "flat earth" or "qanon"), external links (from Rumble, OANN, telegram, etc) and hashtags, such as #MAGA, #WWG1WGA, #thegreatawakening, #electionfraud.
