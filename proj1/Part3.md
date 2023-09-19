Progress is a never-ending journey characterized by constant innovation, intelligent reflection, and unrelenting improvement in the dynamic world of software development. Our extensive analysis of both the front end and backend of Project1 exposed us to a variety of difficulties and provided us with insightful information about possible weaknesses.

> Recipe Recommender is a web application built using the MERN (MongoDB, Express.js, React.js, and Node.js) Stack. The main motto of the website is to allow users to add food recipes and ultimately get recipe suggestions based on the available ingredients. [Project Zip](https://github.com/Shubh-Nisar/CSC510-G2/blob/main/proj1/Recipe_Recommender.zip)

### Frontend Shortcomings

#### 1. Heavy and Unorganized User Interface

<ul>
  <li>Our first challenge in frontend development was the heavy and disorganized user interface (UI), hindering user navigation and comprehension.</li>

  <li>For Project2, we plan to implement React Router for routing, dividing the application into separate pages for a more organized and user-friendly experience. This approach will streamline navigation and enhance user comprehension.</li>
</ul>

#### 2. Inconsistent Code Structure

<ul>
  <li>Inconsistent code structure in the frontend hindered maintenance and updates due to scattered components and pages.</li>

  <li>To address this, we commit to creating a 'pages' folder in Project2, where each route/page will have its own JavaScript (or JSX) file. This structural change will improve code organization, making it easier to locate and update components.</li>
</ul>

#### 3. Non-Uniform File Naming Convention

<ul>
  <li>Inconsistent file naming conventions caused confusion within the frontend codebase.</li>

  <li>To ensure consistency in Project2, we will adhere strictly to a standardized file naming convention. This will eliminate naming discrepancies and promote smoother collaboration.</li>
</ul>

#### 4. ES5 vs. ES6 Compatibility

<ul>
  <li>The mixture of ES5 and ES6 standards in our frontend codebase posed challenges in terms of code maintenance and collaboration.</li>

  <li>For Project2, we commit to using the ES6 standard exclusively to ensure consistency and compatibility among team members.</li>
</ul>

#### 5. Missing Iconography

<ul>
  <li>The absence of icons impacted user experience and User Interface aesthetics.</li>

  <li>In Project2, we plan to incorporate a UI library that includes icons to enhance the visual appeal and interactivity of our website.</li>
</ul>

### Backend Challenges

#### 1. Disorganized File System

<ul>
  <li>The disorganized backend file system, including routes, controllers, and middleware, hindered code maintenance. It makes it difficult for new developers to understand the codebase.</li>

  <li>In Project2, we will restructure the backend file system to provide clear separation of routes, controllers, and middleware. This will enhance code readability and maintainability.</li>
</ul>

#### 2. Inconsistent File Naming

<ul>
  <li>Inconsistent file naming conventions in the backend codebase caused delays and confusion.</li>

  <li>In Project2, we will establish a consistent file naming convention to streamline development and make file locations more intuitive.</li>
</ul>

#### 3. Nodemailer Compatibility Issue

<ul>
  <li>Nodemailer has deprecated the use of Gmail accounts for sending emails and now mandates the use of a company email address for this purpose.</li>

  <li>For Project2, we will choose a more robust email service or library that remains compatible with commonly used email providers, ensuring uninterrupted email functionality.</li>
</ul>

#### 4. Insecure Password Handling

<ul>
  <li>Storing unencoded passwords in the database posed a significant security risk. Open passwords in a database are vulnerable to database injection attacks leading to loss of private user data. </li>

  <li>To enhance security in Project2, we will implement password encryption before storing user credentials, safeguarding sensitive information.</li>
</ul>

#### 5. Lack of Database Connection Separation

<ul>
  <li>Insufficient separation of database connection concerns in the backend led to potential code redundancy and maintenance challenges.</li>

  <li>In Project2, we will adopt a structured approach to database connection management, isolating it from other application logic for improved code structure and maintainability.</li>
</ul>

#### 6. File Format Issues

<ul>
  <li>File format inconsistencies in the backend created compatibility problems.</li>

  <li>In Project2, we will validate and standardize file formats thoroughly to ensure compatibility across various systems and environments.</li>
</ul>

#### 7. Security Vulnerability: Open Password

<ul>
<li>Exposing passwords in plaintext within the code was a critical security flaw.</li>
</ul>

#### 8. Improperly Coded Chai Tests

<ul>
  <li>Inadequate Chai tests compromised the reliability of our backend testing suite.</li>

  <li>To address this, we commit to improving testing practices in Project2 by investing more time in writing comprehensive and well-structured Chai tests.</li>

  <li>In Project2, we will implement best practices to secure sensitive information, ensuring that passwords are never stored in plain text within the codebase.</li>
</ul>

### Conclusion

In conclusion, our journey through the development of Project1's front end and back end has provided valuable lessons and opportunities for improvement. By addressing these challenges and implementing our proposed solutions in Project2, we aim to enhance code quality, maintainability, and security while delivering a more user-friendly and efficient application, thereby enforcing the solutions to the shortcomings mentioned above. Our next phase will improve user engagement and promote code maintainability and collaboration by standardizing many programming principles. The lessons learned above will serve as our guide as we move forward to the next phase of our project.
