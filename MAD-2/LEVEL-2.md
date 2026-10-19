# MAD-2 - Level 2 Viva Questions

> Duplicate wording has been merged. The count shows how many times the same question or task was reported in the supplied PDFs.

## Vue component communication, state, and routing

1. What are props, slots, and emits in Vue? *(Asked 9 times)*
2. How does a parent component communicate with a child component? *(Asked 3 times)*
3. How does a child component send data to its parent? *(Asked 3 times)*
4. How can data be passed from one component to another? *(Asked 3 times)*
5. Did you use slots? If yes, where and why? *(Asked 2 times)*
6. What is Vuex, and why is it used? *(Asked 8 times)*
7. Did you use Vuex? Why or why not? *(Asked 2 times)*
8. What are state, mutations, and actions in Vuex? *(Asked 4 times)*
9. What is the purpose of Vuex actions? *(Asked 2 times)*
10. What is the difference between a Vuex store and session/local storage? *(Asked 2 times)*
11. What are Vue lifecycle hooks, and which hooks did you use? *(Asked 4 times)*
12. What is the difference between `created` and `mounted`? *(Asked 3 times)*
13. How does `watch` work in Vue, and where did you use it? *(Asked 2 times)*
14. What are Vue routes, and how does Vue Router work? *(Asked 4 times)*
15. Which functions of `this.$router`, such as `push()` or `go()`, did you use? *(Asked 1 time)*
16. Why are there many Vue files in the project? *(Asked 1 time)*
17. What is the difference between components and pages? *(Asked 2 times)*
18. How can MAD-1 template inheritance be reproduced in Vue using components and slots? *(Asked 2 times)*

## JavaScript, browser, and frontend internals

19. What is the JavaScript event loop? *(Asked 1 time)*
20. What are async and await? *(Asked 2 times)*
21. What is the difference between AJAX and Fetch? *(Asked 2 times)*
22. What is CORS in JavaScript, and why can a browser block a request? *(Asked 4 times)*
23. What are server-sent events? *(Asked 1 time)*
24. What is an opaque request or opaque response? *(Asked 1 time)*
25. How does the frontend catch and handle a non-success HTTP response such as 400? *(Asked 2 times)*
26. What styling approach did you use in the project? *(Asked 2 times)*
27. Why does inline CSS receive higher precedence? *(Asked 2 times)*
28. Can a page be made responsive without writing custom CSS? *(Asked 1 time)*

## Flask, Python, and application architecture

29. What is `Flask(__name__)`, and can the `__name__` argument be removed? *(Asked 2 times)*
30. What is WSGI? *(Asked 2 times)*
31. What is a Flask Blueprint? *(Asked 2 times)*
32. What is the need for a virtual environment? *(Asked 2 times)*
33. Would the current stack be efficient at a large scale? *(Asked 2 times)*
34. What is scaling, and how would you scale the project for more than 10,000 users? *(Asked 3 times)*
35. What are horizontal and vertical scaling? *(Asked 2 times)*
36. What is load balancing? *(Asked 1 time)*
37. How can the server be accessed without a browser or URL bar? *(Asked 2 times)*
38. What are Python decorators? *(Asked 7 times)*
39. Write a Hello World decorator. *(Asked 2 times)*
40. What are dunder methods? *(Asked 2 times)*
41. What is `__repr__` used for in a model? *(Asked 2 times)*
42. What is the difference between `__repr__` and `__str__`? *(Asked 2 times)*
43. What does `if __name__ == "__main__"` do? *(Asked 1 time)*
44. What is a dataclass? *(Asked 2 times)*
45. What is the difference between `is` and `==`, and is there a speed difference? *(Asked 1 time)*
46. What are async and await in Python? *(Asked 1 time)*
47. What is exception handling? Show it in the code. *(Asked 6 times)*
48. What are the different types of Python exceptions? *(Asked 2 times)*
49. What is the base class of Python exceptions? *(Asked 2 times)*

## REST APIs, HTTP, and serialization

