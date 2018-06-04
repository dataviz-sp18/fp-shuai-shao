In this project, I visualized the results of my research on moral judgments. The projects include two parts with the same content. First, I wrote a research paper and it indicates how I applied the rules of data visualization to an academic research paper. My goal is to generate a printable journal paper with R. This is the link: https://shaoshuai.shinyapps.io/moral_judgments/. Second, I designed a webpage with the graphics. It is a convenient way to present my project, especially for those who seldom read the psychology academic journals. My target audiences are psychologists who are interested in my project. Therefore, I am presenting the results according to APA style (sixth edition).

Truthfulness: The data were collected through real experiments conducted by UBC Child Lab (I am the lab's co-author). We recruited the participants in China and Canada, randomly assigned them to experimental conditions, and strictly controlled the confounding variable (i.e., the location, the way of interviewing, the experiment stimuli, etc.). Therefore, generally speaking, the dataset is true and reliable.

Beautiful: I tried to present the data in the most precise and direct way, as required by the academic journal. I received the feedback in my presentation that the color of my graphics looks messy. Therefore, I used the color blue in all my graphics to make it clearer.

Functional: These graphics allow the audience learn the statistic results immediately, which is exactly the purpose of graphics in academic journals. Besides, the readers can not only learn the numbers such as P-value and X^2 value quickly but also have the intuitive feelings from the graphics directly. Therefore, these graphics successfully convey the necessary information to readers. 

Enlightening: This is a very enlightening topic since moral judgments is an important angle for us to understand human development and social cognition in modern society. Specifically, the moral education is an indispensable part of school education. Moreover, traditional psychology studies are mainly conducted with WEIRD (Western, educated, industrialized, rich and democratic) Societies. A cross-cultural comparison will help us understand the moral judgments comprehensively. 

Insightful: These graphics are majorly spontaneous insight since the results are quite straight-forward. I tried to convert some of them into interactive ones with plot_ly but I found it not worthy since a static graphic has conveyed enough information to readers.

Some improvements based on the presentation feedbacks:

- I removed the "Most Frequent Word" graphics in the text analysis since their functions are overlapped with the word cloud.
- I adjusted the color of my graphics. Now they are all in blue (steel blue, light blue, royal blue, etc.) Those are not very "colorful" graphics but you can still differentiate them easily.
- I remove the error bar, since it might be confusing to laypeople, and then I filled the bars instead of merely coloring the boundary.  

Bugs:

The [wordcloud2] package is still under developing. One obvious bug is that we cannot display more than one interactive word clouds with [wordcloud2], although we can run them out separately. Hence, I substituted one interactive [wordcloud2] with static [wordcloud]. Also, the [wordcloud2] might fail to be loaded occasionally. However, I insisted on presenting [wordcloud2] because it can depict a really beautiful interactive word cloud. I hope the developers can solve the bug soon.

Something else I want to address:

At the very beginning, I decided to visualize my research with no hesitation, since it contains numeric data and text data. I can visualize the proportion, text analysis, means, etc. However, when doing my assignment, I found I failed to apply all that I learned in this class to my final project. It might be not a wise choice to present my research project since as a psychology student, I can hardly have a chance to draw an interactive map because we seldom have a dynamic big data. On the other hand, academic graphics have very high standards for details, such as the color selection, data cleaning, etc. Hopefully, I will have a dynamic and large dataset in future so that I can then fully use my knowledge of interactive graphics, network analysis and so on.
