# Shack_Labs_DS_Assignment

This repo contains two projects given by shack labs as an assignment 

Part 1: Predict the price of a house --
* Done Explorartory Analysis to understand the relationship between house features and how these
variables affect the house price.
* predicted the price of the house using :
  * GradientBoostingRegressor
  * XGBRegressor
  * RandomForestRegressor
  * BaggingRegressor
  * LinearRegression
  * SVR
  * KNeighborsRegressor
  * MLPRegressor
  * DecisionTreeRegressor
 * Model	Results : 
   * XGBRegressor	0.785174
   * GradientBoostingRegressor	0.777912
   * RandomForestRegressor	0.75888
   * BaggingRegressor	0.690698
   * LinearRegression	0.643865
   * SVR	0.592828
   * MLPRegressor	0.57107
   * KNeighborsRegressor	0.542228
   * DecisionTreeRegressor	0.53747
* Done hyperparameter tuning to improve model performence using GridSearchCV for finding the optimum hyperparameters


Part 2 : Product Matching 
* Using ML/DL techniques, matched similar products from the Flipkart dataset with the Amazon dataset. Once
similar products are matched, display the retail price from FK and AMZ side by side.
* Used Sentence Transformers for vector Representations 
  * Sentence transformers is a Python framework for cutting-edge sentence vector representations. Having the phrases in space allows us to calculate the distance between them, and by doing so, we can identify the ones that are most comparable in terms of their semantic meaning.
  * Used the "all-MiniLM-L6-v2" Sentence Transformer model for calculating semantic similarity between Amazon and Flipkart product names.
 * used tensorflow.nn.top_k for storing the index of a similar Flipkart product corresponding to each Amazon product
 * the final output file is attached 
