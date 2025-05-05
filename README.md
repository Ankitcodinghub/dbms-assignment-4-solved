# dbms-assignment-4-solved
**TO GET THIS SOLUTION VISIT:** [DBMS Assignment 4 Solved](https://www.ankitcodinghub.com/product/dbms-assignment-4-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;100158&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;DBMS Assignment 4 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Consider that we have the following tables in a database (primary keys are underlined):

Student (roll_no int not null, name varchar(30) not null, cgpa decimal(7,2) not null with default 0.00, credits_cleared int not null with default 0)

Student_course (roll_no int not null, course_cd char(2) not null, grade_point int not null with default 0) [Note: Here Grade point denotes integer equivalent of letter grades, e.g., EX10, A9, etc.]

Course (course_cd char(2) not null, course_name not null, credits int not null) Prerequisite (course_cd char(2) not null, prereq_course_cd char(2) not null)

</div>
</div>
<div class="layoutArea">
<div class="column">
2.

3.

</div>
</div>
<div class="layoutArea">
<div class="column">
a. b.

</div>
<div class="column">
Write a trigger on the Student_course table so that whenever a row is inserted, the value for credits_cleared of the corresponding student will be updated using the Course table. Note that credits cleared will be considered to be non-zero if the grade point obtained is greater than or equal to 5. [10] Write a trigger on the Course table for update of the column credits so that whenever its value is changed, for all the students in the Student table, who have taken that course, the credits_cleared column will be appropriately updated. Note that credits cleared will be considered to be non-zero if the grade point obtained is greater than or equal to 5. [10]

Consider the same tables used in Problem 1.

Write a database procedure/function that will take a roll_no as input and update the value of the cgpa column using the Course table and the Student_course table. The value of cgpa should also be returned as output. [20]

Consider the same tables used in Problem 1. Assume that any course that does not have a pre-requisite, will not exist in the Prerequisite table

Write a recursive query which will take a course_cd (say AB) as a hardcoded input (i.e., somewhere in your SELECT, there will be a clause like AND course_cd = ‘AB’ or WHERE course_cd = ‘AB’. This input is not in the sense of an input in a function/procedure) and return the total number of credits one can complete if AB is completed. If AB is not the prerequisite for any other course, it should return 0. Note, you need to make use of the Course table and the Prerequisite table only. [10]

</div>
</div>
</div>
