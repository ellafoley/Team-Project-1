# Team-Project-1

This is the collaboration space for CS210 Group #3 at Bellevue College, Winter 2020 Semester. We are learning Java, group collaboration, and introducing ourselves to the use of Github for coding projects.

# Team-Project-2

This will be the second of your team projects for this quarter. Data for the project can be found in the ZIP archive SSANames.zip, a link to which is in the Module Chapter 6. In that ZIP archive are files of names, as known by Social Security, for every year from 1880 to 2018. Your job will be to create a program that responds to a user query about the popularity of a name in a given year, with that name's frequency in that year; note that the name may be both a female and a male name, so you may need to output information for both. There is a PDF in the ZIP archive that tells you the format for the annual name-frequency text files; these files have names of the form yobyyyy,txt, where yyyy is the year in which the names inside were registered with the Social Security Administration.

The first job of the team is to pick a project lead, whose responsibility will be to write up the team report; it must be a Word document, and it must identify the contributions of all the team members to the project, and describe the project's process that led to achieving its goal. The project deliverable will be a ZIP archive in the usual format, i.e. Java source file(s) in the prescribed format, and any data files required for its operation. Also required to be present in the submission will be a Word document, identifying the contributors, and the specific contributions of each, as well as describing the project's process, i.e., how did the project accomplish its goals, event by event.The project deliverable file must be named TeamNTP02.zip, where N is replaced by a specific team number. The project lead will submit this archive against the assignment.

#### How to read the data

For each year of birth YYYY after 1879, we created a comma-delimited file called yobYYYY.txt.
Each record in the individual annual files has the format "name,sex,number," where name is 2 to 15
characters, sex is M (male) or F (female) and "number" is the number of occurrences of the name.
Each file is sorted first on sex and then on number of occurrences in descending order. When there is
a tie on the number of occurrences, names are listed in alphabetical order. This sorting makes it easy to
determine a name's rank. The first record for each sex has rank 1, the second record for each sex has
rank 2, and so forth.
To safeguard privacy, we restrict our list of names to those with at least 5 occurrences
