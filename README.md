# Research Techniques NPE

## Team members

| Naam     | Github                        | Email                               |
| :---     | :---                          | :---                                |
| student1 | <https://github.com/student1> | <mailto:student1@student.hogent.be> |
| student2 | <https://github.com/student2> | <mailto:student2@student.hogent.be> |
| student3 | <https://github.com/student3> | <mailto:student3@student.hogent.be> |
| student4 | <https://github.com/student4> | <mailto:student4@student.hogent.be> |

Use this repository to store all information, source code and results of your group assignment for the Research Techniques course. The file [checklist.md](checklist.md) contains an overview of the most important TODOs. 

Use [Markdown](https://guides.github.com/features/mastering-markdown/) when writing reports, procedures, etc., that is, for all documents with formatted text that you would otherwise have used Word for. A LaTeX-template for the final paper and bibliographic database is also provided.

- Familiarize yourself with Git. Read the documentation on GitHub or peruse the slides of the [Git Workshop for the IT-lab](https://gitpitch.com/HoGentTIN/workshop-git-itlab#/) (slides in Dutch)
    - If you haven't done this already, add your @student.hogent.be email address to your Github-account (you can add multiple addresses to a single account).
    - It is essential to configure Git correctly on your laptop, add your name and the email address associated with your Github account. Instructions are given below, including recommended global settings.
- Each team member needs to clone this repository to their laptop
- Add the names and contact information of all team members to the table above

Execute the following commands on the terminal:

```console
$ git config --global user.name "GivenName SurName"
$ git config --global user.email "GivenName.SurName@student.hogent.be"
$ git config --global push.default simple
$ git config --global pull.rebase true
$ git config --global core.autocrlf input
```