50. What is a webhook? *(Asked 4 times)*
51. What is the difference between a webhook and an API? *(Asked 1 time)*
52. What is the difference between a webhook and a WebSocket? *(Asked 2 times)*
53. What is the difference between POST and PUT? *(Asked 2 times)*
54. What is the difference between PUT and PATCH? *(Asked 3 times)*
55. What is the difference between POST, PUT, and PATCH? *(Asked 1 time)*
56. Why is POST not idempotent? *(Asked 1 time)*
57. Can POST be used instead of PUT? *(Asked 2 times)*
58. How is an authentication token sent in an API header? *(Asked 1 time)*
59. What is the difference between JSON and `jsonify()`? *(Asked 3 times)*
60. What is the difference between `jsonify()`, marshaling, the `json` package, and `json.dumps()`? *(Asked 3 times)*
61. What is serialization with respect to models? *(Asked 1 time)*
62. Explain HTTP status codes 400, 401, 403, and 404. *(Asked 2 times)*
63. Explain the complete process of creating a REST API. *(Asked 1 time)*
64. Did you use a local API or a REST API? *(Asked 1 time)*

## Authentication and security

65. What authentication mechanism did you use: JWT or Flask-Security? *(Asked 3 times)*
66. Explain how JWT works in your code and how a JWT is built. *(Asked 7 times)*
67. Why did you choose token-based authentication over session-based authentication? *(Asked 2 times)*
68. Where is the authentication token stored? *(Asked 1 time)*
69. What is the difference between a session and a token? *(Asked 2 times)*
70. What is the difference between a session and a cookie? *(Asked 2 times)*
71. What is Flask-Security? *(Asked 2 times)*
72. How do `@auth_required` and `@role_required` work? *(Asked 3 times)*
73. Can the order of authentication and role decorators be swapped? *(Asked 2 times)*
74. What is CSRF? *(Asked 2 times)*
75. What is a man-in-the-middle attack? *(Asked 2 times)*
76. What is SQL injection? *(Asked 2 times)*
77. What is a rainbow table? *(Asked 2 times)*
78. What was the default password-hashing algorithm in MAD-1? *(Asked 2 times)*
79. What is SHA-256, and can it be decrypted? *(Asked 2 times)*
80. Why can a password be visible in the browser's network payload, and how should it be protected? *(Asked 2 times)*
81. What is the difference between security and privacy? *(Asked 3 times)*
82. What is a denial-of-service attack? *(Asked 2 times)*

## SQLAlchemy, database design, and SQL

83. What are `db.Model` and `db.relationship()`? *(Asked 3 times)*
84. What is the difference between `backref` and `back_populates`? *(Asked 2 times)*
85. What does `lazy="dynamic"` mean? *(Asked 2 times)*
86. What does `cascade="all, delete-orphan"` mean? *(Asked 4 times)*
87. What is lazy loading? *(Asked 5 times)*
88. What is the difference between eager loading and lazy loading? *(Asked 1 time)*
89. If the database changes from SQLite to PostgreSQL, what code or configuration must change? *(Asked 3 times)*
90. Which databases does SQLAlchemy support? *(Asked 2 times)*
91. Can database models be changed while the application is in production? How? *(Asked 1 time)*
92. Explain one-to-one, one-to-many, and many-to-many relationships. *(Asked 2 times)*
93. Can a primary key be replaced with `UNIQUE + NOT NULL + AUTO INCREMENT`? *(Asked 2 times)*
94. What is a candidate key? *(Asked 1 time)*
95. What is `ON DELETE CASCADE`, and what happens without it? *(Asked 3 times)*
96. What happens to referencing records when a parent record is deleted? *(Asked 1 time)*
97. After deleting an auto-incremented row, what value will the next inserted row receive? *(Asked 1 time)*
98. What is an index, why is it useful, and how do you create a two-column index in SQLAlchemy? *(Asked 2 times)*
99. Explain joins, subqueries, aggregate functions, `GROUP BY`, and `HAVING`. *(Asked 3 times)*
100. What is the difference between `DELETE` and `TRUNCATE`? *(Asked 1 time)*
101. What is the difference between `LIKE` and `ILIKE`? *(Asked 1 time)*
102. In `db.String(128)`, what does `128` mean? *(Asked 1 time)*
103. What is the difference between `String` and `Text` database fields? *(Asked 1 time)*
104. What happens when a string is inserted into an integer field or vice versa? *(Asked 2 times)*
105. Does inserting the wrong data type into an empty SQLite table still raise an error? *(Asked 1 time)*
106. Why was a separate association table used for user roles? *(Asked 1 time)*
107. What are SQL constraints? *(Asked 2 times)*
108. Can Microsoft SQL Server connect through SQLAlchemy? *(Asked 1 time)*
109. What are the advantages of relational databases? *(Asked 2 times)*
110. What is a left join? *(Asked 1 time)*

