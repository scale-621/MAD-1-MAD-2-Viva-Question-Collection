# MAD-1 - Level 2 Viva Questions

> Duplicate wording has been merged. The count shows how many times the same question or task was reported in the supplied PDFs.

## Flask, routing, and architecture

1. What does `@app.route()` do, and why is it a decorator? *(Asked 21 times)*
2. What is the difference between `render_template()`, `redirect()`, and `url_for()`? *(Asked 24 times)*
3. Does `url_for()` take a route path or a function name, and what happens if the name is wrong? *(Asked 7 times)*
4. What is Flask's default port, and how can you change it? *(Asked 10 times)*
5. What is a Flask secret key, and what breaks if it is removed? *(Asked 9 times)*
6. What do `db.init_app(app)` and `app.app_context()` do? *(Asked 5 times)*
7. What does `if __name__ == "__main__"` do, and what happens if it is removed? *(Asked 8 times)*
8. What is a Flask Blueprint, and why would you use one? *(Asked 3 times)*
9. What is a virtual environment, and why is it needed? *(Asked 4 times)*
10. What is the difference between two-tier, three-tier, client-server, and distributed architectures? *(Asked 20 times)*
11. What are horizontal and vertical scaling? *(Asked 18 times)*
12. What is load balancing, and why is it needed? *(Asked 18 times)*
13. Is the current stack scalable? How would you scale it for many users? *(Asked 7 times)*

## HTTP, REST, and APIs

14. What is HTTP, and why is it stateless? *(Asked 16 times)*
15. What is the difference between stateful and stateless communication? *(Asked 6 times)*
16. What is the difference between HTTP and HTTPS, and how does HTTPS provide security? *(Asked 22 times)*
17. Explain GET, POST, PUT, PATCH, DELETE, HEAD, and OPTIONS. *(Asked 40 times)*
18. What is the difference between PUT and POST? Can PUT be used to create a resource? *(Asked 16 times)*
19. What is the difference between PUT and PATCH? *(Asked 9 times)*
20. Can GET perform the same work as POST? Why is POST preferred for some operations? *(Asked 10 times)*
21. Can POST be used to fetch data, and can an API return a Boolean value? *(Asked 6 times)*
22. What is an API, and what is a REST API? *(Asked 90 times)*
23. What constraints and disadvantages does REST have? *(Asked 7 times)*
24. Why did you use or not use APIs in your application? *(Asked 10 times)*
25. Show the API endpoints and demonstrate all CRUD requests in Postman or another client. *(Asked 12 times)*
26. How can a server be accessed without a browser? *(Asked 3 times)*
27. Explain HTTP status codes 200, 201, 302, 400, 401, 403, 404, 500, and 501. *(Asked 20 times)*
28. What happens when a requested user or resource ID does not exist? *(Asked 4 times)*
29. What is the difference between a local API and a REST API? *(Asked 2 times)*
30. What alternatives to REST exist, and when would GraphQL be useful? *(Asked 2 times)*

## SQLAlchemy and database design

31. Is `SQLAlchemy()` a class or a function? *(Asked 8 times)*
32. What is `db.Model`, and why do model classes inherit from it? *(Asked 18 times)*
33. What is `db.relationship()`? *(Asked 8 times)*
34. What are `backref` and `back_populates`, and how are they different? *(Asked 51 times)*
35. What do `lazy`, `uselist`, `secondary`, and `uselist=False` mean in a relationship? *(Asked 23 times)*
36. What is cascading, and what does `cascade="all, delete-orphan"` do? *(Asked 34 times)*
37. What is referential integrity? *(Asked 4 times)*
38. Is a foreign key required to be unique? *(Asked 5 times)*
39. What are database constraints, including `NULL`, `NOT NULL`, `UNIQUE`, and foreign-key constraints? *(Asked 11 times)*
40. What is database normalization? Is your schema normalized? *(Asked 9 times)*
41. What are structured and unstructured databases? Give examples. *(Asked 13 times)*
42. What are the advantages and disadvantages of SQLite compared with MySQL or other databases? *(Asked 12 times)*
43. Why is SQL verbose? *(Asked 1 time)*
44. What is an index, why is it used, and how do you create a multi-column index in SQLAlchemy? *(Asked 5 times)*
45. What are clusters in a database? *(Asked 1 time)*
46. Explain SQL joins and the different join types. *(Asked 8 times)*
47. What are `GROUP BY`, `ORDER BY`, `HAVING`, subqueries, and aggregate functions? *(Asked 7 times)*
48. What is the difference between `LIKE`, `ILIKE`, and `UNLIKE`? *(Asked 6 times)*
49. What is the difference between a view and a table in SQL? *(Asked 2 times)*
50. What does `db.session.commit()` do? *(Asked 3 times)*
51. How do you add, update, delete, and query records using SQLAlchemy? *(Asked 12 times)*
52. Why does deleting all users fail when foreign-key constraints exist? *(Asked 3 times)*
53. What is the difference between `DELETE` and `TRUNCATE`? *(Asked 3 times)*
54. How can database models be changed safely after an application is in production? *(Asked 2 times)*

