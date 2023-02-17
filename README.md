# Projects:



<h2 id="python">Python</h2>

<div class="card">
  <h3>#Fitnesiac - gym tracking app</h3>
  <p><b>Python, Django</b></p>
  <ul>
    <li>A website made using django. A user can create an account to share their gym workouts and comment progress of other users.</li>
    <li>Users can follow each other to see each other's posts, or they can tag a post to make it visible to everyone.</li>
    <li>The user can also discover new exercises for specific body parts thanks to gifs showing how to perform them.</li>
    <li>You can visit the website by clicking on <a id="inner" href="https://skowronski.pythonanywhere.com">this link</a> and logging into a test account ( <em>beta | 1234!@#$ </em> ) </li>
  </ul>
  <a href="https://github.com/skowronskid/fitnesiac"><span class="card-link-spanner"></span></a>
</div>


<div class="card">
  <h3>#SUPERVISION_HACK hackathon</h3>
  <p><b>Python, Web Scraping, Natural Language Processing</b></p>
  <ul>
    <li>The task of the hackathon was to use webscraping to download KIID documents and then extract the information needed from them and present it in a structured form</li>
    <li>The main part of the task was to find parts of the text using regular expressions and fuzzy matching </li>
    <li>Another part of the task involved creating a Bag of Words model.</li>
    <li>We came third in this competition</li>
  </ul>
  <a href="https://github.com/wojciechkosiuk/Hackathon2k22"><span class="card-link-spanner"></span></a>
</div>


<div class="card">
  <h3>Chess - predicting number of moves to mate</h3>
  <p><b>Python, Machine Learning</b></p>
  <ul>
    <li>We had a dataset of every possible situation of endgame when on the board there are only two kings and a white rook.The aim was to predict number of moves required to mate.</li>
    <li>Carried out an in-depth analysis of the possible outcomes (what the situation looks like when there is a draw, mate, 1 move)</li>
    <li>We compared the prediction results obtained using regression and multilabel classification.</li>
  </ul>
  <a href="https://github.com/skowronskid/projects/blob/main/supervised_ml/chess_mate/kings_rook_mate.ipynb"><span class="card-link-spanner"></span></a>
</div>


<div class="card">
  <h3>AutoKeras benchmark</h3>
  <p><b>Python, AutoKeras</b></p>
  <ul>
    <li>Part of a larger project in which we benchmarked AutoML frameworks in a simmilar way to <a href="https://arxiv.org/abs/1907.00909">this benchmark</a>. </li>
    <li>In the article, we tried to explain how the AutoKeras framework works and then subjected it to a classification task on 22 datasets</li>
    <li>Finally, we compare the results with other groups who have worked with FLAML, AutoGluon, AutoPytorch and Autosklearn.</li>
  </ul>
  <a href="https://github.com/skowronskid/projects/tree/main/supervised_ml/AutoKeras_benchmark"><span class="card-link-spanner"></span></a>
</div>


<div class="card">
  <h3>USA census</h3>
  <p><b>Python, Unsupervised Machine Learning</b></p>
  <ul>
    <li>Conducted clustering on the 1990 USA census dataset</li>
    <li>As a result, we identified 5 groups of types of people</li>
  </ul>
  <a href="hhttps://github.com/skowronskid/projects/blob/main/unsupervised_ml/usa_census.ipynb"><span class="card-link-spanner"></span></a>
</div>


<div class="card">
  <h3>UK car accidents</h3>
  <p><b>Python, Unsupervised Machine Learning</b></p>
  <ul>
    <li>Given the coordinates of all car accidents in cities and towns reported in UK in years 2000-2016 we grouped them to distinguish between the areas.</li>
    <li>We tried using different methods of clustering to figure out which one of them gave us the best results. </li>
    <li>The result is a map of the UK with clearly separated urban areas. </li>
  </ul>
  <a href="https://github.com/skowronskid/projects/blob/main/unsupervised_ml/urban_uk.ipynb"><span class="card-link-spanner"></span></a>
</div>



<div class="card">
  <h3>GDP forecast chart</h3>
  <p><b>Python,R, matplotlib</b></p>
  <ul>
    <li>The purpose of the project was to find a graph on the web where the data is presented incorrectly and redesign it.  </li>
    <li>I found such graph on <a href="https://www.economist.com/graphic-detail/2021/10/12/the-imf-warns-that-the-global-economic-recovery-will-be-grossly-uneven">The Economist</a></li>
    <li>First I redesigned it using ggplot2 and some time later I came back and made it even better using matplotlib. </li>
  </ul>
  <a href="https://github.com/skowronskid/projects/blob/main/data_visualisation/GDP_forecasts_chart/Raport.ipynb"><span class="card-link-spanner"></span></a>
</div>

<h2 id="r">R</h2>

<div class="card">
  <h3>Facebook Messenger dashboard </h3>
  <p><b>R, shiny, plotly</b></p>
  <ul>
    <li>The project consisted of presenting our data in the form of a dashboard. In our case, we chose data from Facebook Messenger.</li>
    <li>We created the dashboard as a shiny website. Most of the graphs are made with plotly, and are interactive.</li>
    <li>You can visit it by clicking <a href="https://skowronski.shinyapps.io/messenger/">this link</a> (you might have to wait a couple seconds becasuse the data is loaded from json files). </li>
  </ul>
  <a href="https://github.com/skowronskid/projects/tree/main/data_visualisation/FB_shiny"><span class="card-link-spanner"></span></a>
</div>

<div class="card">
  <h3>BTC impact on environment poster</h3>
  <p><b>R, Inkscape</b></p>
  <ul>
    <li>The task of the project was to present something that has a negative impact on the environment in the form of a poster. In our case it was BTC.</li>
    <li>Using the data we found online we made plots using ggplot2 and exported them as vector images.</li>
    <li>We arranged the plots with texts regarding in poster's form using Inkscape. </li>
  </ul>
  <a href="https://github.com/skowronskid/projects/tree/main/data_visualisation/BTC_environment"><span class="card-link-spanner"></span></a>
</div>


<div class="card">
  <h3>Nobel Prize laureates dashboard</h3>
  <p><b>R, shiny</b></p>
  <ul>
    <li>It's a dashboard of Noble Prize laureates using the data from <a href="https://www.kaggle.com/datasets/imdevskp/nobel-prize">Kaggle</a></li>
    <li>There are interactive plots made using plotly.</li>
    <li>You can visit the site by clicking <a href="https://skowronski.shinyapps.io/Nobel_Prize/">this link</a> </li>
  </ul>
  <a href="https://github.com/skowronskid/projects/tree/main/data_visualisation/Nobel_shiny"><span class="card-link-spanner"></span></a>
</div>



<h2 id="matlab">Matlab</h2>
<div class="card">
  <h3>Application for LU decomposition using Crout's method </h3>
  <p><b>Matlab</b></p>
  <ul>
    <li>It's an implementaton of Crout's method for LU matrix decomposition in form of Matlab application</li>
    <li>Application accepts input of two matrices and solves a matrix equation using LU decomposition </li>
    <li>Outputs both L and U matrices as well as the solution</li>
  </ul>
  <a href="https://github.com/skowronskid/projects/tree/main/Matlab/LU_Crout"><span class="card-link-spanner"></span></a>
</div>


<div class="card">
  <h3>Jarratt's method</h3>
  <p><b>Matlab</b></p>
  <ul>
    <li>It's an implementaton of Jarrat's method for solving polynomial equations</li>
    <li>Implementation uses Horner's algorithm to determine derivatives </li>
    <li>Shows graphs of number of steps required and convergence to solution for points in complex plane. </li>
  </ul>
  <a href="https://github.com/skowronskid/projects/tree/main/Matlab/MetodaJarratta"><span class="card-link-spanner"></span></a>
</div>


<h2 id="java">Java</h2>


<div class="card">
  <h3>Android application for placing markers on the map of Warsaw.</h3>
  <p><b>Java, Android Studio</b></p>
  <ul>
    <li>Using Android Studio, we designed an android application that can be used to place markers of places where you can drink beer in Warsaw.</li>
    <li>User can add information to the marker about the place and rate it</li>
    <li>User can filter the placed markers</li>
    <li>You can watch a quick presentation <a href="https://www.youtube.com/watch?v=qd5JLx1BE3o">here</a></li>
  </ul>
  <a href="https://github.com/skowronskid/projects/tree/main/Java/Lokalizator_android"><span class="card-link-spanner"></span></a>
</div>






