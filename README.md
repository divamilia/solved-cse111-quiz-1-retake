Download Link: https://assignmentchef.com/product/solved-cse111-quiz-1-retake
<br>
<strong>DATABASESYSTEMS</strong>

(30 points)

Consider the following relational schema, provided as a SQLite database populated with sample data:

<ul>

 <li>Product(maker, model, type)</li>

 <li>PC(model, speed, ram, hd, price)</li>

 <li>Laptop(model, speed, ram, hd, screen, price)</li>

 <li>Printer(model, color, type, price)</li>

</ul>

Write SQL statements for the following queries (<strong>5 points each</strong>) in the given quiz-1.sql file:

<ol>

 <li>What makers produce Laptops cheaper than $2000 with a screen larger than 16?</li>

 <li>What makers produce PCs but do not produce Laptops?</li>

 <li>For every maker that sells both PCs and Printers, find the combination of PC and Printer that hasmaximum price. Print the maker, the PC model, Printer model, and the combination price (PC price + Printer price).</li>

 <li>What Laptop hd sizes are offered in at least 2 different models?</li>

 <li>What PCs are less expensive than all the Laptops? Print the model and the price.</li>

 <li>What makers produce at least a Laptop model and at least 2 Printer models?</li>

</ol>

We will grade your quiz by running the quiz-1.sql file on the given database and another database populated with different data. So, make sure your SQL statements are general. You should test that your code works without errors by running the command sqlite3 data.sqlite &lt; quiz-1.sql in the terminal. quiz-1.sql is the only file you have to turn in.