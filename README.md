# Content-Management-System
Developing a “Content Management System” –CMS- by using Java programming language. You should handle Roles, Users and Contents within system.

1. SOFTWARE USAGE
This application is designed to operate with the contents such as, video, image, and
document. In general, the user can perform three main functions by using this
program. The user can save a content into the application by inserting name, ID
number, and mime type of the content. These contents can also be listed by the user.
If you want to run this application, you should follow the following steps. First, you
should open an input file. You should insert a data in the right format in order to save
user, role, and content information on input file. There is an example in here:
There are some other features this application provides to its users. One of them is if
the user is authorized, he will be able to read the content in the program. If he has an
authorization, you can receive an output message from result file. In addition, you
can see the results of the activities that are performed from log file.
Another one is if the user is not authorized, he will be able to list the file size of all
contents. You will be able to see this list on the result file. Also, log file keeps
activities of the user whether or not he pursues successfully.
2. PROBLEM
This section will articulate the problems which I have faced during this assignment.
The most challenging part was to design link list as custom. The problem was the
data which I defined in content category did not match with the data I received after
applying file parcer. Another problem I encountered was the string type data I was
receiving. Moreover, the software gave a series of error while I was getting readings
of input and output files. I had difficulty to set these files’ paths. After setting them, the
software gave errors again. For example;
In addition, as I was adding content and creating an object, I have encountered
errors. Even though I had searched for a solution via online resources, I couldn’t
reach to a solution. Another problem I experienced was I was missing override
software design knowledge while I was implementing toString method.
3. SOLUTION
This section will present the solutions for the problems that I have stated in section 2.
In order to custom design the link list, I got inspired by online websites examples. I
developed a method called functionSelection so that I would be able to adapt the
detail I have to custom category. By doing this step, I was able to dissect some of the
data in fileparser and then seperate it to its components in functionSelection.
Eventually, I assigned every component to content variables.
Regarding to my second problem, the data I received was in string type due to the
function I was using. I used a premade integer conversion function to convert string
type to integer. I did a research for special functions in Oracle’s website in order to
solve this problem.
As a solution to the diffuculty of input and output file reading and writing, I found
answers and applications in online blogs. I needed to type the input and output file
name as it is without including their paths so that these files could had been saved in
this assignment’s file.
Overall, the problem I had with creating an object and its content had an
uncomplicated solution; even though, it seemed very challenging. I achieved creating
the object and its contents by following steps in order: parse(ing) the data, assigning
the parse(d) data to its variables, and creating an object. However, I tried to create an
object before assigning the object.
Eventually, I did a search on override software design online in order to overcome my
problem.
