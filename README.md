# Research Techniques NPE

## Team members

| Naam     | Github                        | Email                               |
| :---     | :---                          | :---                                |
| student1 | <https://github.com/student1> | <mailto:student1@student.hogent.be> |
| student2 | <https://github.com/student2> | <mailto:student2@student.hogent.be> |
| student3 | <https://github.com/student3> | <mailto:student3@student.hogent.be> |
| student4 | <https://github.com/student4> | <mailto:student4@student.hogent.be> |

Use this repository to keep all information, source code and results of your group assignment for the Research Techniques course. The file [checklist.md](checklist.md) contains an overview of the most important TODOs. bevat een overzicht van de belangrijkste TODOs.

Use [Markdown](https://guides.github.com/features/mastering-markdown/) for reports, procedures, etc., that is, for all documents with formatted text that you would have used Word for. A LaTeX-template for the final paper and bibliographic database is also provided.

- Familiarize yourself with working with Git. Read the documentation on Github or peruse the slides of the [Git Workshop for the IT-lab](https://gitpitch.com/HoGentTIN/workshop-git-itlab#/) (slides in Dutch)
    - If you haven't done this before, register your @student.hogent.be email address in your Github-account (you can add multiple addresses to a single account).
    - It is essential to configure Git correctly on your laptop with your name and the email address associated with your Github account. Instructions are given below, including recommended global settings.
- Each team member clones this repository on their laptop
- Fill out the names and contact information of all team members in the table above

Execute the following commands on the terminal:

```console
$ git config --global user.name "GivenName SurName"
$ git config --global user.email "GivenName.SurName@student.hogent.be"
$ git config --global push.default simple
$ git config --global pull.rebase true
$ git config --global core.autocrlf input
```
