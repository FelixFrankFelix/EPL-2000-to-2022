
# EPL Analysis 2000 to 2022

The Project features an analysis of EPL Standings from the 2000/01 season to the 2021/22 season. I went ahead to build predictive ML models; Linear, Random Forest and Catboost Regressors to see how well a team in the 2021 season would perform in the 2022 season and what position it will likely finished.

## Analysis



![Analysis Dashboard]('/Analysis Dashboard/1.png')
From Analysis, Manchester City, The Current EPL Title Holders are the raving force in the EPL with presence of heavy rivalry between the champions and Liverpool in recent times.
    
Although Manchester United was the dominant force for a long time in the earlier seasons of the EPL, they experienced a decline in 2012 that they haven't risen from, but managed to clinch 2nd in both the 2017/18 and 2020/21 seasons.

Man City have not always been a force in the EPL but had a steady incline from the 05/06 season until winning their first title in the 11/12 season and remaining in top form since then, with their worst performance been the 2015/16 EPL only finishing  4th 

### Tools
- Pandas
- Canva

## ML Model Building

I went ahead to build ML models to predict the position of each team in the EPL 2020/21 Season If they had played in the 2021/22 EPL Season. 
I used Linear, Random Forest, and Catboost Regressor Models to build predictive models to predict the different teams' positions and compare the different models' performances. 

All models use the features, Points, and Goal Difference, (Obviously! ) with Goals Scored, Goals Conceded, Number of Wins, and Loses as features for accuracy enhancement.
I dropped Goal Difference and Draws to avoid issues due to multicollinearity 

On Aggerate, As predicted by the Models The 2020/21 Manchester City had a chance of claiming the title but will most probably finish in Second place if they had played in the 2021/22 Season. While the 2020/21 Red devils have a chance of finishing 3rd place and qualifying for the 2023 UEFA Champions League. But, Unfortunately, their 2021/22 version finished at 6th. The Table below shows as predicted by my models how well each team in the 2020/21 season would perform in the succeeding season


![App Screenshot]('/Analysis Dashboard/Table.png')


