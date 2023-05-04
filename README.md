Download Link: https://assignmentchef.com/product/solved-cs6360-001-quiz-4
<br>
<strong>Database Design </strong>

<strong> </strong>

<strong> </strong>

<ol>

 <li>Consider the following relation:</li>

</ol>

CAR_SALE(Car#, Date_sold, Salesperson#, Commission%, Discount_amt)




Assume that a car may be sold by multiple salespeople, and hence {Car#, Salesperson#} is the primary key. Additional dependencies are




Date_sold → Discount_amt and

Salesperson# → Commission%

Based on the given primary key, is this relation in 1NF, 2NF, or 3NF? Why or why not? How would you successively normalize it completely?




<ol start="2">

 <li>Consider the following relation for published books:</li>

</ol>

BOOK (<u>Book_title</u>, <u>Author_name</u>, Book_type, List_price, Author_affil, Publisher)




Author_affil refers to the affiliation of author. Suppose the following dependencies exist:

Book_title → Publisher, Book_type

Book_type → List_price

Author_name → Author_affil




<ol>

 <li>What normal form is the relation in? Explain your answer.</li>

 <li>Apply normalization until you cannot decompose the relations further.</li>

</ol>

<strong> </strong>




<ol start="3">

 <li>Consider the relation REFRIG(Model#, Year, Price, Manuf_plant, Color),which is abbreviated as REFRIG(M, Y, P, M_P, C), and the following set F of functional dependencies: F = {M → M_P, {M, Y} → P, M_P → C}</li>

</ol>




<ol>

 <li>Evaluate each of the following as a candidate key for REFRIG, giving reasons why it can or cannot be a key: {M}, {M, Y}, {M, C}.</li>

</ol>




<ol>

 <li>Based on the above key determination, state whether the relation REFRIG is in 3NF and in BCNF. Explain why. If relation is not already in 3NF, normalize it into 3NF.</li>

</ol>

<strong> </strong>

<ol start="4">

 <li>Are F and G equivalent?</li>

</ol>

F = {A-&gt;C, AC-&gt;D, E-&gt;AD, E-&gt;H}

G = {A-&gt;CD, E-&gt;AH}







<ol start="5">

 <li>Consider the relation schema S (P, <u>C</u>, <u>R</u>, A) and below functional dependencies. Normalize S into 3NF by using minimal cover method.</li>

</ol>

P -&gt; R, C, A

R, C -&gt; A, P

A-&gt;C