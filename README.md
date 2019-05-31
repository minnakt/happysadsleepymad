# 😊😢😴😤 (HappySadSleepyMad) 
This is an adapted version of a private repo. As such some code has been omitted.

## 📈 Data collection 
Data was collected from Twitter from March 9th to April 12th. Around 300,000 tweets in total were collection during this one month period. Tweets collected for every emoji except 'Symbol' emojis (which includes emojis like flag emojis). Tweets stored in a SQL database.

## 🤓💻 Analyses 
- K-means clustering comparing sentiment to emotion.
- NLP word vectorization to find words used in similar contexts to certain emojis across different languages.
- KNN model that could classify the sentiment based on all emojis in a tweet with accuracy prediction around 75%. Used for keywords "data science" and "Donald Trump."
- Attempted a model to predict what emojis a person would use based on the text of tweet. However, accuracy was only 3%.

## 🎨 Visualizations 
- Matplotlib for K-means clustering. 
- D3 bar graph to show ratio of positive/negative/neutral tweets corresponding to each of 😊😢😴😤.
- D3 bar graph to show language frequency.
- Radial graphs to show words used in similar contexts to each of 😊😢😴😤.
- Word clouds showing most commonly associated words as well as the ratio of negative and positive emojis, and what emojis are used in negative versus positive contexts with respect to the keyword.
- Pie chart showing top emojis for 'data science.'

## 🎉 Poster / Results 
![download](https://user-images.githubusercontent.com/47064971/58680914-f34f2100-8337-11e9-9bc2-d05afcdc3ebf.png)
<br></br>
High quality version can be seen as a PDF at https://github.com/minnakt/happysadsleepymad/blob/master/final_poster.pdf.

## 📝 Blog 
More detailed information about the project process can be found here:
- Part 1: https://medium.com/@happysadsleepymad/emojis-patterns-in-text-brown-cs1951a-blog-post-1-eee079c6f436
- Part 2: https://medium.com/@happysadsleepymad/blog-post-2-43017b9698fb
- Part 3: https://medium.com/@happysadsleepymad/final-blog-post-f92f24c3d6c5

If a summary is required, I recommend to read Part 3 only; there are some interesting results not included on the poster included on there. 

## 📊 Tweet Database  
https://drive.google.com/file/d/1Bt_KnTEvEh1LbtU-GKYKfMVYYYYSeYAV/view?usp=sharing

## 🔥👩❤️ Acknowledgements 
This project could not have been completed without the following lovely and brilliant women:
- Katherine Sang (https://github.com/artset) 💛
- Iris Yao (https://github.com/iris0301) 🧡
- Maggie Wu (https://github.com/maggie1059) 💙

## 📚 Resources 
Sources for creating the emoji json data:
- https://github.com/iamcal/emoji-data 
- https://github.com/amio/emoji.json 
- https://github.com/words/emoji-emotion/blob/master/index.json

D3 pie chart:
- https://codepen.io/lig-dsktschy/pen/mMgeEY

Radial graphs: 
- https://stackoverflow.com/questions/33695073/javascript-polar-scatter-plot-using-d3-js
