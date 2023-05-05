Download Link: https://assignmentchef.com/product/solved-cse654-484-homework-01
<br>
In this homework we will use vector representation of words. Here are the steps of the homework

<ol>

 <li>Download the standard textbooks from the Ministry of Education <a href="http://aok.meb.gov.tr/kitap/">(</a><a href="http://aok.meb.gov.tr/kitap/">http://aok.meb.gov.tr/kitap/</a><a href="http://aok.meb.gov.tr/kitap/">)</a> for at least 20 textbooks (literature, history, sociology, etc.) Convert them to text documents. You should have at least 2000 pages of Turkish text. More is better.</li>

 <li>Download the word2vect source code <a href="https://github.com/tmikolov/word2vec">https://github.com/tmikolov/word2vec</a> . Compile and run it on the whole textbook set. Run a few distance and analogy demos to see if the vectors are fine.</li>

 <li>As we know from the lectures, word2Vect produces vectors only for the words seen before. We will try to come up with a new way of producing vectors. Here are the steps for your new algorithm

  <ol>

   <li>Find an open source program to divide Turkish words into syllables. If we are given Turkish words “okula gitmek”, the syllables are (o, ku, la, git, mek).</li>

   <li>Convert all the words in your data sets into syllables and run word2Vect on this new set. Each syllable will have its own vector.</li>

   <li>To calculate the vector for a given Turkish word, divide the word into syllables and then add the vectors of each word. This way you can find the word representation for any word.</li>

  </ol></li>

 <li>Run analogy and similarity experiments for both vector sets (word2vect and syllable based) for</li>

</ol>

at least 30 Turkish examples. Measure the accuracy using formulas we learned in the lectures.




Prepare your report and submit it to the Teams page. You may use any programming language for the implementation. The word2vec source code in C language but you will use it to produce only the word vectors.




Notes

<ol>

 <li>You will demo your homework result online</li>

 <li>Your report should be very clear about the formula for testing calculation</li>

 <li>Your report is as important as the homework itself and it is not optional</li>

</ol>