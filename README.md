This is a demonstration of a simple form of text analysis: the word cloud. This demonstration will require the use of R, as well as the R packages `dplyr`, `tm`, and `wordcloud`. Using these tools, there are actually three different forms of word cloud that will be demonstrated.


The first form is a basic word cloud that displays the words used in a segment of text such that the font size of any given word is proportional to the frequency of its usage (i.e., the more a word is used, the larger it will appear).


The second form is a comparison cloud. In this form, two or more different blocks of text are compared; text size is proportional in the same way as the basic format of word cloud. In this format, however, color is used to differentiate the words favored in the different blocks of text. Where a given word is used in more than one block of text in the comparison, the block of text where the frequency of that word is greatest will be the one to display that word in that block's color.


The third form is a commonality cloud. In this form, a single word cloud is displayed, but only those words that are common across all compared blocks of text are used.


Important note:


For the purposes of this demonstration, I have used the text of the acceptance speeches given by the Democratic (Hillary Clinton) and GOP (Donald Trump) Presidential Nominees at their respective conventions in 2016. These texts were used because they are timely and present an interesting opportunity to use exactly the tools that I am demonstrating here. I will not be making any political critiques of these candidates or their speeches; I present this in an entirely politically neutral context. I am trying to demonstrate a skill set, not a political preference. This demonstration should not be understood in any way to indicate support for any candidate.