# Lab 2: Create an issue template in GitHub

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMSkillsNetwork-WD0231EN-SkillsNetwork/IDSN-logo.png" width="200" alt="cognitiveclass.ai logo">

**Estimated time needed:** 10 minutes

In this lab, you will create an issue template in GitHub that will help you to write well-formatted user stories in ZenHub.



After completing this lab, you will be able to:

1. Create an issue template in GitHub that contains the information required for writing good user stories.

## Exercise 1 : Create an issue template in GitHub

In this exercise, you will create an issue template in GitHub. This only needs to be done once for each new repository that you create.

1. Go to [GitHub.com](http://github.com) and select the &#x60;lab-agile-planning&#x60; repository that you created in [Lab 1](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_1/lab1-get-set-up-in-zenhub.md.html).
    ![github home](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_2/images/lab2-select-repository.png).

1. From the repository page, select **Settings**.
    ![select settings](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_2/images/lab2-select-settings.png)

1. Scroll down to the **Features** section and select **Set up templates**.
    ![select setup templates](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_2/images/lab2-select-setup-templates.png)

1. From the dropdown list labeled **Add template** (1), select **Custom template** (2).
    ![select custom template](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_2/images/lab2-select-custom-template.png)

1. Next to the **Custom issue template** entry, press the **Preview and edit** button.
    ![select preview and edit](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_2/images/lab2-select-preview-edit.png)

1. Press the **pencil** icon to edit the template.
    ![select pencil](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_2/images/lab2-edit-template.png)

1. Copy the following markdown for the story template content:
    &lt;pre&gt;
    **As a** [role]  
    **I need** [function]  
    **So that** [benefit]  
      
    ### Details and Assumptions
    * [document what you know]
      
    ### Acceptance Criteria  
      
    &#x60;&#x60;&#x60;gherkin
    Given [some context]
    When [certain action is taken]
    Then [the outcome of action is observed]
    &#x60;&#x60;&#x60;&lt;/pre&gt;

1. Edit the **Template name** to be: &#x60;User Story&#x60;, give it an appropriate **description**, and paste the contents of the above markdown into the **Template content**
    ![template contents](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_2/images/lab2-template-contents.png)

1. Scroll to the top of the page and press the **Propose changes** button.
    ![propose changes](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_2/images/lab2-propose-changes.png)

1. Press the **Commit changes** button to commit the change to your repository.
    ![commit template changes](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_2/images/lab2-commit-template-changes.png).

1. You should now have a new folder in your repository called &#x60;.github/ISSUE_TEMPLATES&#x60;, which will contain your new user story template.
    ![template created](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_2/images/lab2-template-created.png).

## Summary

You now have an issue template that you can use for all of your GitHub repositories that you need to write stories for to use in ZenHub. When we create issues in future labs, this template will guide you through what information is needed to create your user story.

## Author(s)

[John Rofrano](https://www.coursera.org/instructor/johnrofrano)

## Changelog
| Date | Version | Changed by | Change Description |
|------|--------|--------|---------|
|2023-08-17| 1.4 | Lavanya Rajalingam | Fixed Link for Lab1 |
|2023-05-11| 1.3 | Eric Hao &amp; Vladislav Boyko | Updated Page Frames |
|2023-05-10| 1.2 | Eric Hao &amp; Vladislav Boyko | Updated Page Frames |
|2023-05-10| 1.1 | Eric Hao &amp; Vladislav Boyko | Updated Page Frames |
|2023-05-10| 1.0 | Eric Hao &amp; Vladislav Boyko | Updated Page Frames |
| 2021-08-05 | 0.1 | John Rofrano | Initial version created |
## <h3 style="align:center;">IBM Corporation 2023. All rights reserved. <h3>