## Security, sessions, and validation

55. What is RBAC, and how did you implement it? *(Asked 22 times)*
56. How does a login-required or role-required decorator work? *(Asked 7 times)*
57. What security mechanism did you implement in your project? *(Asked 15 times)*
58. What is password hashing, and why should passwords not be stored in plain text? *(Asked 18 times)*
59. Why can the same password produce different hashes? *(Asked 2 times)*
60. What is SQL injection, and how does SQLAlchemy help prevent it? *(Asked 3 times)*
61. What is CSRF, and how can it be prevented? *(Asked 3 times)*
62. How long does a login session remain valid after the browser tab is closed? *(Asked 3 times)*
63. What types of storage are available in a browser? *(Asked 5 times)*
64. What is the difference between `request.args`, `request.form`, and direct dictionary access such as `request.form[]`? *(Asked 5 times)*
65. Why is backend validation mandatory even when frontend validation exists? *(Asked 9 times)*
66. How would you enforce unique usernames and handle the resulting exception? *(Asked 8 times)*
67. How would you restrict a username to ten characters on both frontend and backend? *(Asked 7 times)*
68. How would you validate a strong password with length, uppercase, lowercase, number, and special-character rules? *(Asked 12 times)*
69. How would you validate age before allowing access to an age-restricted product or service? *(Asked 3 times)*
70. How would you validate that an expiry date is not earlier than today? *(Asked 2 times)*

## HTML, CSS, JavaScript, and Jinja

71. What is the DOM, where does it exist, and which language manipulates it? *(Asked 31 times)*
72. How do you select an element by ID or class in JavaScript and CSS? *(Asked 9 times)*
73. What is the difference between HTML `id`, `class`, and `name` attributes? *(Asked 10 times)*
74. What is the difference between block and inline elements such as `div`, `p`, and `span`? *(Asked 4 times)*
75. What are inline, internal, and external CSS, and what is their precedence? *(Asked 34 times)*
76. Why can inline CSS override internal or external CSS? *(Asked 5 times)*
77. What are CSS selectors, and which symbols select an ID and a class? *(Asked 9 times)*
78. What is the difference between cell spacing and cell padding? *(Asked 13 times)*
79. What is responsive design, and how can an application be made responsive? *(Asked 5 times)*
80. What are JavaScript frameworks? Name some examples. *(Asked 12 times)*
81. What is AJAX? *(Asked 4 times)*
82. What is template inheritance versus class inheritance? *(Asked 3 times)*
83. How do you write a Jinja `for` loop, condition, variable expression, and filter? *(Asked 8 times)*
84. How are arrays or lists passed from Flask to Jinja templates? *(Asked 3 times)*
85. What is `enctype="multipart/form-data"`, and when is it required? *(Asked 2 times)*

## Python, Git, and testing

86. What is the difference between a list, tuple, dictionary, and array? *(Asked 18 times)*
87. What do mutable and immutable mean? *(Asked 5 times)*
88. What is a lambda function? *(Asked 5 times)*
89. What is a decorator? Show a simple decorator. *(Asked 9 times)*
90. What is inheritance in Python, and did you use it? *(Asked 10 times)*
91. What is a class, and what is an object? *(Asked 5 times)*
92. What are exceptions, and how do `try` and `except` work? *(Asked 7 times)*
93. What are the types of software testing, and which tests did you perform? *(Asked 8 times)*
94. What is algorithmic complexity, such as `O(n)`? *(Asked 2 times)*
95. How are dictionaries stored and iterated using keys, values, `items()`, or `enumerate()`? *(Asked 3 times)*
96. What is a namespace, and where is it used? *(Asked 2 times)*
97. What is the difference between Git, GitHub, and a VCS? *(Asked 14 times)*
98. Explain common Git operations such as init, add, commit, branch, merge, push, and pull. *(Asked 9 times)*

## Live coding and modification tasks

99. Write and run a Hello World Flask route. *(Asked 4 times)*
100. Build a form that accepts input and displays it on another page. *(Asked 4 times)*
101. Fetch all database records and display them using a Jinja loop. *(Asked 5 times)*
102. Add or repair search functionality and display the number of matching records. *(Asked 9 times)*
103. Exclude the admin account or unwanted results from search. *(Asked 2 times)*
104. Add a clear/reset button to the login form. *(Asked 9 times)*
105. Move, center, align, or swap a form, button, navbar, header, card, text, or graph. *(Asked 17 times)*
106. Change a page background, background image, navbar, button, font, card, or chart color. *(Asked 52 times)*
107. Convert cards to a table or change the page layout. *(Asked 4 times)*
108. Store a submitted name or title in uppercase in the backend. *(Asked 5 times)*
109. Add a new field to a form and model, then update the database. *(Asked 5 times)*
110. Add delete, delete-all, accept-all, or multi-select delete functionality. *(Asked 10 times)*
111. Add validation to prevent duplicate requests, campaigns, categories, users, or bookings. *(Asked 7 times)*
112. Implement a discount, promo code, buy-one-get-one offer, or purchase-threshold rule. *(Asked 6 times)*
113. Update stock or inventory correctly after cart and purchase operations. *(Asked 6 times)*
114. Change a bar chart to a pie chart, swap charts, or restrict chart colors. *(Asked 6 times)*
115. Add file or ID-proof upload functionality with appropriate validation. *(Asked 3 times)*
116. Add a flash message or error page for an invalid action. *(Asked 5 times)*
117. Debug a reported application error and explain how you would support the user. *(Asked 5 times)*
118. Modify the app so a value such as capacity, quantity, or price updates everywhere consistently. *(Asked 5 times)*

