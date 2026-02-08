- Daniel
  - done
    - cleaning of charging session dataset
      (formatting of time data, handle missing userID values, handled duplicated sessionID, corrected handle missing / invalid values, adding of needed features, outlier analysis, weather data cleaning)
    - KPIs
      (choosed all 3 KPIs and implemented them with in-depth description of them)
    - Site Detection
      (created more visualizations: total energy per site, avg session duration per site, number of session per day of the week, number of sessions per site and gave an argument for which site is private based on these vuisualizations and the work of Linus)
    - proposed alternative clustering with more cluster and (new created) features
    - started with prediction (polynomal regression with ridge & lasso regularization)
  - in progress
    - feature selection for prediction
    - visualize decision tree
    - train NN
    - thinking about Covid impact
  - planned
    - support of the report
    - finish prediction
    - try to find better clustering

- Linus
  - done
    - cleaning of charging session dataset
      (formatting, handle missing / invalid values, handle duplicates)
    - implemented initial clustering
      (inlcuded creating user level dataset and hyperparameter tuning)
    - implemented several cluster visualization to evaluate clusters
    - implemented heatmaps of charging sessions by hour and day of week
      for site detection and argued why based on heatmaps site 1 is private
    - build decision tree for prediction including tuning of hyperparameters
    - added visualization to help with feature selection for prediction
    - added before_covid feature to handle covid impact
    - build alternative prediction model which was dropped due to complexity
    - wrote report on site detection
    - created project strucure

- Robin
  - done
    - created instruction: how to run
  - to be reviewed by the team
    - implemented a multi dimensional clustering
  - in progress
    - write the final report
    - interprete user groups by clustering
  - planned
    - evaluate further clustering features
    - refine prediction target to support business case

- Nils
  - done
    - handled and cleaned user inputs
    - added additional visualization to the descriptives part
    - evaluated business case for the prediction
    - corrected typos and formulations in markdowns and plots
  - in progress
    - write the final report
  - planned
    - refine prediction target to support business case and assist with implementation
    - refactor plots, graphs and markdowns to ensure notebook coherence
