# Lab 4: Refine your Product Backlog

**Estimated time needed:** 20 minutes

In this lab, you will follow the steps of conducting a backlog refinement meeting. You will be the product owner getting the product backlog ready for your next sprint planning meeting. This involves grooming the stories we created in the last lab to make them *sprint ready*.

::page{title&#x3D;&quot;Objectives&quot;}

After completing this lab, you will be able to:

1. Triage new issues.
1. Make stories sprint ready.
1. Create new labels in GitHub.
1. Add labels to stories.

---

## Initial State

At the completion of [Lab 3](../lab_3/lab3-assemble-product-backlog.md), your kanban board should look like this:

![finished kanban](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_4/images/lab4-zenhub-starting-kanban.png)

**New Issues:**

- Deploy service to the cloud
- Need the ability to remove a counter
- Need ability to update a counter to a new value

**Icebox:**

- Must allow multiple counters

**Product Backlog:**

- Need a service that has a counter
- Must persist counter across restarts
- Counters can be reset

---

## Exercise 1 : Triage new issues

In this exercise, you will take all of the stories in the **New Issues** pipeline and move them to an appropriate pipeline or reject them.

1. Go to [app.zenhub.com](http://app.zenhub.com/?utm_medium&#x3D;Exinfluencer&amp;utm_source&#x3D;Exinfluencer&amp;utm_content&#x3D;000026UJ&amp;utm_term&#x3D;10006555&amp;utm_id&#x3D;NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMCD0116ENSkillsNetwork857-2023-01-01) and sign in with your GitHub account and bring up your kanban board.
    ![initial kanban](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_4/images/lab4-zenhub-initial-board.png)

1. The first new issue is **Deploy service to the cloud**. We want to do that after adding persistence, so move that to the **Product Backlog** pipeline under **Must persist counter across restarts**.
    ![new issue](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_4/images/lab4-zenhub-move-issue-5.png)

1. The next new issue is **Need the ability to remove a counter**. We only have one counter and we wouldn&#x27;t want to remove that, so let&#x27;s move that to the **Icebox** after  **Must allow multiple counters**.
    ![new issue](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_4/images/lab4-zenhub-move-issue-6.png)

1. The last new issue is **Need ability to update a counter to a new value**. We might want to do that as an enhancement after we can reset the counter, so let&#x27;s move that to the **Product Backlog** after **Counters can be reset**.
    ![new issue](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_4/images/lab4-zenhub-move-issue-7.png)

You have now completed new issue triage and can start making the stories in the **Product Backlog** pipeline sprint ready.

---

## Exercise 2 : Make stories sprint ready

In this exercise, you will add more details to the stories in the **Product Backlog** that you feel might make it into the next sprint. You will be provided with the details for two of the stories. You must provide the details for the other three.

1. Select the first story at the top of the **Product Backlog** pipeline to open it. Then press the **Edit** button to edit the issue.
    ![edit issue 1](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_4/images/lab4-zenhub-edit-issue-1.png)

1. Edit the **Details and Assumptions** to let developers know what we know, and edit the **Acceptance Criteria** to make sure that everyone understands what the definition of &quot;*done*&quot; is. Make your story look like this one:  
    ![issue 1 content](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_4/images/lab4-zenhub-content-issue-1.png)

1. When you are finished editing, press the **Update** button to save the edits.
    ![update issue 1](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_4/images/lab4-zenhub-update-issue-1.png)

1. Close the window by pressing the **X** icon.
    ![refined issue 1](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_4/images/lab4-zenhub-refined-issue-1.png)

1. Edit the **Must persist counter across restarts** story in the same way and make it look like the following:
    ![issue 1 content](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_4/images/lab4-zenhub-content-issue-2.png)

1. Edit the **Deploy service to the cloud** story and make up your own **Details and Assumptions**, and **Acceptance Criteria**.

1. Edit the **Counters can be reset** story and make up your own details, assumptions, and acceptance criteria.

1. Edit the **Need ability to update a counter to a new value** story and make up your own details, assumptions, and acceptance criteria.

At the completion of this exercise, your kanban board should have sufficient details in all of the stories in the **Product Backlog** to make them sprint ready.

---

## Exercise 3 : Create new labels in GitHub

In this exercise, you will create a new label in GitHub called &#x60;technical debt&#x60; to flag those stories that provide no visible customer value but must be completed in order to continue development.

1. Go to [github.com](http://www.github.com) and select your **lab-agile-planning** repository.
    ![select reo](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_4/images/lab4-github-select-repo.png)

1. From your repository page, select the **Issues** tab.
    ![select issues](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_4/images/lab4-github-select-issues.png)

1. From the issues page, select the **Labels** button.
    ![select labels](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_4/images/lab4-github-select-labels.png)

1. From the labels page, select the **New label** button.
    ![new label](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_4/images/lab4-github-select-new-label.png)

1. In the new label section: (1) set the **Label name** to &#x60;technical debt&#x60;, (2) set the **Color** to &#x60;yellow&#x60; (&#x60;#FBCA04&#x60;), then (3) press the **Create label** button.
    ![technical debt](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_4/images/lab4-github-label-technical-debt.png)

1. You should now see a yellow &#x60;technical debt&#x60; label that we can use to annotate our stories.
    ![label complete](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_4/images/lab4-github-label-complete.png)

---

## Exercise 4 : Add labels to stories

In this exercise, you will go back to ZenHub and add labels to the stories in the **Product Backlog** to further make them sprint ready. You will also use our new label called &#x60;technical debt&#x60; to flag those stories that provide no visible customer value but must be completed to continue development.

1. Go to ZenHub and select the first story at the top of the **Product Backlog** pipeline to open it. Then press the **Gear** icon next to **Labels** to assign a label.
    ![open labels](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_4/images/lab4-zenhub-labels-open.png)

1. Our first story is an enhancement to our product. From the label menu, select **enhancement** to reflect this.
    ![assign labels](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_4/images/lab4-zenhub-labels-assign.png)

1. Click anywhere off of the labels menu to close it. You should now see that the label **enhancement** has been assigned to this story.
    ![assign labels](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_4/images/lab4-zenhub-labels-enhancement.png)

1. Select each of the following stories in the **Product Backlog** pipeline and assign them the corresponding labels.

    | Story Title | Label |
    |-------|-------|
    | Must persist counter across restarts | enhancement |
    | Deploy service to the cloud | technical debt |
    | Counters can be reset | enhancement |
    | Need ability to update a counter to new value | enhancement |

At the end of this exercise, your kanban board should look like this:

![labeled kanban](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_2/lab_4/images/lab4-zenhub-labeled-kanban.png)

## Summary

You learned how to triage new issues, add detail to stories to make them sprint ready, create new labels, and assign labels to stories in preparation for a sprint planning meeting.

## Author(s)

[John Rofrano](https://www.coursera.org/instructor/johnrofrano?utm_medium&#x3D;Exinfluencer&amp;utm_source&#x3D;Exinfluencer&amp;utm_content&#x3D;000026UJ&amp;utm_term&#x3D;10006555&amp;utm_id&#x3D;NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMCD0116ENSkillsNetwork857-2023-01-01)

## Changelog
| Date | Version | Changed by | Change Description |
|------|--------|--------|---------|
|2023-05-11| 1.3 | Eric Hao &amp; Vladislav Boyko | Updated Page Frames |
|2023-05-10| 1.2 | Eric Hao &amp; Vladislav Boyko | Updated Page Frames |
|2023-05-10| 1.1 | Eric Hao &amp; Vladislav Boyko | Updated Page Frames |
|2023-05-10| 1.0 | Eric Hao &amp; Vladislav Boyko | Updated Page Frames |
| 2021-08-06 | 0.1 | John Rofrano | Initial version created |
## <h3 style="align:center;">IBM Corporation 2023. All rights reserved. <h3>
