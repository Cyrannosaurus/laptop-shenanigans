# laptop-shenanigans

## m2_predict
Predicting the release date of the next wave of Apple products because I really like the price to performance of the M1 chip, its surprisingly good for Apple, but would like more than 16gb of dedowated wam. Also, V2s are normally leaps and bounds better than V1 due to all the optimizations that couldn't make it in the first iteration. Anhow, here's the predictions:

| Product  | Predicted Release Date |
| ------------- | ------------- |
| MacBook Air  | 2021-09-27  |
| MacBook Pro  | 2021-06-24  |
| Mac Mini  | 2022-05-01  |
| Mac Pro  | 2021-07-02  |

### TODO:
- Using the historical data I scraped of all other Apple product releases to inform the model of trends. Still thinking of the methodology.
- Match the cyclic nature of releases, e.g. WWDC

## match_prediction
Predicting LoL game outcomes (binary win lose) with just the info in the spectator API (with supervision by the match API). Hardly even in a state that I would call a WIP.

### TODO:
- Parse a single match's data from spectator api
- Parse champion mastery data for players in match using player id from above and mastery api
- Parse winning team from match api
- Pick / create a PyTorch model to use
  - How could good runes / team comps / counter picks be gleaned from the model?
  
 ### Stretch:
 - Use the match api with win masked as training data to see effect of first baron / dragon etc.
