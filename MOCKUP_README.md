# Sprint1-MockUp

## bpmn daigram
![7fca8523.png](https://github.com/Micro-Workflow/waterflow-frontend/raw/lacee/feature-02/MockupScreenPics/sprint-1.png)

## Frontend Mockup

### Roles
- Unregistered User
- Registered User
  - Admin
  - Designer
  - Developer
  - Aprover

`Unregistered User` The user who first explores our product. They will see our landing page to view our product's feature, and click **sign in** or **sign up for free** to redirect to **workspace**.

#### Landing page
![ed1c2b4b.png](https://github.com/Micro-Workflow/waterflow-frontend/raw/lacee/feature-02/MockupScreenPics/LandingPage.png)

#### Sign up page
![31cfa7ee.png](https://github.com/Micro-Workflow/waterflow-frontend/raw/lacee/feature-02/MockupScreenPics/SignUp.png)

#### Sign in page
![b810d493.png](https://github.com/Micro-Workflow/waterflow-frontend/raw/lacee/feature-02/MockupScreenPics/SignIn.png)

#### Workspace
The workspace will show all the workspace the user has to manage or join.
For each workspace, there are four roles: `Admin`, `Designer`, `Developer`, `Approver`.
- If the user click **Create Workspace**, this user will become an `Admin` of this workspace by default. 
- If the user click **Join Workspace**, this user needs to type the workspace name and invitation code. The role is already assigned by the workspace's admin. This user will be either `Designer`, `Developer` or `Approver`.

![e421542a.png](https://github.com/Micro-Workflow/waterflow-frontend/raw/lacee/feature-02/MockupScreenPics/WorkSpace.png)

`Designer`: If join a Designer role workspace, this user will get into **Workflow for Designer App**
- Canvas: The designer can create a task and draw the flow on the canvas
![9b1b6ef4.png](https://github.com/Micro-Workflow/waterflow-frontend/raw/lacee/feature-02/MockupScreenPics/DesignerCanvas.png)
- Task Overview: The designer can configure input/output information and assign a developer for each task.
![444e654d.png](https://github.com/Micro-Workflow/waterflow-frontend/raw/lacee/feature-02/MockupScreenPics/DesignerTaskOverview.png)
![5a1b4395.png](https://github.com/Micro-Workflow/waterflow-frontend/raw/lacee/feature-02/MockupScreenPics/DesignerTaskToggle.png)

`Developer`: If join a Developer role workspace, this user will get into **Workflow for Developer App**


![32a941e0.png](https://github.com/Micro-Workflow/waterflow-frontend/raw/lacee/feature-02/MockupScreenPics/DeveloperTaskOverview.png)
Each task has the status: waiting, accepted, submitted, completed, failure.

The user can click **Detail** to see more information for a specific task and give an action.
![f8049e58.png](https://github.com/Micro-Workflow/waterflow-frontend/raw/lacee/feature-02/MockupScreenPics/DeveloperTaskDetail.png)

`Approver`: If join an Approver role workspace, this user will get into **Workflow for Approver App**

Approver App logic is similar to Developer. Approver can overview all the procedures received. For each procedure, there is two status: Waiting, Submitted. Approver can click detail to see more information about each procedure and make actionable decisions.

![https://github.com/Micro-Workflow/waterflow-frontend/raw/lacee/feature-02/MockupScreenPics/ApproverOverview.png)
![https://github.com/Micro-Workflow/waterflow-frontend/raw/lacee/feature-02/MockupScreenPics/ApproverDetail.png)

`Admin`: If you are an admin, this user will get into **Workflow for Admin App**
You can view all the workflow as well as add or delete different roles in this workspace.
![3df68224.png](https://github.com/Micro-Workflow/waterflow-frontend/raw/lacee/feature-02/MockupScreenPics/AdminOverview.png)
![85000656.png](https://github.com/Micro-Workflow/waterflow-frontend/raw/lacee/feature-02/MockupScreenPics/AddMember.png)




