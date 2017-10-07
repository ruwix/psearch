# psearch
A program to navigate your project folder <br />
Requirements: <br />
  To run, instead of typing "./psearch", use ". ./psearch", so that it will run in the current bash session <br />
  Also, you projects folder should be in this format: <br />
  <pre>
    └── [project-folder] <br />
        ├── [language1]  <br />
        |   ├── [file1]  <br />
        |   └── [file2]  <br />
        |
        ├── [language2]  <br />
        |   ├── [file1]  <br />
        |   ├── [file2]  <br />
        |   └── [file3]  <br />
        |
        └── [language3   <br />
            └── [file1]  <br />
  </pre>


Usage: <br />
  ```
  psearch [project] | Finds a project with the given name and goes to that directory"
  psearch -l [language] | Lists all projects of a given language, leave blank to just list languages
  psearch -c [language] [name] | Creates a new project in the given language with the given name
  psearch -a [language] | Add a new language folder
  ```
