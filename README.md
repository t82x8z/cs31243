java c
CS 338 Computer Applications in Business: Database
Assignment #3 – ERD and Mapping
IntroductionAssignments are essential in learning the material and preparing for exams. You can ask for help but make sure you write the answers in your own words. We will check for copies. You should submit your work to the Dropbox on Learn, by 1pm on Nov 13, 2024. Late submission will NOT be accepted.
In order for Learn to properly render and display your file, when you submit your assignment (or exam) file, please ONLY upload PDF file or image (JPG, JPEG, BMP, PNG) file.
Questions
1.   Draw an entity-relationship diagram to store the following publishing information. Every author has a unique ID and might have URL pointed to their personal web site. An author might write multiple publications. Each publication has a unique ID (PUBID) and could be a book, a journal, a proceedings, or an article. A proceedings consists of articles presented in a conference while a journal is made up of written articles. A proceedings or a journal has one and only author, who is actually the chief editor. A book or an article might have multiple authors. A book might or might not contain any article. An article might appear in book(s), journal(s), or proceedings. Make your own assumptions based on your understanding of the problem when needed. Your assumptions will be graded by their reasonableness. You can fill in the missing attributes like names, titles etc. Make sure to also properly specify primary keys, participation constraints and cardinality constraints.
2.   The rules of mapping ERD to relational schema are well defined and you don’t need to know the semantics of the diagram to properly convert it to a relational model. This is why I intentionally made the names meaningless in this exercise. Map the following ER diagram into a relational schema. Make sure to include proper primary keys and foreign keys.

3.   Based  on  the  function,  information  and  your  own  experience  about  eBay.ca,  draw  an  entity- relationship diagram to store related information about the site. Note that you don’t need to include all the functions and attributes, just the important ones. Make your own assumptions based on your understanding of the problem when needed. Your assumptions will be graded by their reasonableness.
4.   Great West Life has been providing outstanding service to University of Waterloo since 1994. They have been storing the claim information in files. Now they want to modernize their practice. You have been requested to design a database to store information on health claims. A health claim form. is attached on the last page. Based on the form, identify the entities and attributes. T代 写CS 338 Computer Applications in Business: Database Assignment #3 – ERD and MappingPython
代做程序编程语言hen draw a complete entity-relationship diagram to model the data in the claim form. Make sure to include proper primary keys, relationships, cardinality constraints, and participation constraints. Make your own assumptions based on your understanding of the problem when needed. Your assumptions will be graded by their reasonableness
5.   Map the following ER diagram into a relational schema. Make sure to include proper primary keys and foreign keys.





6.   Map the following ER diagram into a relational schema. Make sure to include proper primary keys and foreign keys.

7.   The Sales database stores the following information. A customer might place some order. An order contains some item(s). An item is a product made by some manufacturer who might offer warranty for the product. The database involves the following relations where primary keys are underlined and arrows indicate foreign keys. Your job is to reverse-engineer the schema and re-construct the ERD. Make  your  own  assumptions  based  on  your  understanding  of the problem when needed. Your assumptions will be graded by their reasonableness. You can fill in the missing attributes like names, titles etc. Make sure to also properly specify primary keys, participation constraints and cardinality constraints.



8.   Modify the shipping ERD to accommodate the following changes:
•   Add an ID to every port so that it can be uniquely identified on its own.
•   Due to the improved precision of GPS, ship movement can be tracked using the ship’s time stamp, longitude and latitude.
•    Ship names are no longer unique as it is regulated by different countries. So ships registered in different countries might have the same name. As such, more ship owner information needs to be included, including their names, address and phone number. A ship might be owned by multiple owners and an owner must own at least one ship.
•   Every ship now must have a home port.
•   We need to include information about whether a state/country is near an ocean, a lake or a sea. If it is, indicate the country is near which waterbody.
•   Also a port now could be on multiple water bodies (sea/ocean/lake). For examples, ports near a river entrance to an ocean could be defined as being on both water bodies. 

Marking (40 points)
Each question is worth 5 points and is marked according to the following scheme:
•   Excellent (no mistake or very small one): 5 points;
•   Good (some mistakes): 4 points;
•   Ok (lots of mistakes): 3 points;
•   Poor (mostly wrong but has some merit): 1 point;
•   Wrong (totally off or no answer): 0 point.



         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
