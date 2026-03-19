<h2>Formula 1 Social Media Analysis</h2>

  <h3>Overview</h3>
  <p>
    This project explores how Formula 1 race performance relates to fan engagement on social media,
    with a focus on Reddit. My primary contribution was designing and implementing the Reddit data
    pipeline used to analyze fan discussions and engagement patterns.
  </p>

  <h3>My Contribution</h3>
  <ul>
    <li>Built a Reddit scraper using PRAW to collect posts from the r/formula1 subreddit</li>
    <li>Queried posts for each driver and extracted metadata including score, upvotes, comments, and timestamps</li>
    <li>Structured raw data into a clean dataset for analysis</li>
    <li>Engineered engagement metrics and prepared data for correlation analysis</li>
  </ul>

  <h3>Methodology</h3>
  <ul>
    <li>Collected top posts for each driver over defined time windows before races</li>
    <li>Aggregated engagement metrics (average score, comments, upvotes)</li>
    <li>Aligned Reddit activity with race results data</li>
    <li>Performed correlation analysis to measure relationships between engagement and performance</li>
  </ul>

  <h3>Key Insights</h3>
  <ul>
    <li>Higher Reddit engagement is negatively correlated with subsequent race performance</li>
    <li>Posts about drama, incidents, and controversy generate the most interaction</li>
    <li>Fan sentiment has only a weak relationship with actual driver success</li>
  </ul>
  <img src="https://raw.githubusercontent.com/taylor-clark6/MyWebsite/master/assets/images/banners/f1-vis.jpg">

  <h3>Tools & Technologies</h3>
  <ul>
    <li>Python (pandas)</li>
    <li>PRAW (Reddit API)</li>
    <li>VADER Sentiment Analysis</li>
    <li>Matplotlib</li>
  </ul>
  
You can view the source code and explore this project in more detail <a href="https://github.com/taylor-clark6/Formula-1-Social-Media-Analysis">here</a>!
