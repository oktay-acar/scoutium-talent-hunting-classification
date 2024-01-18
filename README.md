# Talent Hunting Classification with Machine Learning using [SCOUTIUM](https://scoutium.com/)'s Dataset

**Business Problem**

Predicting which class *(average, highlighted)* players are based on the points given to the characteristics of the football players watched by the Scouts.

**Dataset Story**

The dataset consists of information containing the characteristics and scores of the football players evaluated by the scouts according to the characteristics of the football players observed in the matches from **Scoutium**.

**Variables**

**scoutium_attributes.csv**

- **task_response_id:** The set of a scout's evaluations of all players on a team's roster in a match
- **match_id:**  The id of the relevant match
- **evaluator_id:**  The id of the evaluator *(scout)*
- **player_id:**  The id of the relevant player
- **position_id:**  The id of the position played by the relevant player in that match
      
  **1.** Goalkeeper
  
  **2.** Stopper
  
  **3.** Right-back
  
  **4.** Left-back
  
  **5.** Defensive midfielder
  
  **6.** Central midfielder
  
  **7.** Right wing
  
  **8.** Left wing
  
  **9.** Attacking midfielder
  
  **10.** Striker
- **analysis_id:** Set of attribute evaluations of a scout for a player in a match
- **attribute_id:** The id of each attribute that the players were evaluated for
- **attribute_value:** The value *(points)* a scout gives to a player's attribute

**scoutium_potential_labels.csv**
- **task_response_id:** The set of a scout's evaluations of all players on a team's roster in a match
- **match_id:** The id of the corresponding match
- **evaluator_id:** The id of the evaluator *(scout)*
- **player_id:** The id of the respective player
- **potential_label:** A label that indicates a scout's final decision regarding a player in a match *(target variable)*

---

## Requirements
~~~python
catboost==1.2
lightgbm==3.3.5
matplotlib==3.7.1
numpy==1.24.3
pandas==1.5.1
seaborn==0.12.1
sklearn==1.3.1
tabulate==0.9.0
xgboost==1.7.5
~~~

---

## Author
[Oktay Acar](https://github.com/oktay-acar)