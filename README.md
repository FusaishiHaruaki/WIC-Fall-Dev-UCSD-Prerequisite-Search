# WIC-Fall-Dev-UCSD-Prerequisite-Search

# Instructions: 
- Download main.html
- Run webpage on browser
- enter course code to see visual representation of prerequisites

# Limitations: 
- The page can currently only be accessed through the local file
- Requires wifi to run
- Ugly layout
- Requires input with specific regulations
- Outdated? prerequisite sheet

# Graph keys: 
- Multiple courses pointing to the same port indicates "or" relation. Only one of the prerequisites need to be fulfilled for the prerequisite. 
- e.g. Minimum one of MATH 3C or MATH 4C need to be taken for the prerequisite of MATH 10A. 
<img width="504" alt="Screen Shot 2022-12-30 at 10 43 23 PM" src="https://user-images.githubusercontent.com/100342771/210056600-5513fa01-228a-4a29-8452-b1a6c2963fc5.png">

- Multiple ports of one node indicates "and" relation. All prerequisites for the course must be fulfilled for the prerequisites.          

- e.g. Both CSE 12 and CSE 15L need to be taken for the prerequisite of CSE 30. 
<img width="495" alt="Screen Shot 2022-12-30 at 10 43 51 PM" src="https://user-images.githubusercontent.com/100342771/210056617-eb3092d2-a53e-417f-931c-4f8e1c14eece.png">

The below image indicates that MATH 20C and one of MATH 31AH, MATH 20F, MATH 18 are required for MATH 109.
<img width="330" alt="Screen Shot 2022-12-30 at 10 44 54 PM" src="https://user-images.githubusercontent.com/100342771/210056983-1c0c8554-64ee-4c06-82f4-2406b668f52d.png">


# Sources: 
Used library: GoJS https://gojs.net/latest/index.html
Sample: https://gojs.net/latest/samples/dynamicPorts.html

Course prereq JSON file from: https://github.com/dcao/seascape/blob/master/data/prereqs.json