## Additional code-level questions reported in later batches

119. How does a "Remember me" login feature work? *(Asked 2 times)*
120. What is the CSS `:hover` pseudo-class, and how would you use it on a button? *(Asked 3 times)*
121. What do the HTML `required`, `value`, `action`, and `method` attributes do? *(Asked 4 times)*
122. What happens when the `method="POST"` attribute is removed from an HTML form? *(Asked 2 times)*
123. Can a browser form directly submit PUT or DELETE requests? *(Asked 2 times)*
124. What happens when `method="GET"` is used on a form? *(Asked 2 times)*
125. What do `query.all()`, `query.first()`, `query.get()`, and `abort()` do? *(Asked 3 times)*
126. How is a default value supplied to `request.args.get()`? *(Asked 1 time)*
127. What is `db.session.flush()`, and how is it different from `commit()`? *(Asked 1 time)*
128. What is `db.session.rollback()`, and when should it be used? *(Asked 1 time)*
129. What are Flask-Migrate and database migrations used for? *(Asked 2 times)*
130. How do you add a column to an existing SQL table or model? *(Asked 3 times)*
131. What are the ACID properties of a database transaction? *(Asked 1 time)*
132. What is the difference between hashing and encryption? *(Asked 5 times)*
133. How would you lock an account temporarily after three failed login attempts? *(Asked 1 time)*
134. What are `Enum`, `@staticmethod`, `UserMixin`, and `functools.wraps`, and why were they used? *(Asked 5 times)*
135. What are Flask-WTF and its forms used for? *(Asked 2 times)*
136. What is the difference between Flask application context and request context? *(Asked 1 time)*
137. What is the instance folder in Flask, and how is it created? *(Asked 1 time)*
138. Can the `templates` and `static` folders be renamed? If yes, how? *(Asked 1 time)*
139. What does `SQLALCHEMY_TRACK_MODIFICATIONS` do? *(Asked 1 time)*
140. What does `localhost` mean? *(Asked 1 time)*
141. Can a Flask route return a Boolean directly? *(Asked 7 times)*
142. What metadata is present in HTML? *(Asked 2 times)*
143. What does the CSS `rem` unit mean? *(Asked 1 time)*
144. What does `display: flex` do, and how can a section be limited to half the page width? *(Asked 2 times)*
145. What HTML tags are used to create a table? Create a three-column table. *(Asked 1 time)*
146. What are Pytest markers, and how are markers different from keyword selection? *(Asked 1 time)*
147. What is an assertion? *(Asked 1 time)*
148. What are cloud services? *(Asked 1 time)*
149. What is Flask-Login, and what do `LoginManager`, `UserMixin`, and `@login_required` provide? *(Asked 5 times)*
150. How can one user be assigned multiple roles in the data model? *(Asked 2 times)*
151. How do you round a partial parking hour upward using `math.ceil()`? *(Asked 1 time)*
152. Should parking-floor information be stored in the parking-lot table or a separate table? Why? *(Asked 1 time)*
153. What is the difference between a controller and an API endpoint? *(Asked 1 time)*
154. What are command-line arguments? *(Asked 1 time)*
155. What do SQLAlchemy's `or_()` and `ilike()` expressions do in search logic? *(Asked 2 times)*
156. What is a bad-request error, and why does it occur? *(Asked 2 times)*
157. What do HTTP status codes 304, 305, and 306 mean? *(Asked 3 times)*
158. What is blockchain technology? *(Asked 1 time)*
159. How are flash messages related to the Flask secret key? *(Asked 1 time)*
160. How can two simultaneous users or browsers be used to test role separation and booking conflicts? *(Asked 2 times)*
161. How would you prevent the same vehicle number, slot, or appointment from being booked twice? *(Asked 4 times)*
162. How would you sort services or requests alphabetically at query time? *(Asked 3 times)*
163. How would you build a form with a dropdown populated from database records? *(Asked 2 times)*
164. Given query parameters in a URL, how would you write an endpoint that returns them as JSON? *(Asked 1 time)*

---

## Share Your Viva Questions

After your viva, please share the questions asked by your examiner so this question bank can be kept up to date.

[Submit your viva questions through this Google Form](https://docs.google.com/forms/d/e/1FAIpQLScOeEe-1RRju08RNZybXVXceB1SMb1nBqtstKJmk-w6vmsIEQ/formResponse)

