## Summary (Summarize the bug encountered concisely)

     A typographical error exists on the Project Creation page, where the option to start a new project is incorrectly labeled "Create black project" instead of the intended "Create blank project." This affects UI and professionalism.

## Steps to reproduce

     Precondition: Log in to GitLab using a valid user account.

     Navigate to the New Project creation page: https://gitlab.com/projects/new#blank_project.

     Observe the tabs available for project creation (e.g., "Create blank project", "Create from template").

## What is the current bug behavior?

     The label for starting a new project displays a typo: instead of blank = black.

## What is the expected correct behavior?

     The label for starting a new project without any template should read: "Create blank project".

## Relevant logs and/or screenshots

 Bug Screenshot (Current Behavior)
 ![Bug Screenshot](https://github.com/janunanu/Janina_Ahma_Testing_Project/blob/main/Image/Bug_Project_create_blank.png)

 Expected Screenshot (Correct Behavior)
 ![Fixed Screenshot](https://github.com/janunanu/Janina_Ahma_Testing_Project/blob/main/Image/Bug_Screenshot.png)

     

## Possible fixes

     Locate the string variable or constant responsible for the tab label text in the Project Creation module.

     Change the value from "Create black project" to "Create blank project".

## Whom do you report/ Assign To/ Tags

      /label ~bug ~reproduced ~needs-investigation
      /cc @project-manager
      /assign @qa-tester

## Priority

     Minor
     This is a simple text fix that impacts the user interface's quality and professionalism.


