# redwine quality

Red wine is a type of wine made from dark-colored (black) grape varieties. The actual color of the wine can range from intense violet, typical of young wines, through to brick red for mature wines and brown for older red wines. The juice from most purple grapes is greenish-white; the red color comes from anthocyan pigments (also called anthocyanins) present in the skin of the grape; exceptions are the relatively uncommon tentoria varieties, which produce a red colored juice. Much of the red-wine production process therefore involves extraction of color and flavor components from the grape skin.
Wine producers constantly brag about the quality ratings that their wines receive from critics, because a high wine rating — implying high quality — translates into increased sales for a wine. But quality wines come in all colors, degrees of sweetness and dryness, and flavor profiles.
Just because a wine is high quality doesn’t mean that you will actually enjoy it. Personal taste is more relevant than quality in choosing a wine. A good wine is, above all, a wine that you like enough to drink — because the whole purpose of a wine is to give pleasure to those who drink it.

In this project, the question I am going to consider is

•	Determine which physiochemical properties make a wine 'good'!

•	$quality$ >=7 => "good", $quality$ <= 4 => "poor", $quality$ ==5 or 6 => "okay"

For predicting these scores, two data mining techniques will be used in this project.  I will show a few approaches to each problem, as well as considerations when we're evaluating how these perform.

•	regression techniques which will output numbers (Support Vector Regression)

•	classification techniques, where each quality score is considered a class or category (Random Forest & Decision Tree)

Note: A decision tree is built using the whole dataset considering all features, but in random forests a fraction of the number of rows is selected at random and a particular number of features are selected at random to train on and a decision tree is built on this subset.
The target audience for this project is for wine producers to increase sales in countries like China where wine market is growing. The Chinese like to drink wine. China’s millionaires, of which there are beau coup, don’t think twice about dropping $300 on a bottle of wine. And, since China’s economy looks like it’s emerging from its recent doldrums, wine consumption is on the upswing. Not only is per capita consumption rising, but the way the Chinese drink wine is changing.
Source: https://www.kaggle.com/uciml/red-wine-quality-cortez-et-al-200
