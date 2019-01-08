<!-- add-breadcrumbs -->
# Project

The project is an individual or collaborative enterprise, involving various types of tasks like research, design, execution, documentation that is carefully planned, usually by a project team, to achieve a particular aim.

In ERPNext, Project management in is 'Task' driven. You can a create Project with multiple and assignable Tasks.

<img class="screenshot" alt="Project" src="{{docs_base_url}}/assets/img/project/project-1.1.png">

### Defining Tasks

The project generally has a broader scope and the tasks within a project have specific scope and are executed by individual members.

These Tasks can be created from a Project itself or a [Task](/docs/user/manual/en/projects/tasks.html) can be created separately as well.

Tasks can be assigned to specific users using 'Assign' feature in task.

<img class="screenshot" alt="Project" src="{{docs_base_url}}/assets/img/project/project-1.png">

### Project Completion Status

You can configure the way completion status of each project is calculated.

  1. Based on **Task Completion:** The overall project's status can be computed solely based on the number of tasks completed.
     If there are 10 tasks in the project, and 5 tasks are in 'Closed' status, then overall project completion status will be 50%.
     In this method each task carries equal weightage.
  2. Based on **Task Progress:**   The overall project's status can be completed based on the percentage of completion of individual tasks.
     If there are two tasks in the project and one task is 50% complete, then overall project is 25% complete.
  3. Based on **Task Weight:** Some projects will have tasks with different weightage. Let's say an ERPNext feature development project has
  requirement gathering, design, development, testing, and documentation tasks. Whole project is expected to be completed in 10 hours. Development is
  expected to take take 6 hours and each of the remaining tasks 1 hour. In this project you can set the weightage of development task to 0.6 and for all other tasks 0.1, Please note the sum of weights assigned to all tasks should be equal to 1.

<img class="screenshot" alt="Project 2" src="{{docs_base_url}}/assets/img/project/project-2.png">

Some examples of how the % Completion is calculated based on Tasks.

<img class="screenshot" alt="Project 3" src="{{docs_base_url}}/assets/img/project/percent-complete-calc.png">

<img class="screenshot" alt="Project 4" src="{{docs_base_url}}/assets/img/project/percent-complete-formula.png">

### Project Costing

The Project Costing section helps you track the time, expenses and purchases incurred against the project.

<img class="screenshot" alt="Project - Costing" src="{{docs_base_url}}/assets/img/project/project_costing.png">

* The Total Cost is composed of the costing amount from timesheets, the total cost of expense claims and the total cost of purchase invoices created against this project.

* The Gross Margin is the difference between Total Billed Amount and the Total Cost Amount for this project.

### Gantt Chart

ERPNext gives you an illustrated view of tasks scheduled for that project in Gantt Chart View.

* To view Gantt chart against a project, go to the Task list and Apply filter on the Project.

<img class="screenshot" alt="Project Gantt" src="{{docs_base_url}}/assets/img/project/project-1.1.png">

### Project Help Video

This is a tutorial video on how to manage Project and associate Tasks in ERPNext.

<div class="embed-container">
  <iframe src="https://www.youtube.com/embed/gCzShu9Niu4?rel=0" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen>
  </iframe>
</div>

{next}
