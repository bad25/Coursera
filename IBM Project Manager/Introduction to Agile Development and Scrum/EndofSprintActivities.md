# Lab 8: End of Sprint Activities

**Estimated time needed:** 10 minutes

In this lab, you will close out the current sprint by moving done stories to closed, dealing with unfinished stories. 

::page{title&#x3D;&quot;Objectives&quot;}

After completing this lab, you will be able to:

1. Determine which stories to close complete a sprint.
1. Deal with unfinished work.

---

## Exercise 1 : Move Done stories to Closed

In this exercise, you will move all of the done stories that the product owner has deemed completed at the sprint review to the Closed pipeline.

1. Go to [app.zenhub.com](http://app.zenhub.com/?utm_medium&#x3D;Exinfluencer&amp;utm_source&#x3D;Exinfluencer&amp;utm_content&#x3D;000026UJ&amp;utm_term&#x3D;10006555&amp;utm_id&#x3D;NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMCD0116ENSkillsNetwork857-2023-01-01) and sign in with your GitHub account and bring up your kanban board.
    ![initial kanban](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_3/lab_8/images/lab8-initial-kanban.png)

1. At the sprint review meeting, the product owner agreed that all of the stories that we demonstrated meet the definition of done, per the **Acceptance Criteria** in the **Issue** and can now be closed. Move all of the stories from the **Done** pipeline to the **Closed** pipeline.
    ![done to closed](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_3/lab_8/images/lab8-move-done-to-closed.png)

At the end of this exercise, your kanban board should look like this:
    ![stories closed](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_3/lab_8/images/lab8-stories-closed.png)

---

## Exercise 2 : Deal wth unfinished work

In this exercise, you will deal with the unfinished stories in the sprint. These are stories that the team has started, but not completed. We want to adjust the estimate to take credit for the story points expended so that it is reflected in the teams velocity, and create a new story to finish the work in the next sprint.

1. Select the story &quot;*Deploy service to the cloud*&quot; in the **In Progress** pipeline to open it.
    ![open story](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_3/lab_8/images/lab8-select-unfinished-story.png)

1. Click the **Gear** next to **Estimate** to open the dropdown.
    ![open estimates](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_3/lab_8/images/lab8-click-estimates.png)

1. The developer has determined that they did not expend **5** story points of effort on this story and just ran out of time. They estimated that **2** story points were expended. Select **2** from the dropdown list to change the story points to **2**.
    ![change story points](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_3/lab_8/images/lab8-change-estimate-2.png)

1. We can see that the story points are now set to **2**. Click the **X** to close the window.
    ![close window](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_3/lab_8/images/lab8-close-window.png)

1. Now the story points have been adjusted to reflect the effort that was made in this sprint. Move this story to the **Closed** pipeline.
    ![close unfinished](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_3/lab_8/images/lab8-move-unfinished-to-closed.png)

1. We want to create a new story to document the remaining work. Press the **New Issue** button.
    ![new issue](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_3/lab_8/images/lab8-new-issue.png)

1. Since we know this new issue is going into the **Product Backlog** pipeline, click the gear icon next to **Pipelines** to open the dropdown list.
    ![open pipelines](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_3/lab_8/images/lab8-open-pipeline-new-issue.png)

1. Select **Product Backlog** from the dropdown list.
    ![assign pipeline](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_3/lab_8/images/lab8-assign-new-issue-pipeline.png)

1. Set the **Estimate** to **3**, which represents the remaining story points from the unfinished story. Set the label to &#x60;technical debt&#x60;, just like the original story.
    ![assign estimate](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_3/lab_8/images/lab8-assign-estimate-labels.png)

1. Fill in the new issue with the remaining details to complete the story. (*Hint: You may want to copy and paste some details from the unfinished story as a starting point*.) When completed, press the **Submit new Issue** button.
    ![submit issue](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_3/lab_8/images/lab8-submit-new-issue.png)

1. Be sure the story is at the top of the **Product Backlog** pipeline to be selected for the next sprint.
![check backlog](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_3/lab_8/images/lab8-check-product-backlog.png)

Congratulations! You can completed all of the end of sprint activities.

## Summary

You learned how to conduct the activities required to close out a sprint. You moved done stories to closed, adjusted unfinished stories to reflect the true effort, and created new stories to document the remaining work. ZenHub will automatically close the sprint when it&#x27;s end date has expired so there is nothing for you to do there. *Bonus: After the end of sprint date is passed, you might want to go back and look at your Velocity chart under Reports to see the teams velocity reflected in the chart*.

## Author(s)

[John Rofrano](https://www.coursera.org/instructor/johnrofrano?utm_medium&#x3D;Exinfluencer&amp;utm_source&#x3D;Exinfluencer&amp;utm_content&#x3D;000026UJ&amp;utm_term&#x3D;10006555&amp;utm_id&#x3D;NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMCD0116ENSkillsNetwork857-2023-01-01)

## Changelog
| Date | Version | Changed by | Change Description |
|------|--------|--------|---------|
|2023-05-11| 0.6 | Eric Hao &amp; Vladislav Boyko | Updated Page Frames |
|2023-05-10| 0.5 | Eric Hao &amp; Vladislav Boyko | Updated Page Frames |
|2023-05-10| 0.4 | Eric Hao &amp; Vladislav Boyko | Updated Page Frames |
|2023-05-10| 0.3 | Eric Hao &amp; Vladislav Boyko | Updated Page Frames |
| 2021-08-08 | 0.1 | John Rofrano | Initial version created |
| 2022-01-14 | 0.2 | John Rofrano | Removed Milestones |
