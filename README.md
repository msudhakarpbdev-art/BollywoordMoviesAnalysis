🎬 Bollywood Movie Analysis Using Python & Machine Learning (2013–2015)
This project presents an exploratory data analysis (EDA) and basic machine learning workflow using a dataset of Bollywood movies released between 2013 and 2015. The goal is to uncover trends in box office performance, release strategies, social media influence, and investment returns.

📁 Dataset Description
The dataset (bollywood.csv) contains the following columns:

SlNo: Release Date
MovieName: Name of the movie
ReleaseTime: Time of release
LW – Long Weekend
FS – Festive Season
HS – Holiday Season
N – Normal
Genre: Movie genre (e.g., Romance, Thriller, Action, Comedy, etc.)
Budget: Production budget in crore INR
BoxOfficeCollection: Gross earnings in crore INR
YoutubeViews: Views on trailer
YoutubeLikes: Likes on trailer
YoutubeDislikes: Dislikes on trailer
🔍 Analysis Overview
The following tasks were performed:

✅ Total number of records and dataset metadata
📊 Movie counts by genre & the genre with highest releases
🔁 Cross-tabulation of Genre vs ReleaseTime
📅 Monthly release trends (by extracting month from ReleaseDate)
💰 High-budget movie trends by month (≥ ₹25 crore)
📈 Top 10 movies with highest ROI
[ ROI = \frac{BoxOfficeCollection - Budget}{Budget} ]
🎉 Average ROI across release times (FS, LW, HS, N)
🧩 Budget distribution using histogram and KDE plot
🤔 ROI comparison: Comedy vs Drama
📉 Correlation between Box Office Collection and YouTube Likes
📦 Boxplots: YouTube Likes across genres
🔗 Correlation analysis between Budget, BoxOfficeCollection, YoutubeViews, YoutubeLikes, YoutubeDislikes using heatmap and pair plot
📊 Visualizations Used
Histogram & KDE Plot (Budget)
Boxplots (Genre vs YouTube Likes)
Heatmaps & Pair Plots (Correlation)
Scatter plots (BoxOffice vs Likes)
Count plots, bar charts, and more
🚀 How to Run
Clone the repository:
git clone https://github.com/your-username/bollywood-eda.git
cd bollywood-eda

Install dependencies:
pip install pandas matplotlib seaborn

Launch Jupyter Notebook or Google Colab
Run Bollywood Release Data Visualization.ipynb


