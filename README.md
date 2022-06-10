# Pygame Community GitHub Projects

A repository for documenting and storing information about projects of the GitHub organization.

## Adding a project directory
The procedure for adding project information in this repository is as follows:

1. **Find the project number of the organization project.**
    - This can be seen under the project name at the **Projects** tab of the organization or in the URL of the project.
2. **Create a kebab-case version of the project name.**
    - This should be done with an online converter or comparable tools for uniformity reasons.
3. **Create a `README` for the project at `project_number/kebab-case-project-name/README.md`.**
    - The first line of the README file **must** be (literally) `path:project_number/kebab-case-project-name`, as it helps with searching through this repository for the project.
    - The title of the page must be a H1 (header 1) markdown title, which should contain a hyperlink to the project it is documenting.

Additional files and directories may be added to `project_number/kebab-case-project-name/` as needed.

## Commits

### Commit Rule 1
**Each commit made to this repository that adds, edits or renames a series of files must contain the paths of the files being modified.**
- For example, a commit that modifies `4/project-mission-control/README.md` should be phrased as "Update 4/project-mission-control/README.md". If the modified files are within the same directory, only the directory can be specified, with other affected files mentioned in the description of the commit.

### Commit Rule 2
**Commit descriptions should always be provided for larger changes to one or more files.**

### Commit Rule 3
**Each commit made to this repository must only modify one project directory at a time.**

Together, these rules allow for a cleaner and easy-to-follow commit history.
