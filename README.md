## Flask Application Design for Resume Builder

**HTML Files**

- resume_builder.html: User interface for creating and saving resumes. Contains fields for personal information, education, skills, and experience.
- resume_view.html: Displays a generated resume in PDF format.

**Routes**

- `/`: Main route that redirects to the resume builder page (resume_builder.html).
- `/create_resume`: Route for handling resume creation. POST request to this route saves the resume data entered in the form on resume_builder.html to a database or file.
- `/view_resume`: Route for generating and displaying a resume in PDF format based on the data stored in the database or file.
- `/edit_resume`: Route for editing an existing resume. POST request to this route updates the resume data in the database or file.