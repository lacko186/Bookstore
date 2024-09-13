

<style>
.page-break { page-break-after: always; }
</style>
<p style = "font-size: 14px; text-align: center">A project report on</p>
<p style = "font-size: 14px; text-align: center ">BCA-CC-606</p>
<p style = "font-size: 26px; text-align: center ">“Bookstore Management System”</p>
<p style = "font-size: 14px; text-align: center">Submitted to  <span style="font-weight: bold"> Smt. K.B. Parekh College of Computer Science-Mahuva </span></p>
<p style = "font-size: 14px; text-align: center ">(Affiliated to Maharaja Krishnakumarsinhji Bhavnagar University)</p>

<center><img style="width: 200px; " src="kep1.png"></center>
<p style = "font-size: 14px; text-align: center ">in partial fulfillment for the award of degree of</p>
<p style = "font-size: 28px; text-align: center ">BACHELOR<br>
OF<br>
COMPUTER APPLICATIONS</p>
<p style = "font-size: 14px; text-align: center">Submitted by</p>
<p style = "font-size: 14px; text-align: center; font-weight: bold">MAKWANA DHAVAL N. (BCA SEMESTER-6 SEAT NO: 21260256)<br>
BARAIYA KUMAR K. (BCA SEMESTER-6 SEAT NO: 21260254)</p>
<p style = "font-size: 14px; text-align: center">Guided by</p>
<p style = "font-size: 14px; text-align: center;font-weight: bold">ASHSISH PANDYA</p>
<p style = "font-size: 12px; text-align: center">Assistant Professor<br>
Smt. K.B. Parekh College of Computer Science-Mahuva</p>

<p style = "font-size: 14px; text-align: center; font-weight: bold">March - 2019

--- 

<center><img style ="width: 250px" src ="kep2.png"></center>

## <center> "Smt.K.B.Parekh College of Computer Science Mahuva-364290 </center>
### <center>(Affiliated to Maharaja Krishnakumarsinhji Bhavnagar University)</center>

<p style="text-align: right"><b>Date:</b> 15/03/2019</p>


## <p style ="text-align:center">TO WHOMSOEVER IT MAY CONCERN</p>

This is to certify that the Student **Makwana Dhaval** and **Baraiya Kumar** of Smt.K.B.Parekh College of Computer Science Mahuva has satisfactorily completed his/her Project **BOOKSTORE MANAGEMENT SYSTEM** during the period December 2019 to March 2019 in the partial fulfillment of BCA-CC-606.<br><br><br><br><br><br>



 
##### <span style="text-align: left">Name & Signature of Project Guide:</span>       <span style="text-align:right"> Signature and Seal of Principal.</span>
<br><br><br><br><br><br><br>

 







**Address:**  Smt.K.B.Parekh College of Computer Science, Prabhat Nagar Road, Near Parekh College Campus, Cooperative Housing Society, Mahuva, Gujarat 364290 Ph-02844/228332 Email:kbpbcamahuva2000@gmail.com

---

<h2 style ="text-align: center">ACKNOWLEGEMENT</h2>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;We have taken efforts in this project. However, it would not have been possible without the kind support and help of our Faculties. We would like to extend my sincere thanks to all of them.<br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;We are highly indebted to K. B. Parekh College of Computer Science, Mahuva for their guidance and constant supervision as well as for providing necessary information regarding the project & also for their support in completing the project.<br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;We would like to express my gratitude towards my parents & member of KBP for their kind co-operation and encouragement which help us in completion of this project. Last but not least, many thanks go to the head of the project, Mr. Ashsish Pandya whose have invested his full effort in guiding the team in achieving the goal. We have to appreciate the guidance given by other supervisor as well as the panels especially in our project presentation that has improved our presentation skills thanks to their comment and advices.<br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;We would like to express our special gratitude and thanks to all above mentioned people for giving us such attention and time. Our thanks and appreciations also go to our colleague in developing the project and people who have willingly helped us out with their abilities.<bry

---
 
<h2 style ="text-align: center">ABSTRACT</h2>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Bookstore Management System is basically used to build an web application program which help people to find and buy latest design of Books with different categories like Biography, Programming, Management, etc. It is useful in the way that it makes an easier way to buy Personal Bookstore. <br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Today most of the book shop is useful for shopping site. The admin have lots of paper work and they are using desktop, spread sheet like MS Excel application to manage data in soft copy about user record. In this proposed Bookstore System it will run in server and user can handle whole the registration activities.<br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;This application maintains the centralized database so that any changes done at a location reflects immediately. This is an online tool so more than one user can login into system and use the tool simultaneously.<br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The aim of this application is to reduce the manual effort needed to manage transactions and historical data used in various gods owns. Also this application provides an interface to users to view the details And Design about Bookstore.
---












<h2 style = "text-align:center">Table of Contents</h2>

