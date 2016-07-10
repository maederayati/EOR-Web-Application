# Chemical EOR Web Application


##Login and Registeration
Since the website is not free, in order to use it one have to register first. In order to do the registeration you have to choose a user name a password and enter the registration key you are already given. Notice that each registration key is associated with one license, meaning only one username and password can register with one key.  After registering your user name and password you can enter login page and enter the website. <br><br>



![Login Page](https://github.com/maederayati/Test/blob/master/login.jpg) <br><br>


![Registration Page](https://github.com/maederayati/Test/blob/master/register.jpg) <br><br>

When you are loged in you can see the processes menu and all the sub-menus. Overall there are eight chemical injection processes as follows:
1. Alkaline
2. Surfactant
3. Polymer
4. SP
5. Gel
6. AP
7. AS
8. ASP


Each process has  the same layout as the others and it is as follows:
* Technical Resources
* Database
* Screening Criteria
* Performance Data
* Economic Models
<br><br>

![Main Page](https://github.com/maederayati/Test/blob/master/main.jpg)<br><br>




## Technical Resources

The Technical Resources,  contains related sources to the process. For example in polymer, the following items can be viewed as follows:<br><br>

![Technical Resources Page](https://github.com/maederayati/Test/blob/master/technicalResources.jpg)<br><br>


## Database

The main purpose of this page is to draw plots based on the databse. The plots might be either two dimensional (Y, X1) or three dimensional (Y, X1, X2). The follwoing information is necessary to get any plot:

1. X Axis: All the possible options for X axis are shown on a drop down list. The parameters that are listed for X axis are either numerical or textual.
2. Y Axis:  All the possible options for X axis are shown on a drop down list. The options for Y axis are only numerical.

If the user for some reason does not choose a parameter name for X axis or Y axis or both, an alert would pop up and reminds the user to enter the values completely. Other optional parameters for ploting are as follows: 

3. Upper bound and lower bound for X axis
4. Upper bound and lower bound for Y axis
5. Second X Axis
6. Upper bound and lower bound for second X axis
7. Numerial Constraint 1 to filter more the resulted data
8. Upper bound and lower bound for constraint 1
9. Numerial Constraint 2 to filter more the resulted data
10. Upper bound and lower bound for constraint 2
11. Textual Constraint to filter more the resulted data
12. Relation Between Constraints which is either "AND" or "OR"


Notice that By default the relation between constraint is "And", unless user changes the relation to "OR".
Parameters in the drop down list are sorted alphabetically, but for convenience, project name could be seen as the first item in the list. 

<br><br>

![Technical Resources Page](https://github.com/maederayati/Test/blob/master/database.jpg)<br><br>


After choosing the desired parameters he user clicks on plot and get the related plot. The pictures below are examples of the plot. The first plot is a two dimentinal plot and the second plot is a three dimentional plot. <br><br>

![Plot 1](https://github.com/maederayati/Test/blob/master/graph1.jpg)<br><br>
![Plot 2](https://github.com/maederayati/Test/blob/master/graph2.jpg)<br><br>




Furthermore, there is an option to see the value of textual parameters for each process. The user can choose a specific project name and by selecting a textual parameter (e.g. references for that project). Then he can access the textual value of that parameter of that project. The data would show up in a table format. Once at a time one can either see a plot or a table but not both.<br><br>

![Table 1](https://github.com/maederayati/Test/blob/master/table1.jpg)<br><br>



## Screening Criteria
Screening criteria submenu is mainly designed for comparing values for certain parameters in existing projects with what the user has in mind. The parameters for Existing Projects are the median values (at cumulative 50%) from the existing projects. As an example, after the user inputs a temperature, and click Compare, it will show all existing project temperature compared with the user input temperature.<br><br>

![Table 1](https://github.com/maederayati/Test/blob/master/screeningCriteria.jpg)<br><br>

As the picture below suggests the number of graphs is proportional to the number of projects found in the database. Each graph shows the data for at most 50 projects. 

![Table 1](https://github.com/maederayati/Test/blob/master/ScGraph.png)<br><br>





