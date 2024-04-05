# projects
# The Project
This project is a modest attempt at replicating how job posting websites work. 
First, we begin by scraping specific elements from a job postnig website, and store these elements in a dataframe. Then, users can interact with a constructed interface to find jobs matching their criteria, and eventually allowing them to apply for the selected jobs directly from the companies websites. Furthermore, users can choose to have their job-matching criteria directly sent to their email adresses. 

Among the criterias a user can choose from:
- **Keyword** : this can relate to job titles, or the company's name.

- **Contract type** : users can choose between a 'CDI', 'CDD', 'Stage', 'Alternance', 'Contrat d'apprentissage' or 'freelance' job.

- **City and Postal Code** 

- **Remote work** : users can choose between completely remote jobs, and jobs allowing only partial or occasional remote work. 

We use ***Selenium*** to scrape job postings from the Indeed website, and ***Tkinter*** (along with ***customtkinter***) to build an easy-to-use interface (among other packages of course) 

Below is a snippet of the interface:
Users can interact with the interface to search for jobs matching their criteria, and be directly sent to the job posting on the company's website to apply.

![image](https://github.com/Ousow/projects/assets/157910867/e7b6557e-6de4-4200-8145-4f17b5f53c52)


Furthermore, users can choose to receive the job offers by email. Indeedm wheb the checkbox is clicked, a new part of the interface will reveal itself, allowing users to receive jobs by email.

![image](https://github.com/Ousow/projects/assets/157910867/79596531-6f8d-4f25-9589-e45a3156acc0)



And here is a snippet of the email format that is sent to users:
![image](https://github.com/Ousow/projects/assets/157910867/e926bef1-afaa-4b70-9c0c-7b6e0369c73d)
