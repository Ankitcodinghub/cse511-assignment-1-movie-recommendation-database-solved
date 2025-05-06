# cse511-assignment-1-movie-recommendation-database-solved
**TO GET THIS SOLUTION VISIT:** [CSE511 Assignment 1-Movie Recommendation Database Solved](https://www.ankitcodinghub.com/product/cse511-assignment-1-movie-recommendation-database-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96104&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE511 Assignment 1-Movie Recommendation Database Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="section">
<div class="layoutArea">
<div class="column">
Create Movie Recommendation Database

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Create Movie Recommendation Database

</div>
</div>
<div class="layoutArea">
<div class="column">
Submit Assignment

</div>
</div>
</td>
</tr>
<tr>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Introduction

You have learned how to design a movie recommendation database. The assignment will give you an opportunity to create such a database from scratch and build applications on top of this database.

Background

In this database, a movie has two attributes: id, title. A possible movie record is as follows: 54796, 2 Days in Paris (2007).

A movie can be categorized into multiple genres. A genre is selected from Action, Adventure, Animation, Children’s, Comedy, Crime and so on. A movie may not have a genre.

A user can give a 5-star scale rating (0-5) to a movie. For instance, User (ID 4) gave 4 stars to Movie “God Father”. A user can only rate a movie once. The database needs to log each rating operation. The database should not allow any out-of-range ratings

A user can also assign a tag to a movie. A user can tag a movie multiple times. For instance, User (ID 20) assigned “very cool” tag to Movie “Mission: Impossible – Ghost Protocol”. Two days later, he added a new tag “unbelievable” to the same movie. Each tag is typically a single word or short phrase. The meaning, value and purpose of a particular tag are determined by each user. The database needs to log each tagging operation.

</div>
</div>
<div class="layoutArea">
<div class="column">
Requirement

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
https://canvas.asu.edu/courses/75440/assignments/1882002

</div>
<div class="column">
1/4

</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
1/24/2021 Create Movie Recommendation Database

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
According to the database design made by you, the movie database includes multiple tables. In particular, you need to consider seven tables: users, movies, taginfo, genres, ratings, tags, hasagenre. In this phase, you must create these tables and load the corresponding data into these tables.

1. The description of the tables is as follows. You should also check the requirement in the given graphic description:

users: userid (int, primary key), name (text)

movies: movieid (integer, primary key), title (text)

taginfo: tagid (int, primary key), content (text)

genres: genreid (integer, primary key), name (text)

ratings: userid (int, foreign key), movieid (int, foreign key), rating (numeric), timestamp (bigint, seconds since midnight Coordinated Universal Time (UTC) of January 1, 1970)

tags: userid (int, foreign key), movieid (int, foreign key), tagid (int, foreign key), timestamp (bigint, seconds since midnight Coordinated Universal Time (UTC) of January 1, 1970).

hasagenre: movieid (int, foreign key), genreid (int, foreign key)

2. The requirement only tells you the name and data type of each attribute in each table. You need to figure out the primary keys, foreign keys, constraints or other necessary

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
https://canvas.asu.edu/courses/75440/assignments/1882002

</div>
<div class="column">
2/4

</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="layoutArea">
<div class="column">
1/24/2021 Create Movie Recommendation Database

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
settings by yourself. The key information in the requirement is not complete and attributes can be primary keys and foreign keys at the same time.

Remarks

1. All table names and attribute names must be in lowercase letters and exactly same

with the specification.

2. You can use COPY FROM / INSERT to load data and test your tables but don’t put it in

the submission.

3. Your SQL script should NOT contain the commands to create database, change database or set encoding. Please do not use any commands to change Postgres DB settings. This may crash the grading environment! Your script should just simply create tables. I will decide the working database and all other parameters.

Test data

We provide some test data for you to try. The delimiter of all files is “%”. But the grading system will use more test data and test cases to try your SQL script.

Data link:

https://github.com/jiayuasu/Coursera-ASU- Database/tree/master/course1/assignment1/exampleinput (https://github.com/jiayuasu/Coursera-ASU- Database/tree/master/course1/assignment1/exampleinput)

Submission

Submit a single plain text file “solution.sql”

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
https://canvas.asu.edu/courses/75440/assignments/1882002

</div>
<div class="column">
3/4

</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="section">
<div class="layoutArea">
<div class="column">
1/24/2021 Create Movie Recommendation Database

</div>
</div>
<div class="layoutArea">
<div class="column">
https://canvas.asu.edu/courses/75440/assignments/1882002

</div>
<div class="column">
4/4

</div>
</div>
</div>
</div>
