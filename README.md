# ML-Fifa-Predictions

This machine learning model predicts the overall and potential ratings of players in the game Fifa23. Based on data up to 6/07/2023
The models are trained with data from different web pages like https://www.transfermarkt.com/ , https://sofifa.com/ , https://www.footysimulator.co.uk/Rankings/Club/ , https://www.besoccer.com/

## Table of Contents
- [Instructions for the Url Input Version](#instructions-for-the-url-input-version)
- [Instructions for the Manual Version](#instructions-for-the-manual-version)

## Instructions for the Url Input Version

https://github.com/joshuafrank77/ML-Fifa-Predictions/assets/41444376/df54016d-c95c-4f86-b440-cd75fdf5b855


You can start predicting players' overall and potential ratings using the URL input version by clicking here: https://predict-fifa-overall-potential-e49a2cd8c976.herokuapp.com/voila/render/Predict_single_player.ipynb?

When you start the application, you will encounter the following menu:

![image](https://github.com/joshuafrank77/ML-Fifa-Predictions/assets/41444376/a0776c43-c306-4daa-9ef2-0643fe8bf6c0)

To predict a player's overall rating, follow these steps:

1. Select the position that best suits the player you want to predict. The available options are:

   - CAM (Center Attacking Midfielder)
   - CB (Center Back)
   - CDM (Center Defensive Midfielder)
   - CF (Center-Forward)
   - CM (Center Midfielder)
   - GK (Goalkeeper)
   - LB (Left Back)
   - LM (Left Midfielder)
   - LW (Left Winger)
   - LWB (Left Wing-Back)
   - RB (Right Back)
   - RM (Right Midfielder)
   - RW (Right Winger)
   - RWB (Right Wing-Back)
   - ST (Striker)

2. Provide additional information for the prediction. This includes the current league the player plays in, continent, nationality, and the statistics from the last season that you want to consider.

3. Enter the club ranking by visiting [this webpage](https://www.footysimulator.co.uk/Rankings/Club/), finding the player's club, and copying the ranking number. For example, if the player plays for Manchester City, the club ranking would be 144.018.

   ![image](https://github.com/joshuafrank77/ML-Fifa-Predictions/assets/41444376/0e4f94ed-80f5-43c2-968e-117fbf3c2816)

4. Provide the Transfermarkt URL for the player. Search for the player on the [Transfermarkt website](https://www.transfermarkt.com/), and copy the player's URL. For example, if you want to predict Kylian Mbappé's ratings, the URL would be [https://www.transfermarkt.com/kylian-mbappe/profil/spieler/342229](https://www.transfermarkt.com/kylian-mbappe/profil/spieler/342229).

   ![image](https://github.com/joshuafrank77/ML-Fifa-Predictions/assets/41444376/d73f24c4-e10b-4e43-91a7-5d10c48e819d)

5. Provide the BeSoccer URL for the player. Find the player on the [BeSoccer website](https://www.besoccer.com/) and copy the player's URL. For example, for Mbappé, the URL would be [https://www.besoccer.com/player/k-mbappe-lottin-234474](https://www.besoccer.com/player/k-mbappe-lottin-234474).

   ![image](https://github.com/joshuafrank77/ML-Fifa-Predictions/assets/41444376/e09fbcac-9426-41a6-aea9-e1f0729c0aec)

6. Click on the "Predict" button, and the results will be displayed on the screen.

## Instructions for the Manual Version

To utilize the manual version of the ML-Fifa-Predictions model, please follow these steps:

1. Begin by clicking on the provided link to access the manual input version: https://predict-fifa-overall-potential-e49a2cd8c976.herokuapp.com/voila/render/Predict_manual.ipynb?

2. Upon launching the application, you will be presented with the following menu:

   ![image](https://github.com/joshuafrank77/ML-Fifa-Predictions/assets/41444376/d9442996-dcb6-437d-bc16-9f8266b3e20e)

   This menu contains various fields required for making predictions. The initial set of information can be obtained from the [Transfermarkt website](https://www.transfermarkt.com/).

3. Refer to the image below to understand the different fields:

   ![image](https://github.com/joshuafrank77/ML-Fifa-Predictions/assets/41444376/6da111dc-480c-4a7d-9c5c-cb3eba6ec7f2)

   The red arrow indicates the player's age, blue represents their position, yellow denotes the league they compete in, green indicates their continent of origin, and orange represents their nationality. The player's market value is also displayed.
   
4. To fill the Club Ranking (footysimulator), you can obtain this information from the [FootySimulator website](https://www.footysimulator.co.uk/Rankings/Club/). Simply enter the club name in the search box and copy the rating, as shown in the example below:

   ![image](https://github.com/joshuafrank77/ML-Fifa-Predictions/assets/41444376/3d6c9999-6534-4ec6-9d16-c8c9cf5ede34)
   
   ![image](https://github.com/joshuafrank77/ML-Fifa-Predictions/assets/41444376/ace08548-a8e1-4314-8833-1611194d64b7)
   
5. For the Transfermarkt link, you will just need to paste the URL from Transfermarkt (this is to retrieve the image from the Transfermarkt URL).

6. To retrieve the achievements, follow these steps:

   - Click on Achievements
   
     ![image](https://github.com/joshuafrank77/ML-Fifa-Predictions/assets/41444376/4bfec591-3f55-4b88-91a0-f8a0d38f0229)

   - Count all the titles marked within the red rectangle, as shown in the example below:
   
     ![image](https://github.com/joshuafrank77/ML-Fifa-Predictions/assets/41444376/4d474bc9-3afd-454f-b65b-942b7249064e)
   
     In this case, for Mbappe, there are 56 titles as indicated.
   
     ![image](https://github.com/joshuafrank77/ML-Fifa-Predictions/assets/41444376/a8a5020b-e41b-48de-9099-821ce4ed531d)

7. For Besoccer Elo and Besoccer Ranking, you can obtain this information from the [BeSoccer website](https://www.besoccer.com/). Type in the player's name to search for them. In the top image, you can find the Elo rating. For example, for Mbappe, the Elo rating is 90. In the bottom image, you can find the Rating Progression General Ranking Table, which displays the player's ranking. In this case, the ranking for Mbappe is 7.
   
   ![image](https://github.com/joshuafrank77/ML-Fifa-Predictions/assets/41444376/53dafaf7-b399-4f10-b7e7-04b3b2fb8284)
   
   ![image](https://github.com/joshuafrank77/ML-Fifa-Predictions/assets/41444376/62095765-4ca7-47c4-b2e5-86ace4c9ad02)
   
8. To obtain information on Club Total Appearances, Goals, Assists, and Minutes, you can visit [this webpage](https://www.transfermarkt.com/) and navigate to the player you want to predict. Follow these steps:
   
   - Search for the player you want to predict.
   
   - Navigate to the player's profile and click on the "Stats" tab.
   
   - Under the "Stats" tab, click on "All seasons" as shown below:
   
     ![image](https://github.com/joshuafrank77/ML-Fifa-Predictions/assets/41444376/ed4d5016-83f1-4e24-8064-6a94cd5b0d0b)
   
   - After clicking "All seasons," scroll down to see the total statistics, as shown below:
   
     ![image](https://github.com/joshuafrank77/ML-Fifa-Predictions/assets/41444376/a0110dde-9001-4064-aecb-bf0dc837614a)
   
     ![image](https://github.com/joshuafrank77/ML-Fifa-Predictions/assets/41444376/8fe89f86-4759-435c-a89c-fbeae753834f)
   
     In this case, for Mbappe, the total statistics are as follows:
     - Appearances: 325
     - Goals: 244
     - Assists: 116
     - Minutes Played: 24,464
     
     ![image](https://github.com/joshuafrank77/ML-Fifa-Predictions/assets/41444376/8b69cd6c-9b9f-41e5-a88f-b32b656290c3)
     
9. To obtain the National Team Total Appearances, Goals, Assists, and Minutes, follow these steps:

   - In the player's profile on the [Transfermarkt website](https://www.transfermarkt.com/), click on the "National Team" tab as shown below:
   
     ![image](https://github.com/joshuafrank77/ML-Fifa-Predictions/assets/41444376/99470578-c575-4698-a73b-a901fa77a9a7)
   
   - After clicking the "National Team" tab, the information we need will be displayed, as shown below:
   
     ![image](https://github.com/joshuafrank77/ML-Fifa-Predictions/assets/41444376/60508d5c-fd2b-4d12-8cd9-d418499f8c84)
   
   In this case, for Mbappe's national team, the total statistics are as follows:
   - Appearances: 68
   - Goals: 38
   - Assists: 24
   - Minutes Played: 5,124
   
   ![image](https://github.com/joshuafrank77/ML-Fifa-Predictions/assets/41444376/c656c8d7-38b0-4748-85f8-40a2c0b03980)

10. To obtain the First Tier Total Appearances, Goals, Assists, and Minutes, follow these steps:

   - Navigate to the player's profile and click on the "Stats" tab.
   
   - Under the "Stats" tab, click on "All seasons" as shown below:
   
     ![image](https://github.com/joshuafrank77/ML-Fifa-Predictions/assets/41444376/ed4d5016-83f1-4e24-8064-6a94cd5b0d0b)
     
   - Click on the dropdown menu "League ranking / League type:" and select the "First Tier" option.
   
   - Then, click on the "show" button.
   
     ![image](https://github.com/joshuafrank77/ML-Fifa-Predictions/assets/41444376/594ad652-4313-482d-bc06-1f555653a2a6)
     
   - A table will appear showing the information we need, as shown below:
   
     ![image](https://github.com/joshuafrank77/ML-Fifa-Predictions/assets/41444376/4e76f342-d676-4c4a-84fe-b06b9822be84)

   In this case, for Mbappe, the first-tier statistics are as follows:
   - Appearances: 217
   - Goals: 164
   - Assists: 67
   - Minutes Played: 16,041
   
   ![image](https://github.com/joshuafrank77/ML-Fifa-Predictions/assets/41444376/dba6d3f8-5d1d-4f30-b3ab-757596787a6a)

11. To obtain the last season's stats for Appearances, Goals, Assists, and Minutes, follow these steps:

   - Navigate to the player's profile and click on the "Stats" tab.
   
   - Under the "Stats" tab, click on "Current season" as shown below:
   
     ![image](https://github.com/joshuafrank77/ML-Fifa-Predictions/assets/41444376/cf68fc3a-7e7b-42a1-8251-55a19c18dfa9)
     
   - Select the desired season from the "Filter by season" dropdown menu.
   
   - Then, click on the "show" button.
   
     ![image](https://github.com/joshuafrank77/ML-Fifa-Predictions/assets/41444376/5cffda6c-74b7-4be0-89e5-3c19ad66bac4)
     
   - A table will appear showing the information we need. In this case, for Mbappe, the stats for the last season (22/23) are as follows:

     ![image](https://github.com/joshuafrank77/ML-Fifa-Predictions/assets/41444376/2ccfdff3-bcf2-4f17-8bf9-e94f2a71e04d)

     - Appearances: 43
     - Goals: 41
     - Assists: 10
     - Minutes Played: 3,564

     ![image](https://github.com/joshuafrank77/ML-Fifa-Predictions/assets/41444376/af1daa89-8791-441c-a3eb-f594abeb99ff)

12. To obtain the stats for International Cups, follow these steps:

   - Navigate to the player's profile and click on the "Stats" tab.
   
   - Under the "Stats" tab, click on "Stats by competition" as shown below:
   
     ![image](https://github.com/joshuafrank77/ML-Fifa-Predictions/assets/41444376/306e11f4-9807-4dde-8cdd-70c06d98b022)
     
   - Scroll down to the International Cups table.
   
     ![image](https://github.com/joshuafrank77/ML-Fifa-Predictions/assets/41444376/5e3963ce-4b87-45dd-9788-217487ee9e55)
     
   - In this case, for Mbappe, the stats for International Cups are as follows:
   
     - Appearances: 63
     - Goals: 40
     - Assists: 28
     - Minutes Played: 4,834

      ![image](https://github.com/joshuafrank77/ML-Fifa-Predictions/assets/41444376/c2f5fa0a-b3bf-490c-b197-c780eac95c76)

      Now for each idividual competiton we need to add the Appearances, Goals , Assists, and Minutes of all the years that the player participated in that competition. 
      
      For example Mbappe participated in 7 Champions league we need to add this information from the table as shown below:
      
      ![image](https://github.com/joshuafrank77/ML-Fifa-Predictions/assets/41444376/41942e16-c2cc-4226-8933-8f75b8f27d43)

     - Champions League:
       - Appearances: 61
       - Goals: 40
       - Assists: 26
       - Minutes Played: 4,770
    
     ![image](https://github.com/joshuafrank77/ML-Fifa-Predictions/assets/41444376/0886c95f-6afb-48a5-8e51-6e225024131f)

     - Europa League:
       - Appearances: 1
       - Goals: 0
       - Assists: 1
       - Minutes Played: 34

     ![image](https://github.com/joshuafrank77/ML-Fifa-Predictions/assets/41444376/869b7410-f5ce-4300-a03e-a2795e0aa781)

     - UEFA Youth League:
       - Appearances: 1
       - Goals: 0
       - Assists: 1
       - Minutes Played: 30

   This is what the filled-in table would look like:

  ![image](https://github.com/joshuafrank77/ML-Fifa-Predictions/assets/41444376/c1a14a52-8ed8-445d-9279-913278052188)

  
  


By following these instructions and providing the necessary information, you will be able to predict players' overall and potential ratings using the manual input version of the ML-Fifa-Predictions model.



