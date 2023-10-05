# Digital Turbine's Auction Bid Price Prediction - Kaggle Competition

## Description

Welcome to the Digital Turbine's Auction Bid Price Prediction Kaggle competition repository. Digital Turbine is a renowned growth & monetization platform powered by a code installed on devices by global carriers and OEMs.

### About Digital Turbine's Ad Exchange

Digital Turbine introduces an Ad Exchange that connects publishers and advertisers. Through this platform, publishers can enhance their businesses and monetize their applications. Concurrently, advertisers can reach more users to install their apps. The Ad Exchange functions by linking Demand Side Platforms (DSPs) and Supply Side Platforms (SSPs) through Real Time Bidding.

### How the Auction Works

1. An ad request is initiated from a user's device to the mediation platform.
2. This platform activates an external auction and directs a bid request to DT Exchange.
3. DT Exchange, after receiving the bid request, starts an internal auction and dispatches bid request(s) to its DSPs.
4. DT Exchange receives bid response(s) and picks the winning bid (1st price auction).
5. It then bids on the mediation auction (external auction).
6. Mediation sends a "Win / Loss" auction resolution event to its participants with the winning bid (the competition target).
7. Eventually, the user's device receives an ad response which the user can interact with.

### The Challenge

As one of the global leading exchanges, Digital Turbine operates on a massive scale, managing over 100 billion requests daily from hundreds of millions of devices. Among the numerous challenges of such a large-scale Ad Exchange, predicting the pricing is paramount. To stay competitive, it's essential to anticipate what other exchanges might bid for a request and, more importantly, predict the winning bid for that request.

**Your task**: Given certain auction attributes and a signal indicating if Digital Turbine won that auction or not, your objective is to determine the bid price that would have secured the auction (i.e., the "winBid"). This is fundamentally a regression problem where the aim is to predict the winning bid price in $ CPM.

For a comprehensive description of the dataset, please refer to the "Data" section of the Kaggle competition.

### Recruitment Opportunity with Digital Turbine

This competition also serves as a recruitment platform for Digital Turbine's Data Science roles in Warsaw and Petach Tikva. Participants showcasing high-quality contributions, such as high leaderboard scores, innovative notebooks, or insightful forum discussions, have the opportunity to secure an interview, giving them an edge in the recruitment process.

[More about the position and how to apply.](LINK_TO_POSITION)

## How to Use this Repository

1. Clone the repository
2. Navigate to the project directory.
3. Add the dataset from Kaggle to the data folder.
4. Run the scripts/notebooks to train and evaluate the models.

## Contributing

Contributions are welcome! Please read the contributing guidelines before making any changes.
