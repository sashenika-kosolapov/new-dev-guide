# Flight rules for New Dev

#### What are "flight rules"?

A guide for astronauts (now programmers who got into our project) about how to understand the project the fastest.

> Flight rules - a set of aviation rules and instructions providing for the performance of flights in conditions in which the location, spatial position and flight parameters of the aircraft are determined by the indications of flight navigation instruments.

#### Conventions for this project
To begin with, you should not send unnecessary spaces. Git provides an easy way to check — before committing, run the command "git diff --check`, which will output a list of unnecessary spaces. By executing this command before committing, you will be able to avoid sending unnecessary spaces that may annoy other developers. Next, try to commit a logically separated set of changes. If possible, try to make your changes easily understandable — you don't need to write code all weekend working on five different tasks, and on Monday send the result as one big commit. Even if you did not commit on the weekend, then on Monday use the prepared files area to divide the work done according to the principle of at least one commit per task, giving useful comments to each of them. This approach also makes it easier to extract or undo individual changes if it is suddenly needed in the future.

The last thing to keep in mind is the commit message. The habit of creating high-quality commit messages makes it easier to use and interact with Git. As a rule, your messages should begin with a short one-line description of no more than 50 characters, followed by an empty line, followed by a more detailed description. The Git project requires a detailed description to include the reason for the changes and a comparison with the current implementation — this is a good example to follow. Write the commit message in the imperative: "Fix bug" and not "Fixed bug" or "Fixes bug". 

Let's look at a simple example of a workflow that can be useful in your project. Your work is structured like this: You are working on a website, you are creating a branch for a new file that you are writing, you are working in this branch. At this point, you receive a message that a critical error has been detected that requires a speedy fix. Your actions: switch to the main branch, create a branch to add a fix, after testing merge the branch containing the fix with the main branch, switch back to the branch where you are writing code and continue working. You can read more about this [тут](https://git-scm.com/book/ru/v2/%D0%92%D0%B5%D1%82%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5-%D0%B2-Git-%D0%9E%D1%81%D0%BD%D0%BE%D0%B2%D1%8B-%D0%B2%D0%B5%D1%82%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F-%D0%B8-%D1%81%D0%BB%D0%B8%D1%8F%D0%BD%D0%B8%D1%8F).

### Kanban 
The project uses the Kanban methodology. This is a development management method that implements the "just-in-time" principle and promotes an even distribution of workload among employees. With this approach, the entire development process is transparent to all team members. Tasks are entered into a separate list as they arrive, from where each developer can extract the required task. Read more [here](https://www.atlassian.com/ru/agile/kanban ).

### Front-end
[Flight rules Front-End.md](Front-End.md)

### Back-end
[Flight rules Back-End.md](Back-End.md)