## Caching, Redis, Celery, and messaging

111. What is memoization? *(Asked 3 times)*
112. What is the difference between memoization and caching? *(Asked 3 times)*
113. Where did you implement caching, and can you show the code? *(Asked 3 times)*
114. Why use Redis instead of a normal database? *(Asked 2 times)*
115. Where does Redis store cached data? *(Asked 1 time)*
116. What is the difference between Memcached and Redis? *(Asked 2 times)*
117. What is the difference between `cache.memoize` and `cache.cached`? *(Asked 2 times)*
118. When should a cache be cleared or invalidated? *(Asked 1 time)*
119. What are the components of Celery? *(Asked 3 times)*
120. What are Celery Beat and a Celery worker, and how are they different? *(Asked 4 times)*
121. What does a Celery worker do, and how does it work? *(Asked 2 times)*
122. Where is Celery configured in the project? *(Asked 1 time)*
123. Show the code where Celery is implemented. *(Asked 2 times)*
124. How can a Celery task be stopped without using the terminal? *(Asked 2 times)*
125. How can Celery tasks be prioritized? *(Asked 2 times)*
126. What is a cron job? *(Asked 2 times)*
127. Explain the Crontab expression used in the Celery schedule. *(Asked 2 times)*
128. Schedule a Celery task to run at a specific time, such as 5:20 PM. *(Asked 2 times)*
129. What are task queues and message queues? *(Asked 3 times)*
130. What is a message broker? *(Asked 1 time)*
131. What is the difference between publish/subscribe and point-to-point messaging? *(Asked 3 times)*
132. How should a long-running Celery task be validated if the user logs out or the token expires? *(Asked 1 time)*
133. What is SMTP, and where is it used? *(Asked 1 time)*

## Advanced project and live-coding tasks

134. How would you send an email when a new show, resource, or event is created? *(Asked 1 time)*
135. Implement a favorite feature, such as marking a theatre as favorite. *(Asked 1 time)*
136. Add a new column, validation rule, or API without breaking existing data. *(Asked 2 times)*
137. Fix overbooking, negative values, duplicate names, or invalid dates. *(Asked 2 times)*
138. Implement or modify frontend search suggestions. *(Asked 1 time)*
139. Change a card layout to a table or modify the frontend component structure. *(Asked 1 time)*
140. Explain how charts are rendered and modify their colors or datasets. *(Asked 1 time)*
141. Export venue, user, or report data from the application. *(Asked 1 time)*
142. Explain how a backend route returns data to Vue and how the response is handled. *(Asked 2 times)*
143. Implement a feature requested during the viva and explain every changed line. *(Asked 3 times)*
144. What is Axios, and how is it different from using the Fetch API? *(Asked 1 time)*
145. What browser storage options are available, and when should each be used? *(Asked 2 times)*
146. What is `fs_uniquifier` in Flask-Security, and why is it required? *(Asked 1 time)*
147. What are Vue plugins, and how are they registered or used? *(Asked 1 time)*
148. How is Chart.js integrated with Vue, and how is chart data updated reactively? *(Asked 2 times)*
149. How are arrays returned by Flask consumed and rendered in Vue? *(Asked 1 time)*
150. Do all project libraries support horizontal scaling, and what state must be externalized? *(Asked 1 time)*
151. How would you prevent an expired JWT from invalidating a long-running export or background job? *(Asked 1 time)*

---

## Share Your Viva Questions

After your viva, please share the questions asked by your examiner so this question bank can be kept up to date.

<a href="https://docs.google.com/forms/d/e/1FAIpQLScOeEe-1RRju08RNZybXVXceB1SMb1nBqtstKJmk-w6vmsIEQ/formResponse" target="_blank" rel="noopener noreferrer">Submit your viva questions through this Google Form</a>