### INTRODUCTION
- 1.1. [Project Background](#project-background) - 9
- 1.2. [Objectives of Project](#objectives-of-project) - 9
- 1.3. [Purpose of Project](#purpose-of-project) - 9
- 1.4. [Scope of Project](#scope-of-project) - 10
- 1.5. [Applicability of Project](#applicability-of-project) - 10

### REQUIREMENT AND ANALYSIS
- 2.1. [Problem Statement](#problem-statement) - 12
- 2.2. [Requirement Specifications](#requirement-specifications) - 12
- 2.3. [Hardware Requirement](#hardware-requirement) - 13
- 2.4. [Software Requirement](#software-requirement) - 13
- 2.5. [Planning and Scheduling](#planning-and-scheduling) - 14

### SYSTEM DESIGN
- 3.1. [Overall System Design Using Design Tools](#overall-system-design-using-design-tools) - 24
- 3.2. [Data Dictionary](#data-dictionary) - 37
- 3.3. [Input/Output Design](#inputoutput-design) - 41

### TESTING AND IMPLEMENTATION
- 4.1. [Testing Approach Used](#testing-approach-used) - 57
- 4.2. [Test Cases](#test-cases) - 59
- 4.3. [Implementation Approaches](#implementation-approaches) - 63

### CONCLUSION
- 5.1. [Limitation of System](#limitation-of-system) - 65
- 5.2. [Future Scope of System](#future-scope-of-system) - 66
- 5.3. [Bibliography](#bibliography) - 66




 
<h2 style = "text-align:center">Contents of figures</h2>


<table>
    <thead>
        <tr>
            <th>Figure No</th>
            <th>Figure Name</th>
            <th>Page No</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1</td>
            <td>Planning and Scheduling</td>
            <td>14</td>
        </tr>
        <tr>
            <td>2</td>
            <td>Spiral Model</td>
            <td>20</td>
        </tr>
        <tr>
            <td>3</td>
            <td>Data Flow Diagram Symbols</td>
            <td>25</td>
        </tr>
        <tr>
            <td>4</td>
            <td>0 Level Data Flow Diagram</td>
            <td>25</td>
        </tr>
        <tr>
            <td>5</td>
            <td>1st Level Data Flow Diagram</td>
            <td>26</td>
        </tr>
        <tr>
            <td>6</td>
            <td>BMS Flowchart Diagram</td>
            <td>26</td>
        </tr>
        <tr>
            <td>7</td>
            <td>User Flow Diagram</td>
            <td>27</td>
        </tr>
        <tr>
            <td>8</td>
            <td>Use Case Diagram Symbols</td>
            <td>28</td>
        </tr>
        <tr>
            <td>9</td>
            <td>User Use Case Diagram</td>
            <td>29</td>
        </tr>
        <tr>
            <td>10</td>
            <td>BMS Use Case Diagram</td>
            <td>30</td>
        </tr>
        <tr>
            <td>11</td>
            <td>Activity Diagram Symbols</td>
            <td>32</td>
        </tr>
        <tr>
            <td>12</td>
            <td>User Activity Diagram</td>
            <td>33</td>
        </tr>
        <tr>
            <td>13</td>
            <td>Login System Activity Diagram</td>
            <td>34</td>
        </tr>
        <tr>
            <td>14</td>
            <td>E-R Diagram Symbols</td>
            <td>35</td>
        </tr>
        <tr>
            <td>15</td>
            <td>E-R Diagram for Bookstore Management System</td>
            <td>36</td>
        </tr>
        <tr>
            <td>16</td>
            <td>BMS Home Page</td>
            <td>41</td>
        </tr>
        <tr>
            <td>17</td>
            <td>BMS Selected Category</td>
            <td>42</td>
        </tr>
        <tr>
            <td>18</td>
            <td>BMS Book Details</td>
            <td>43</td>
        </tr>
        <tr>
            <td>19</td>
            <td>BMS Login Page</td>
            <td>44</td>
        </tr>
        <tr>
            <td>20</td>
            <td>BMS Register Page</td>
            <td>45</td>
        </tr>
        <tr>
            <td>21</td>
            <td>BMS Contact Us Page</td>
            <td>46</td>
        </tr>
        <tr>
            <td>22</td>
            <td>BMS Cart Page Viewers</td>
            <td>46</td>
        </tr>
        <tr>
            <td>23</td>
            <td>BMS Order Page</td>
            <td>47</td>
        </tr>
        <tr>
            <td>24</td>
            <td>Logged in Home Page</td>
            <td>48</td>
        </tr>
        <tr>
            <td>25</td>
            <td>BMS Users Book Details</td>
            <td>49</td>
        </tr>
        <tr>
            <td>26</td>
            <td>BMS Users Cart Page</td>
            <td>50</td>
        </tr>
        <tr>
            <td>27</td>
            <td>BMS Search Books</td>
            <td>51</td>
        </tr>
        <tr>
            <td>28</td>
            <td>BMS Admin Login Page</td>
            <td>51</td>
        </tr>
        <tr>
            <td>29</td>
            <td>BMS Admin Home Page</td>
            <td>52</td>
        </tr>
        <tr>
            <td>30</td>
            <td>BMS Add New Category</td>
            <td>52</td>
        </tr>
        <tr>
            <td>31</td>
            <td>BMS View Category</td>
            <td>53</td>
        </tr>
        <tr>
            <td>32</td>
            <td>BMS Add New Books</td>
            <td>53</td>
        </tr>
        <tr>
            <td>33</td>
            <td>BMS View Books</td>
            <td>54</td>
        </tr>
        <tr>
            <td>34</td>
            <td>BMS Contacted List Books</td>
            <td>54</td>
        </tr>
        <tr>
            <td>35</td>
            <td>BMS Users List</td>
            <td>55</td>
        </tr>
        <tr>
            <td>36</td>
            <td>BMS Forget Password Page</td>
            <td>55</td>
        </tr>
        <tr>
            <td>37</td>
            <td>Black Box Testing</td>
            <td>57</td>
        </tr>
                <tr>
            <td>38</td>
            <td>Gray Box Testing</td>
            <td>59</td>
        </tr>
        <tr>
            <td>39</td>
            <td>Test Cases 1</td>
            <td>60</td>
        </tr>
        <tr>
            <td>40</td>
            <td>Test Cases 2</td>
            <td>61</td>
        </tr>
        <tr>
            <td>41</td>
            <td>Test Cases 3</td>
            <td>61</td>
        </tr>
        <tr>
            <td>42</td>
            <td>Test Cases 4</td>
            <td>62</td>
        </tr>
    </tbody>
</table>

	














---
<br><br><br><br><br><br>
# <p style="text-align: right">Chapter 1 <br> <u>Introduction</u></p>
<br><br><br><br><br><br>
---
 
## 1.1	Project Background
*	This Software allows the Admin to store the book details and the customer details.
*	Easier access to information like customer information and  availability.
*	Provide facility of storing data to reduce the paper work.
*	In Bookstore Management System Users can by a book and Admin shows their name and other background of the user.
*	A  new idea about Project how Bookstore Management System works.
For make a system computerized.

## 1.2	Objectives of Project
*	To reduce the paper work.To make computerized system.
*	Increase operational speed.Faster searching as well as accuracy.
*	Large storage of data using database.
*	Manual process of vehicle purchase and sales on finance and cash and generate reports of model wise, weekly, monthly ,annual progress is so difficult so this project make is easier.
*	Speed and faster information retrieval.

## 1.3 Purpose of Project
*	The main purpose of Book-store Management System is to focused on the solution of all the problems related to the paper work from the different reasons.
*	It provides a facility to handle all the activities at one place. With the help of this application, admin can perform different kind of operations at the same time and place.
*	Bookstore management System has an ability to keep the records safe related to Books.
*	We provide the best service in our website or focuses on user choice. We will improve new feat user can easily understand and trust our system.

## 1.4 Scope of Project
*	The intentions of the system are to reduce over-time pay and increase the number of records that can be treated accurately; Requirements statements in this document are both functional and non-functional.
*	Correct and Accurate Searching that provides the result by applying search operation.
*	Customers can book a book with just few clicks.
*	Give flexibility admin to use database effectively and utilize the word, not pad and calculator Unambiguous and understandable by all level facilities effectively.
*	Unambiguous and understandable by all level.

## 1.5 Applicability of Project:
*	For customers who want to buy books at anywhere or anytime.
*	Admin applicable for insert books, list of books.
*	Database is used for store and fetch data from or to the database so both users and admin can fetch or read data.

 




---
<br><br><br><br><br><br>

# <p style="text-align: right">Chapter 2 <br> <u>Requirement And Analysis</u>

 <br><br><br><br><br><br>
 
---
## 2.1 Problem Statement
*	So much Paper work
*	Process is much time consuming
*	Extra expense in paper work 
*	Large storage of data
*	Manual process of Vehicle purchase and sales on finance and cash and generate reports of model wise, weekly, monthly, annual progress is so difficulties.
*	Speed and faster information retrieval.
*	Accuracy and consistency in manual system is less.
*	Personal delay.
*	In manual system it is tedious task to search a particular record later after.
*	Increase the staff in test taken place and wasting of their precious time.


## 2.2 Requirement Specification
 As per the System Requirements it contains two (2) Modules:
1)  Admin
2)  Client

### <center><p>Functionalities of Admin:</p></center>
*	This Module includes the mainly following tasks:
*	Entry of Category.
*	Category List.
*	Add a New Book.
*	View Book.
*	View Message which Send by Client.

### <center><p>Functionalities of Client: </p></center>
*	This Module includes the mainly following tasks:
*	View Books.
*	Add books to Cart. 
*	Search Books.
*	View or Add items in Cart.

## 2.3	Hardware requirement
*	System type 32 bit Operating System.
*	Windows 7/8/8.1/10
*	Linux  Ubuntu / Light ubuntu
*	Mac OS
*	350MB RAM

## 2.4	 Software Requirement
*	Wamp Server
*	MySQL
*	Browser
*	PHPMyAdmin
<br>**Client Side Tools**
*	&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Processor:** PC with a Dual core processor or above is* Recommended: 2.20 GHz processor.
*	&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**RAM:** 512 MB or onwards Recommended.
*	&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Hard Disk:** 45 MB of available space required on system drive of available or more.  
*	&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Operating System:** Windows or open source 32/64 bit operating system, or later versions.  Browser Mozilla Firefox 2.0 /Internet Explorer 8.0 Onwards / Google* Chrome.

## 2.5	Planning and scheduling

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Different amount of time may be required for each stage in the project cycle, depending on the particulars of the key aspect of the project cycle seem to recur during development process. The information obtained during the requirement gathering of pre-development phase provides the impetus for the requirement analysis and the information is further used in the design phase.

### Planning and Scheduling:-
<table>
    <thead>
        <tr>
            <th>ID</th>
            <th>Task Name</th>
            <th>Start/Finish</th>
            <th>Duration</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1</td>
            <td>Analysis</td>
            <td>25/12/2018 to 01/01/2019</td>
            <td>8 Days</td>
        </tr>
        <tr>
            <td>2</td>
            <td>Design</td>
            <td>01/01/2019 to 09/01/2019</td>
            <td>9 Days</td>
        </tr>
        <tr>
            <td>3</td>
            <td>Coding</td>
            <td>10/01/2019 to 08/02/2019</td>
            <td>4 Weeks</td>
        </tr>
        <tr>
            <td>4</td>
            <td>Implementation</td>
            <td>08/02/2019 to 12/02/2019</td>
            <td>5 Days</td>
        </tr>
        <tr>
            <td>5</td>
            <td>Testing</td>
            <td>12/02/2019 to 17/02/2019</td>
            <td>6 Days</td>
        </tr>
        <tr>
            <td>6</td>
            <td>Documentation</td>
            <td>18/02/2019 to 10/03/2019</td>
            <td>3 Weeks</td>
        </tr>
    </tbody>
</table>

### <center>(Figure 1 : Planning and Sheduling)<center>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The above schedule specifies the estimated time that will be required in various software development phases, considering all situational factors. Team members are technically ready accepting few days training on to get the Technology Awareness. Thus, according to calculation, it is feasible to build such solution in time. **“The schedule will be revised at the end of each phase and updated as required”.**

---
## <center>Brief overview of the technology</center>
### Front End - HTML, CSS , BOOTSTRAP
#### 1.	HTML
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;HTML stands for HYPER TEXT MARKUP LANGUAGE, which is most widely used language on web to develop web pages. HTML refers to the way in which Web pages (HTML documents) are linked together. Thus, the link available on a web page is called Hypertext.
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;HTML was created by Berners-Lee in late 1991 but “HTML 2.0” was the first standard HTML specification which was published in 1995. HTML 4.01 was a major version of HTML and it was published in late 1999. Though HTML 4.01 version is widely used but currently we are having HTML-5 version which is an extension to HTML 4.01, and this version was published in 2012.
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;As its name suggests, HTML is a Mark-up Language which means you use HTML to simply “mark-up” a text document with tags that tells a web browser how to structure it to display.
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Originally, HTML was develop with the intent of defining the structure of documents like heading, paragraph, lists, and so forth to facilitate the sharing of scientific information between researchers. Now, HTML is being widely used to format web pages with the help of different tags available in HTML.

#### 2.	CSS
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Cascading Style Sheet is a style sheet language used for describing the presentation of a document written in a markup language Although most often used to set the visual style of web page and user interfaces written in HTML and XHTML, the language can be applied to any XML document, including plain XML, SVG and XUL, and is applicable to rendering in speech, or on other media. Along with HTML and JavaScript, CSS is a cornerstone technology used by most websites to create visually engaging webpages, user interfaces for web applications, and user interfaces for many mobile applications.

---

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;CSS is designed primarily to enable the separation of document content from document presentation, including aspects such as the layout, colors, and fonts. This separation can improve content accessibility, provide more flexibility and control in the specification of presentation characteristics, enable multiple HTML pages to share formatting by specifying the relevant CSS in a separate .css file, and reduce complexity and repetition in the structural content.
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The CSS specifications are maintained by the World Wide Web Consortium (W3C). Internet media type (MIME type) text/css is registered for use with CSS by RFC 2318 (March 1998). The W3C operates a free CSS validation service for CSS documents 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;CSS has a simple syntax and uses a number of English keywords to specify the names of various style properties. A style sheet consists of a list of rules. Each rule or rule-set consists of one or more selectors, and a declaration block.

#### 3.	BOOTSTRAP
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Bootstrap is a free and open-source, front-end web frame work for designing websites and web applications. It contains HTML- and CSS-based design templates for typography, forms, buttons, navigation and other interface components, as well as optional JavaScript extensions. Unlike many web frameworks, it concerns itself with front-end development only.
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Bootstrap is modular and consists of a series of less stylesheets that implement the various components of the toolkit. These stylesheets are generally compiled into a bundle and included in web pages, but individual components can be included or removed. Bootstrap provides a number of configuration variables that control things such as color and padding of various components.
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Since Bootstrap 2, the Bootstrap documentation has included a customization wizard which generates a customized version of Bootstrap based on the requested components and various settings.
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;As of Bootstrap 4, is used instead of less for the stylesheets. Each Bootstrap component consists of an HTML structure, CSS declarations, and in some cases accompanying JavaScript code.


#### Back End - PHP, MySQL
##### 1.	PHP
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The PHP Hypertext Pre-processor (PHP) is a programming language that allows web developers to create dynamic content that interacts with databases. PHP is basically used for developing web based software applications. This tutorial helps you to build your base with PHP. PHP started out as a small open source project that evolved as more and more people found out how useful it was. Rasmus Lerdorf unleashed the first version of PHP way back in 1994.
*	PHP is a recursive acronym for "PHP: Hypertext Preprocessor".
*	PHP is a server side scripting language that is embedded in HTML. It is used to manage dynamic content, databases, session tracking, even build entire e-commerce sites.
*	It is integrated with a number of popular databases, including MySQL, Postgre SQL, Oracle, Sybase, Informix, and Microsoft SQL Server.
*	PHP is pleasingly zippy in its execution, especially when compiled as an Apache module on the Unix side. The MySQL server, once started, executes even very complex queries with huge result sets in record-setting time.
*	PHP supports a large number of major protocols such as POP3, IMAP, and LDAP. PHP4 added support for Java and distributed object architectures (COM and CORBA), making n-tier development a possibility for the first time.
*	PHP is forgiving: PHP language tries to be as forgiving as possible.
*	PHP Syntax is C-Like.

#### 2.	MySQL
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;MySQL is a database, widely used for accessing querying, updating, and managing data in databases.
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;MySQL is an open source RDBMS that relies on SQL for processing the data in database. MySQL provides APIs for the languages like C, C++, Eiffel, JAVA, Perl, PHP and Python. MySQL is most commonly used for web applications and for embedded applications and has become a popular alternative to proprietary database system because of its speed and reliability. MySQL can run on UNIX, Windows and Mac OS.

## <center><p style ="color: red">Project Analysis and Planning</p></center>

<div style ="color: red">

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The BMS is critical to set-up online order, customers to browse through book categories. This is a small scale project for BMS. The basic idea is that the customers can buy a book from anywhere during any time by the cash through.

**User**

*	User can Register, Login, Logout the system.
*	View different categories and by books.
*	Contact with Admin
*	Add Books to Cart
*	Order Books




**Functionality**

*	One or more user visit web page at a time.
**Usability**

*	In any browser run this webpage.

**Performance**

*	It performs the webpage as per User’s operating system.

**Admin**

*	Admin can manage system.
*	Provide books.
Functionality
*	Admin can insert a book or manage the records.

</div>

---

### <center>Spiral Model</center>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The spiral model combines the idea of iterative development with the systematic, controlled aspects of the waterfall model. This Spiral model is a combination of iterative development process model and sequential linear development model i.e. the waterfall model with a very high emphasis on risk analysis. It allows incremental releases of the product or incremental refinement through each iteration around the spiral.

### <center>Spiral Model - Design</center>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The spiral model has four phases. A software project repeatedly passes through these phases in iterations called Spirals.

#### <center>Identification</center>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;This phase starts with gathering the business requirements in the baseline spiral. In the subsequent spirals as the product matures, identification of system requirements, subsystem requirements and unit requirements are all done in this phase.
This phase also includes understanding the system requirements by continuous communication between the customer and the system analyst. At the end of the spiral, the product is deployed in the identified market.

### <center>Design</center>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The Design phase starts with the conceptual design in the baseline spiral and involves architectural design, logical design of modules, physical product design and the final design in the subsequent spirals.

### <center>Construct or Build</center>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The Construct phase refers to production of the actual software product at every spiral. In the baseline spiral, when the product is just thought of and the design is being developed a POC (Proof of Concept) is developed in this phase to get customer feedback.
Then in the subsequent spirals with higher clarity on requirements and design details a working model of the software called build is produced with a version number. These builds are sent to the customer for feedback.
### <center>Evaluation and Risk Analysis<center>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Risk Analysis includes identifying, estimating and monitoring the technical feasibility and management risks, such as schedule slippage and cost overrun. After testing the build, at the end of first iteration, the customer evaluates the software and provides feedback.<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The following illustration is a representation of the Spiral Model, listing the activities in each phase.
 
 <img src="spiral.png">
 
<p style="text-align: center;font-weight: bold">(Figure 2 : Spiral Model)</p>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Based on the customer evaluation, the software development process enters the next iteration and subsequently follows the linear approach to implement the feedback suggested by the customer. The process of iterations along the spiral continues throughout the life of the software.

### <center>Spiral Model Application</center>

The Spiral Model is widely used in the software industry as it is in sync with the natural development process of any product, i.e. learning with maturity which involves minimum risk for the customer as well as the development firms.
The following pointers explain the typical uses of a Spiral Model −
*	When there is a budget constraint and risk evaluation is important.
*	For medium to high-risk projects.
*	Long-term project commitment because of potential changes to economic priorities as the requirements change with time.
*	Customer is not sure of their requirements which are usually the case.
*	Requirements are complex and need evaluation to get clarity.
*	New product line which should be released in phases to get enough customer feedback.
*	Significant changes are expected in the product during the development cycle.

### <center>Spiral Model - Pros and Cons</center>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The advantage of spiral lifecycle model is that it allows elements of the product to be added in, when they become available or known. This assures that there is no conflict with previous requirements and design.
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;This method is consistent with approaches that have multiple software builds and releases which allows making an orderly transition to a maintenance activity. Another positive aspect of this method is that the spiral model forces an early user involvement in the system development effort.
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;On the other side, it takes a very strict management to complete such products and there is a risk of running the spiral in an indefinite loop. So, the discipline of change and the extent of taking change requests are very important to develop and deploy the product successfully.

The advantages of the Spiral SDLC Model are as follows −
1.	Changing requirements can be accommodated.
2.	Allows extensive use of prototypes.
3.	Requirements can be captured more accurately.
4.	Users see the system early.
5.	Development can be divided into smaller parts and the risky parts can be developed earlier which helps in better risk management.

<br><br><br><br><br><br><br>

---

<br><br><br><br><br><br><br>








# <p style="text-align: right">Chapter 3</p>
# <p style="text-align: right"><u>System Design</u></p>
 
---

## 3.1 Over All System Design Using Designing Tools
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The Purpose of Design Phase is to plan a solution for problem specified by the requirements. System Design aims to identify the modules that should be in the system, the specification of those modules and how they interact with other to produce the results. The goal of the design process is to produce a model that can be used later to build that system. The produced model is called design of the system.<br><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;System Design is the process of defining the architecture, components, modules, interfaces and data for a system to satisfy specified requirements.
<br><br>
Normally, the design proceeds in 2 stages:
*	Physical Design
*	Database Design

<br><br>

### <p style="text-align: center">Physical Design</p>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The Physical Design is a graphical representation of a system showing the system’s internal and external entities and the flow of data into and out of these entities. An internal entity is an entity within the system that transforms data.
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;To represent the Physical Design of the system, we use diagrams like Data Flow Diagrams, E-R Diagrams, Use Case Diagrams, etc…

### <p style="text-align: center">1.	Data Flow Diagram<center></p>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The Data Flow Diagrams (DFD) is a graphical representation of the flow of data through an information system. Data Flow Diagrams are used by systems analysis to design information processing systems but also a way to model whole organization. The main merit of DFD is that it can provide an overview of what data a system would processes. What transformations of data are done, what data are stored and which stored data is used, and where the result is flow.

---

### <center>Standard Symbols used in DFD:</center>

![symbol](symbol.PNG)

###	 <center>(Figure 3 : Data Flow Diagram Symbols)</center> 

* ###	 <center>0 Level DFD (Website Flow Diagram)</center> 


<img src="agrajz.png">
 
 
<h3><center>(Figure 4 : 0 Level Data Flow Diagram)</center></h3>

* ###	 <center>1st Level DFD (Website Flow Diagram)</center>

![diag](diagram6.png)

### <center>(Figure 5 : 1<sup>st</sup> Level Data Flow Diagram)</center>

* ###	<center>Flowchart Diagram</center>
 
![bmsd](bmsdiagram.PNG)
 
 ### <center>(Figure 6 : BMS Flowchart Diagram)</center>
---

 

* #### 	<center>User Flow Diagram</center>
 
 ![flow](flow.PNG)
 
### <center>(Figure 7 : User Flow Diagram)</center>
 
#### 2.	Use Case Diagram

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; A use case is a set of scenarios that describing an interaction between a user and a system.  A use case diagram displays the relationship among actors and use cases.  The two main components of a use case diagram are use cases and actors.

![rajz](rajz.PNG)

 <br>
 
 <h4><center>(Figure 8 : Use Case Diagram Symbols)</center></h4>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;An actor is represents a user or another system that will interact with the sys<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Item you are modeling.  A use case is an external view of the system that represents some action the user might perform in order to complete a task.







*	### <center>User Use Case Diagram</center>
 
![rajz](case.PNG)

<h4><center>(Figure 9 : User Use Case Diagram)</center></h4>



* <h3><center>	BMS Use Case Diagram</center></h3>
 ![szerk](felepites.png)
<center><h4>(Figure 10 : BMS Use Case Diagram)</h4></center>
 
<center><h3>3.	Activity Diagram</h3></center>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Activity diagram is basically a flowchart to represent the flow from one activity to another activity. The activity can be described as an operation of the system.

![sokadik7](diagram7.PNG)

---

![sokadik8](diagram8.PNG)


#### <p style ="text-align:center"> (Figure 11 : Activity Diagram Symbols)</p>
 
 
## <p style="text-align:center">1.	User Activity Diagram</p>
 
 
 ![sokadik5](diagram5.PNG)
 
 
<h4> <p style ="text-align:center">(Figure 12 : User Activity Diagram)</p></h4>
 
 
<h2> <p style="text-align:center">2.	Login System Activity Diagram</p></h 2>


![sokadik4](d0iagram4.PNG)


#### <p style ="text-align:center"> (Figure 13 : Login System Activity Diagram)</p>


	


## <p style="text-align:center">4.	E-R Diagram</p>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Entity-Relationship Diagram is a graphical representation of entities and their relationship to each other. It describes how data is related to each other. An entity is a piece of data- an object or a concept about which data is stored. A relationship is how the data is shared between entities. <br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;In E-R Diagram, there are 3 main components:

![sokadik3](diagram3.PNG)

#### <p style ="text-align:center">(Figure 14 : E-R Diagram Symbols)</p>

 
* ##  <p>	E-R Diagram for Bookstore Management System</p>

![sokadik](diagram.PNG)

#### <p style ="text-align:center">(Figure 15 : E-R Diagram for Bookstore Management System)</p>



# 3.2 Data Dictionary
* ##  <p style="text-align: center">	Database Design & Structure Design</p>
Various tables used in the System are as follows:
1.	Admin
2.	Book
3.	Category
4.	Contact
5.	Register
6.	Order
Detail of all the tables with its all the fields are as below:



1.<span style= "font-weight: bold">Table Name : </span> Admin<br>
<span style= "font-weight: bold">Primary Key :</span> a_id<br>
<span style= "font-weight: bold">Description :</span> For store Admin login Detail
</span>
<table> 
    <thead>
        <tr>
            <th>Field</th>
            <th>Type</th>
            <th>Description</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>A_id</td>
            <td>Int(4)</td>
            <td>Used to Store Admin ID</td>
        </tr>
        <tr>
            <td>A_unm</td>
            <td>Varchar(3)</td>
            <td>Used to Store Username of Admin</td>
        </tr>
        <tr>
            <td>A_pwd</td>
            <td>Varchar(30)</td>
            <td>Used to Store Password of Admin</td>
        </tr>
    </tbody>
</table>







2.	

<span style= "font-weight: bold">Table Name : </span> Book<br>
<span style= "font-weight: bold">Primary Key :</span> b_id<br>
<span style= "font-weight: bold">Description :</span> Store Book Details.
</span>


 <table> <thead> <tr> <th>Field</th> <th>Type</th> <th>Description</th> </tr> </thead> <tbody> <tr> <td>B_id</td> <td>Int(10)</td> <td>Used to Store Book ID</td> </tr> <tr> <td>B_nm</td> <td>Varchar(50)</td> <td>Used to Store Book Name</td> </tr> <tr> <td>B_cat</td> <td>Int(6)</td> <td>Used to Select or Store the Book ID of Different Categories</td> </tr> <tr> <td>B_desc</td> <td>Longtext</td> <td>Used to Store The Description of The Book in Large Amount Data</td> </tr> <tr> <td>B_price</td> <td>Int(4)</td> <td>Used to Store the Price of Book</td> </tr> <tr> <td>B_img</td> <td>Varchar(50)</td> <td>Used to Store the Image Name of Book</td> </tr> <tr> <td>B_time</td> <td>Int(20)</td> <td>Used to store the Time of Inserted book</td> </tr> </tbody> </table>

3.	<span style="font-weight: bold">Table Name: </span> Category<br>
    <span style="font-weight: bold">Primary Key: </span> cat_id<br>
    <span style="font-weight: bold">Description: </span> Store Category Names.<br><br>

    <table>
        <thead>
            <tr>
                <th>Field</th>
                <th>Type</th>
                <th>Description</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Cat_id</td>
                <td>Int(10)</td>
                <td>Used to Store the Category ID</td>
            </tr>
            <tr>
                <td>Cat_nm</td>
                <td>Varchar(50)</td>
                <td>Used to Store the Category Name</td>
            </tr>
        </tbody>
    </table>



4.	<span style="font-weight: bold">Table Name: </span> Contact<br>
    <span style="font-weight: bold">Primary Key: </span> c_id<br>
    <span style="font-weight: bold">Description: </span> Store details for Contact Us.<br><br>

    <table>
        <thead>
            <tr>
                <th>Field</th>
                <th>Type</th>
                <th>Description</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>C_id</td>
                <td>Int(4)</td>
                <td>Store Contact ID of Client/User</td>
            </tr>
            <tr>
                <td>C_fnm</td>
                <td>Varchar(100)</td>
                <td>Store Full Name of User</td>
            </tr>
            <tr>
                <td>C_mno</td>
                <td>Int(10)</td>
                <td>Store Mobile Number of Client/User</td>
            </tr>
            <tr>
                <td>C_email</td>
                <td>Varchar(60)</td>
                <td>Store the E-Mail Address of Client/User</td>
            </tr>
            <tr>
                <td>C_msg</td>
                <td>Longtext</td>
                <td>Store The Message or Query of The Client/User</td>
            </tr>
            <tr>
                <td>C_time</td>
                <td>Varchar(20)</td>
                <td>Store The Time of Contact Page inserted The Data</td>
            </tr>
        </tbody>
    </table>
5.
<span style= "font-weight: bold">Table Name : </span> Register<br>
<span style= "font-weight: bold">Primary Key :</span> r_id<br>
<span style= "font-weight: bold">Description :</span> Details for Registration Visitors or Users.
</span>

<table>
        <thead>
            <tr>
                <th>Field</th>
                <th>Type</th>
                <th>Description</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>R_id</td>
                <td>Int(8)</td>
                <td>Store User Registration ID</td>
            </tr>
            <tr>
                <td>R_fnm</td>
                <td>Varchar(100)</td>
                <td>Store Full Name of User</td>
            </tr>
            <tr>
                <td>R_unm</td>
                <td>Varchar(50)</td>
                <td>Store Username of User</td>
            </tr>
            <tr>
                <td>R_pwd</td>
                <td>Varchar(30)</td>
                <td>Store the Password of User</td>
            </tr>
            <tr>
                <td>R_cno</td>
                <td>Varchar(10)</td>
                <td>Store the Contact Number of User</td>
            </tr>
            <tr>
                <td>R_email</td>
                <td>Varchar(60)</td>
                <td>Store E-Mail Address of User</td>
            </tr>
            <tr>
                <td>R_time</td>
                <td>Varchar(20)</td>
                <td>Store Time of Registration of User</td>
            </tr>
        </tbody>
    </table>


6.	<span style= "font-weight: bold">Table Name : </span> Order<br>
<span style= "font-weight: bold">Primary Key :</span> o_id<br>
<span style= "font-weight: bold">Description :</span> Details for Order
.</span>
<table>
        <thead>
            <tr>
                <th>Field</th>
                <th>Type</th>
                <th>Description</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>O_id</td>
                <td>Int(11)</td>
                <td>Store order ID</td>
            </tr>
            <tr>
                <td>O_name</td>
                <td>Varchar(30)</td>
                <td>Store Full Name of User</td>
            </tr>
            <tr>
                <td>O_address</td>
                <td>Varchar(200)</td>
                <td>Store address of User</td>
            </tr>
            <tr>
                <td>O_pincode</td>
                <td>Int(20)</td>
                <td>Store city Pincode</td>
            </tr>
            <tr>
                <td>O_city</td>
                <td>Varchar(30)</td>
                <td>Store the City Name</td>
            </tr>
            <tr>
                <td>O_state</td>
                <td>Varchar(30)</td>
                <td>Store State</td>
            </tr>
            <tr>
                <td>O_mobile</td>
                <td>Bigint(20)</td>
                <td>Store Mobile Number</td>
            </tr>
            <tr>
                <td>O_rid</td>
                <td>Int(8)</td>
                <td>Store Register ID</td>
            </tr>
        </tbody>
    </table>













## 3.3 Input/Output Design
###### 1.	Home Page
Home Page of BMS without logged in User.
 <img src="home.png">
<p style="text-align: center;font-weight: bold">(Figure 16 : BMS Home Page)</p>

###### 2.	Selected Category

Detective Category is selected.
Shows the Books of Detective Category.
 <img src="select.png">
<p style="text-align: center;font-weight: bold">(Figure 17 : BMS SelectedCategory)</p>

###### 3.	Book Details (Before Login)

Book Detail for Visitors.
Visitors Can’t add Books to Add to Cart.
 <img src="book.png">
<p style="text-align: center;font-weight: bold">(Figure 18 : BMS Book Details)</p>

###### 4.	Visitor Login Page

Login Page for Viewers.
 <img src="2.png">
<p style="text-align: center;font-weight: bold">(Figure 19 : BMS Login Page)</p>

###### 5.	Register Page
Register Page for Viewers.
 <img src="reg2.png">
<p style="text-align: center;font-weight: bold">(Figure 20 : BMS Register Page)</p>


###### 6.	Contact Us Page
 <img src="contact.png">
<p style="text-align: center;font-weight: bold">(Figure 21 : BMS Contact Us Page)</p>

###### 7.	Cart Page
 <img src="cartp.png">
<p style="text-align: center;font-weight: bold">(Figure 22 : BMS Cart Page Viewers)</p>

###### 8.	Order Page
Only Cash On Delivery is Available for Orders.
 <img src="order.png">
<p style="text-align: center;font-weight: bold">(Figure 23 : BMS Order Page)</p>

###### 9.	Home Page (Logged In)

Automatically Navigation Bar Changed.
User Can Log Out.
 <img src="sys.png">
<p style="text-align: center;font-weight: bold">(Figure 24 : BMS Logged in Page)</p>

###### 10.	Book Details (Logged In)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Users can Add Book To Add to cart.<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Removed Sign in Link.
 <img src="details.png">
<p style="text-align: center;font-weight: bold">(Figure 25 : BMS Users Book Details)</p>

###### 11.	Add to Cart (Logged In)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Users Can add books to add to cart.<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Details of books and price.<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Click Recalculate to Qty, Rate and Total will Calculate.<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Users can order Books.<br>

 <img src="category.png">
<p style="text-align: center;font-weight: bold">(Figure 26 : BMS  Users Cart Page)</p>

###### 12.	Search Books
<img src="cart.png">
Book Search Feature.
 <img src="search.png">
<p style="text-align: center;font-weight: bold">(Figure 27 : BMS Search Books)</p>

###### 13.	Admin Login Page (New Template)
 <img src="logi.png">
<p style="text-align: center;font-weight: bold">(Figure 28 : BMS Admin Login page)</p>

###### 14.	Admin Home Page

New Template.
 <img src="admin.png">
 
<p style="text-align: center;font-weight: bold">(Figure 29 : BMS Admin Home Page)</p>

###### 15.	Add Category (Admin)
 
 <img src="add3.png">
 
<p style="text-align: center;font-weight: bold">(Figure 30 : BMS Add New Category)</p>

###### 16.	View Category


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;List of Books.
<img src="category.png">
 
<p style="text-align: center;font-weight: bold">(Figure 31 : BMS View Category)</p>


###### 17.	Add Books

<img src="add2.png">

 <p style="text-align: center;font-weight: bold">(Figure 32 : BMS Add New Books)</p>
 

###### 18. View Books 

List Books for Admin.
<img src="view.png">
 
<p style="text-align: center;font-weight: bold">(Figure 33 : BMS View Books)</p>

###### 19.	View Contacted List
List of People who Contacted using Contacted Page.
 
 <img src="Contacted.png">
 
 
<p style="text-align: center;font-weight: bold">(Figure 34 : BMS Contacted List Books)</p>

###### 20.	Users List


 <img src="userlist.png">
<p style="text-align: center;font-weight: bold"> (Figure 35 : BMS Users List)</p>

###### 21.	Forget Password <br>

<img src="forgot.png">
<p style="text-align: center;font-weight: bold"> (Figure 36 : BMS Forget Password Page)</p>








---
# Chapter 4
# <u>Testing And Implementation</u>
---
 
## 4.1 Testing Approach Used

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Black box testing
Black-box testing is a method of software testing that examines the functionality of  an application based on the specifications. It is also known as specifications based .<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Testing Independent testing team usually perform this type of testing during   the software testing life cycle.<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;This method of test can be applied to each and every level of software testing such as unit, integration, system and acceptance testing.
 
 <img src="box2.png">
<p style="text-align: center;font-weight: bold">(Figure 37 : Black Box Testing)</p>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;This method is named so because the software program, in the eyes of the tester, is like a black box; inside which one cannot see. This method attempts to find errors in the following categories:
* 	Incorrect or missing functions
* 	Interface errors
* 	Errors in data structures or external database access
* 	Behavior or performance errors
* 	Initialization and termination errors
<br>
* #####	Advantages of Black box Testing: 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Tests are done from a user’s point of view and will help in exposing discrepancies in the specifications.
Tester need not know programming languages or how the software has been implemented.
#### White box testing
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;White box testing is a testing technique That examines the program structure and derives test data from the program logic/code. The other names of glass box testing are clear box testing, open box testing, logic driven testing or path driven testing or structural testing.
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;White box testing involves looking at the structure of the code. When you know the internal structure of a product, tests can be conducted to ensure that the internal operations performed according to the specification. And all internal components have been adequately exercised.
 
#### White box testing techniques:
A.	Statement Coverage – This technique is aimed at exercising all programming statements with minimal tests.
A.	Branch Coverage – This technique is running a series of tests to ensure that all branches are tested at least once.
A.	Path coverage – This technique corresponds to testing all possible paths which means that each statement and branches is covered.


#### Advantages of white box Testing:
1.	Forces test developer to reason carefully about implementation.
2.	Reveals errors in “hidden” code.
3.	Sports the code or other issues with respect to best programming practices.

#### Gray-box Testing: 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Grey-box testing is a testing technique performed with limited information about the internal functionality of the system. Grey-box testers have access to the detailed design information about requirements.<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Grey box are generated based on the state based modes, UML diagrams or of the target system.<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Grey Box Testing is a technique to test the software product or application with partial knowledge of the internal workings of an application.
 
 <img src="box.png">
<p style="font-weight:bold; text-align: center"> (Figure 38 : Gray Box Testing Testing)</p>


4.2 Test Cases
4.2.1 Admin Login Detail
 <table>
        <tr>
            <th>Username</th>
            <th>Admin</th>
            <th>Password</th>
            <th>Admin</th>
        </tr>
        <tr>
            <td colspan="4">
                Expected Result : <br><br>
                <ul>
                    <li>If fields empty then gives a error for fill up fields</li>
                    <li>If password or username does not exist then gives error for valid detail</li>
                </ul>
            </td>
        </tr>
    </table>


 
4.2.2 Login Detail<br>

 <table>
        <tr>
            <th>Username</th>
            <th>Admin</th>
                <th>Password</th>
            <th>Admin</th>
        </tr>
        <td colspan="4">
        Expected Result : <br><br>
<li> If fields empty then gives a error for fill up fields<br>
<li> If password or username does not exist then gives error for valid detail
  
  </td>
      
    </table>
    
4.2.3 Registration Details


 <table>
        <tr>
            <th>Username</th>
            <th>EMPTY</th>
            <th>Password</th>
            <th>EMPTY</th>
        </tr>
        <tr>
            <th>Full Name</th>
            <th>EMPTY</th>
            <th>Security Answer</th>
            <th>EMPTY</th>
        </tr>
        <tr>
            <td colspan="4">
                Expected Result : <br><br>
                <ul>
                    <li>If fields empty then gives a error for fill up fields</li>
                    <li>If password or username does not exist then gives error for valid detail.</li>
                    <li>If password is < 8 characters then it will gives error.</li>
                    
                </ul>
            </td>
        </tr>
    </table>

4.2.4 Order Details

 <table>
        <tr>
            <th>Full Name</th>
            <th>Address</th>
            <th>Contact Number</th>
            <th>EMPTY</th>
        </tr>
        <tr>
            <td colspan="4">
                Expected Result : <br><br>
                <ul>
                    <li>If fields empty then gives a error for fill up fields</li>
                    <li>If contact number is not Numeric then gives error</li>
                </ul>
            </td>
        </tr>
    </table>

### <center><u>Screen-Shots</u></center>
#### 1.	User Login
 
## (Figure 39 : Test Cases 1)
  <img src="log2.png">


#### 2.	Admin Login
  <img src="log.png">

## (Figure 40 : Text Cases 2)

#### 3.	Add Book
 <img src="add.png">

## (Figure 41 : Text Cases 3)
 
#### 4.	  User Registration
 
 <img src="reg.png">

## (Figure 42 : Text Cases 4)


##   4.3	Implementation approaches
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Far the biggest challenge encountered was time constraints. Implementation takes an extraordinary amount of time and a large amount of coordination. Scheduling project meetings around every group member’s schedule has been nearly impossible. Many of the group members were unable to devote the amount of focus that the implementation stage required. Both the former and the latter problem may be more of an issue in the academic environment where priorities of the different group members are skewed in a variety of directions. Another issue that cropped up was knowledge of the PHP programming. At least two of the four group members were unfamiliar with PHP Swing API, which is php primary user interface package. Again, this may not be as much of an issue in software engineering outside the academic arena.<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;One of tools we found very useful, in situations where member responsibilities need to be hashed out, is the responsibility matrix. It has really been the only tool that has allowed us to continue making progress. Everyone is assigned a task, and everyone is held accountable for the completion of their assigned task. It also allows us to track tasks that need to be done. The responsibility matrix has proven to be an invaluable tool in the software engineering process.
<div class="page-break"></div>





















# <div class="page-break" style ="font-size: ">Chapter 5<br> <u>Conclusion</u> </div>

 
###### Conclusion
*	At the first look we can say that Bookstore Management System is a perfect system but it has many limitations that are as follow :
*	This is also used for list the category and books also manage the customer and books of the Bookstore.
*	The Bookstore Management System is used to give information of the Books to the customer.
*	We faced problems like Database creation, Flow of our system, designing of front end and back end tools, coding etc.
*	Only single user can use a system at a time.
*	In this system we cannot add a service module.
*	We learnt new languages like jQuery, PHP, Boot-Strap, HTML, CSS, etc..
## 5.1 Limitation of system
*	Help<br>
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Currently the help feature is not available. Using this functionality user can get help about the system.
*	Payment <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Currently the feature of online payment is not available. User cannot give payment online.
*	Multilingual <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Multilingual is not supported in our system. Therefore user cannot work in different languages.
*	Backup & Recovery: <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;User cannot take the backup or recover the data in this the system.
*	Many More Others.


## 5.2 Future Scope of the System
*	Help module <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Using this module user can get help on how to access the system. All functionalities of system are described in this module. And user can easily access the entire module using this feature.
*	Online payment module <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;User can do their payment online using this functionality. In future we will add the online payment for make payment easier for the user.
*	Multilingual <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;In this system we will add the multilingual therefore user can work in different languages and understand easily.

## 5.3 Bibliography
####  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Websites Used
o	www.google.com<br>
o	www.w3cschools.com<br>
o	www.stackoverflow.com<br>
o	www.quora.com<br>
o	www.Scribd.com<br>
#### Apps Used
*	Youtube
*	Solo Learn
*	Udemy..
