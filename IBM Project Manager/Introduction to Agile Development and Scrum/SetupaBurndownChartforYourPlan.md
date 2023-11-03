# Lab 7: Setup a Burndown Chart for Your Plan

**Estimated time needed:** 10 minutes

In this lab, you will set up a burndown chart for your plan. In most cases, the burndown chart is created automatically by ZenHub if you have set the start and end dates of your sprint correctly. There is still some setup to do to customize it to show stories that are done, but not closed. These changes are not permanent and will need to be made whenever you view your burndown charts.

::page{title&#x3D;&quot;Objectives&quot;}

After completing this lab, you will be able to:

1. Understand how to set up your burndown chart.
1. See the data that is contained in a burndown chart.
1. Judge your progress in the sprint.

---

## Exercise 1 : Set up your burndown chart

In this exercise, you will set up your burndown chart to show the status of the **Done** pipeline stories instead of the default **Closed** stories.

Since a burndown chart shows the story points completed vs. the time left in a sprint, it will be difficult to simulate in a one-day lab. Hopefully, you created a sprint that included the date that you performed the previous lab on the topic of daily execution. For best results, it is recommended that you wait a few days after that lab before performing this lab so that the passage of time will be reflected on the burndown chart.

1. Go to [app.zenhub.com](http://app.zenhub.com/?utm_medium&#x3D;Exinfluencer&amp;utm_source&#x3D;Exinfluencer&amp;utm_content&#x3D;000026UJ&amp;utm_term&#x3D;10006555&amp;utm_id&#x3D;NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMCD0116ENSkillsNetwork857-2023-01-01) and sign in with your GitHub account. Bring up your kanban board and click the **&gt;&gt;** icon in the lower left-hand corner to open the side menu bar.
    ![zenhub kanban](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_3/lab_7/images/lab7-initial-kanban.png)

1. From the side menu bar, select **Reports**.
    ![side menu](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_3/lab_7/images/lab7-side-menu-reports.png)

1. From the reports menu, select **Burndown Report**.
    ![report burndown](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_3/lab_7/images/lab7-side-menu-burndown.png)

1. Make sure the current sprint is selected. You can change the sprint using the dropdown list. Since we only have one sprint, the current sprint should already be selected.
    ![select sprint](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_3/lab_7/images/lab7-select-sprint.png)

1. Notice that the burndown chart isn&#x27;t burning down. We just have a straight line across the top. This is because, by default, the burndown measures closed stories. Since we want to keep our stories in the **Done** pipeline before the sprint review, select the **Burn Pipelines** dropdown to change this behavior.
    ![select burn pipelines](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_3/lab_7/images/lab7-select-burn-pipelines.png)

1. From the **Burn Pipelines** drop down, select **Done** to show the status of the stories that are done.
    ![select done](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_3/lab_7/images/lab7-select-done-pipeline.png)

1. You can now see the status of the sprint in the burndown chart. Since you completed your stories in a single lab, there is one big drop in the progress. Normally this would be more gradual. Notice that we are well below the dotted line, which is a projection of where we should be at this time.
    ![burndown chart](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_3/lab_7/images/lab7-burndown-chart.png)

1. If you hover, using your mouse, over any of the blue dots on the burndown line, you will see a pop-up with the stories that contributed to that event. These are the stories that you moved to **Done** in the previous lab.
    ![hover over](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_3/lab_7/images/lab7-hover-over.png)

1. If you scroll down, you will see one status bar for the number of story points completed and remaining in the sprint, and another status bar showing the number of issues and pull requests completed and remaining. This gives a nice visual indicator of how far along you are. Below the status bars you will see the detailed status of all of the stories in your sprint. The detailed status lets you quickly see which stories are completed and which still need work.
    ![sprint status](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0116EN-SkillsNetwork/labs/module_3/lab_7/images/lab4-sprint-status.png)

## Summary

You learned how to set up a burndown chart to show the status of the done stories in your sprint. You also learned how to use the progress bars to get a visual status of where you are in the sprint, and see the status of individual stories. This information should help you get a good sense of how the work is progressing.

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
| 2022-01-14 | 0.2 | John Rofrano | Updated for Sprints |
## <h3 style="align:center;">IBM Corporation 2023. All rights reserved. <h3>
