---
title: Leave feedback with pull requests
intro: You can leave feedback for your students in a special pull request within the repository for each assignment.
permissions: People with read permissions to a repository can leave feedback in a pull request for the repository.
versions:
  free-pro-team: '*'
redirect_from:
  - /education/manage-coursework-with-github-classroom/leaving-feedback-in-github
---

### About feedback pull requests for assignments

{% data reusables.classroom.you-can-create-a-pull-request-for-feedback %}

When you enable the pull request for feedback for an assignment, {% data variables.product.prodname_classroom %} will create a special pull request titled **Feedback** in the assignment repository for each student or team. The pull request automatically shows every commit that a student pushed to the assignment repository's default branch.

### Pré-requisitos

To create and access the feedback pull request, you must enable the feedback pull request when you create the assignment. {% data reusables.classroom.for-more-information-about-assignment-creation %}

### Leaving feedback in a pull request for an assignment

{% data reusables.classroom.sign-into-github-classroom %}
1. In the list of classrooms, click the classroom with the assignment you want to review. ![Classroom in list of classrooms for an organization](/assets/images/help/classroom/click-classroom-in-list.png)
{% data reusables.classroom.click-assignment-in-list %}
1. To the right of the submission, click **Review**. ![Review button for assignment in list of submissions for an assignment](/assets/images/help/classroom/assignments-click-review-button.png)
1. Review the pull request. Para obter mais informações, consulte "[Comentando em uma pull request](/github/collaborating-with-issues-and-pull-requests/commenting-on-a-pull-request)."

### Leia mais

- "[Integrate {% data variables.product.prodname_classroom %} with an IDE](http://localhost:4000/en/free-pro-team@latest/education/manage-coursework-with-github-classroom/integrate-github-classroom-with-an-ide)"
