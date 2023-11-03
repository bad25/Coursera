**Estimated time needed:** 20 minutes

In this lab, you will prepare for the labs that follow by setting up a free GitHub account and a free ZenHub account.

## Objectives

After completing this lab, you will be able to:

1. Create a free GitHub account.
1. Create a GitHub repository.
1. Create a free ZenHub account.
1. Install the optional browser extension for ZenHub.

## Exercise 1 : Create a free GitHub account

In this exercise, you will create a free GitHub account, if you don\&#x27;t already have one. ZenHub requires GitHub so this first step is a prerequisite to getting a ZenHub account.

1. Go to [GitHub.com](http://github.com) and sign up for a free GitHub account.

1. Enter your email address and press the **Sign up for GitHub** button. If you have an account, press the **Sign in** button and login.

    ![Github signup screen](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_1/images/lab1-github-sign-up.png)

## Exercise 2 : Create a GitHub repository

In this exercise, you will create a repository to hold the issues and kanban board for your plan.

1. If you just created your GitHub account, create your first repository by pressing the **Create repository** button, then go to step **3**.

    ![create repository](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_1/images/lab1-github-create-repository.png)

1. If you already have a GitHub account, sign into GitHub and on your account page, press the **New** repository button.

    ![new repository](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_1/images/lab1-github-new-repository.png)

1. Name your repository **lab-agile-planning** and give it a good description like: _This repository contains the lab for agile planning_ and make sure the **Public** option is selected.

    ![name repository](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_1/images/lab1-github-name-repository.png)

1. Scroll down on that page and select **Add a README file** and then press the **Create repository** button to create the new repository.

    ![press create](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_1/images/lab1-github-press-create.png)

You should now have a new repository called **lab-agile-planning** that we will use with ZenHub. It should look similar to the screenshot below:
    ![repository created](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_1/images/lab1-github-repository-created.png)

## Exercise 3 : Create free ZenHub account

In this exercise, you will create a free ZenHub account to use with GitHub. ZenHub is an application that integrates with GitHub. In order to use it, you must sign up for a free account.

1. Go to www.zenhub.com and press the [Try for free](https://www.zenhub.com/sign-up) button. Even though it says &quot;*Start your free 14-day trial with ZenHub*&quot; you can continue to use ZenHub for free on open source projects.

    ![ZenHub home page](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_1/images/lab1-zenhub-homepage.png)

1. On the next page, you need to enter your Email ID and a strong Password to create a new ZenHub account.

    ![get started](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_1/images/lab1-sign-up.png)

	&gt; Note: Alternate way, press the **Sign up with Google** button if you have a google account already and want to use that on ZenHub and then login using your Google/Gmail credentials.

1. Enter whatever you want for this ZenHub survey and press **Submit**

    ![survey](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_1/images/lab1-zenhub-survey.png)

1. On the next page, enter your organization name.

    ![organization](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_1/images/lab1-org.png)

1. Once you have successfully entered your organization name, you may be prompted to connect with your GitHub account. Press the **Connect with GitHub** button.

    ![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/Connect%20with%20GitHub.jpg)

1. You can also connect to your GitHub account from your kanban Board by clicking the **Connect your GitHub account** button.

    ![sign in](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_1/images/lab1-connect-to-github.png)

1. Since you are already signed into GitHub from the previous steps, you should be presented with a page that will allow you to authorize ZenHubIO to access your GitHub account.
    ![authorize zenhub](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_1/images/lab1-zenhub-authorize-zenhubio.png)

1. (optional) If you are not signed into GitHub, you will be prompted to sign in to GitHub. That will bring you to a page where you must use your GitHub credentials.
    ![github credentials](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_1/images/lab1-zebhub-github-credentials.png)

1. If you have two-factor authentication enabled on your GitHub account, you must enter your authorization code now.
    ![two factor auth](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_1/images/lab1-zenhub-two-factor-auth.png)

1. Accept ZenHub\&#x27;s privacy policy
    ![privacy policy](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_1/images/lab1-zenhub-privacy-policy.png)

1. On your kanban board, click on **Add repositories** to add repositories to Development workspace.
    ![add repos](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_1/images/lab1-add-repo.png)

1. On the next page, assign the name &quot;**Development**&quot; to your new ZenHub workspace and click on **Add repos** under connect repositories.
      ![add repos](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_1/images/lab1-add-repo2.png)

1. Select **lab-agile-planning** repository that you created in the previous steps, then click on **Add**.

1. This will place you in your kanban board for the &#x60;lab-agile-planning&#x60; repository.
    ![kanban board](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_1/images/lab1-zenhub-kanban-board.png)

## Exercise 4 : (Optional) Browser extension for Chrome or Firefox

In this optional exercise, you will download a browser extension for ZenHub.

If you use Chrome or Firefox, you can download a browser extension for ZenHub that will add a ZenHub tab while you are using GitHub so that you don&#x27;t have to go to zenhub.com to view your kanban board.

1. Download a browser extension for ZenHub here: [www.zenhub.com/extension](https://www.zenhub.com/extension). Once installed, it will add a ZenHub tab while you are using GitHub. This is purely a convenience. The capabilities of both the browser extension and the web zenhub.com site are the same.

## Summary

Congratulations! You are now set up with a ZenHub account and GitHub account so that you can work through the rest of the labs.

## Author(s)

[John Rofrano](https://www.coursera.org/instructor/johnrofrano)

## Changelog
| Date | Version | Changed by | Change Description |
|------|--------|--------|---------|
|2023-05-11| 0.6 | Eric Hao &amp; Vladislav Boyko | Updated Page Frames |
|2023-05-10| 0.5 | Eric Hao &amp; Vladislav Boyko | Updated Page Frames |
|2023-05-10| 0.4 | Eric Hao &amp; Vladislav Boyko | Updated Page Frames |
|2023-05-10| 0.3 | Eric Hao &amp; Vladislav Boyko | Updated Page Frames |
| 2021-08-03 | 0.1 | John Rofrano | Initial version created |
| 2022-04-27 | 0.2 | Srishti Srivastava | Updated steps as per new ZenHub sign up |
## <h3 style="align:center;">IBM Corporation 2023. All rights reserved. <h3>
