# Sprint1-MockUp

## bpmn daigram
![7fca8523.png](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/14706d9b-295a-4496-bd74-cae3a8621108/BPMN-diagram.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20210212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20210212T021937Z&X-Amz-Expires=86400&X-Amz-Signature=cca9f83795f15e5296b4c8e235753500bef51671939a1f61cd9e1c4d1b83e32d&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22BPMN-diagram.png%22)

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
![ed1c2b4b.png](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/5f74eeb2-d732-4d39-b588-fb221ec456e5/LandingPage.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20210212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20210212T022002Z&X-Amz-Expires=86400&X-Amz-Signature=cce1a07b3a026576961b82c14834485caac5c6d7d9923790dc1a2642ca64b0f2&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22LandingPage.png%22)

#### Sign up page
![31cfa7ee.png](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/febb9dae-8dfe-45b0-aef0-1d5acbf9a53c/SignUp.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20210212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20210212T022017Z&X-Amz-Expires=86400&X-Amz-Signature=0ae1cdf4036546b5cdf6be1d6c523e4c842b90c4de6be8f260e4997d67c10ce2&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22SignUp.png%22)

#### Sign in page
![b810d493.png](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/431bbef4-e2a0-4de6-8bc5-4e460718d8c1/SignIn.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20210212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20210212T022032Z&X-Amz-Expires=86400&X-Amz-Signature=6c2d0d755d178bb0d71fc710be105f52497531b0cee22c1bc0d34aa27fa69708&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22SignIn.png%22)

#### Workspace
The workspace will show all the workspace the user has to manage or join.
For each workspace, there are four roles: `Admin`, `Designer`, `Developer`, `Approver`.
- If the user clicks **Create Workspace**, this user will become an `Admin` of this workspace by default. 
- If the user clicks **Join Workspace**, this user needs to type the workspace name and invitation code. The role is already assigned by the workspace's admin. This user will be either `Designer`, `Developer`, or `Approver`.

![e421542a.png](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/331fe9bf-911d-4b3e-84cf-65e1ea3f28fc/WorkSpace.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20210212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20210212T022057Z&X-Amz-Expires=86400&X-Amz-Signature=5b99b6227c03b972cecf6c11ed3dbdb529899df08371f6cfa8087c75a2ac2c36&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22WorkSpace.png%22)

`Designer`: If join a Designer role workspace, this user will get into **Workflow for Designer App**
- Canvas: The designer can create a task and draw the flow on the canvas
![9b1b6ef4.png](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/5ac9817f-9aa2-48d8-ac59-97f76a956de5/DesignerCanvas.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20210212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20210212T022127Z&X-Amz-Expires=86400&X-Amz-Signature=c509f31d55ad6f9b1a062a71cf4c8b7d001f3a551ed00ddc907d47241950c0c8&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22DesignerCanvas.png%22)
- Task Overview: The designer can configure input/output information and assign a developer for each task.
![444e654d.png](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/f16ed390-59c8-401d-8a01-7899d73a7e67/DesignerTaskOverview.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20210212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20210212T022625Z&X-Amz-Expires=86400&X-Amz-Signature=14247128fd7bc0d478b53a6ce60c53ae8523a52d1220cc49be768fe2bf85ae55&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22DesignerTaskOverview.png%22)
![5a1b4395.png](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/3bb2bb82-eae0-4828-a984-3b811fd2d45c/DesignerTaskToggle.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20210212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20210212T022645Z&X-Amz-Expires=86400&X-Amz-Signature=707672f4c9f259ef3b42f61a0c3afa56d6b7dbb9be98571edcffe7a8ca8cd2fc&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22DesignerTaskToggle.png%22)

`Developer`: If join a Developer role workspace, this user will get into **Workflow for Developer App**


![32a941e0.png](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/d4bd8079-2361-4839-b77a-79814f03aa95/DeveloperTaskOverview.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20210212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20210212T022924Z&X-Amz-Expires=86400&X-Amz-Signature=52235686f86e4a0e0bfaacc1d08be2ba4a15e623c7429fde2345f2566a70e473&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22DeveloperTaskOverview.png%22)
Each task has the status: waiting, accepted, submitted, completed, failure.

The user can click **Detail** to see more information for a specific task and give an action.
![f8049e58.png](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/9b5a6c23-d2fc-4b7c-8ef4-353f23ab2a03/DeveloperTaskDetail.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20210212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20210212T022242Z&X-Amz-Expires=86400&X-Amz-Signature=f698c29ffe715171401da1a38a892313357811cc51bc3a26cc4e1d99639d95f2&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22DeveloperTaskDetail.png%22)

`Approver`: If join a Approver role workspace, this user will get into **Workflow for Approver App**

Approver App logic is similar to Developer. Approver can overview all the procedures received. For each procedure, there is two status: Waiting, Submitted. Approver can click detail to see more information about each procedure and make actionable decisions.

![3df68224.png](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/e74ee6e9-7c37-40b8-8c68-a7c8127412b3/ApproverOverview.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20210212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20210212T022255Z&X-Amz-Expires=86400&X-Amz-Signature=c8bd451a176e52e75363d324a43d24e5d4603fef73c4bc23da0c6496653b2e55&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22ApproverOverview.png%22)
![85000656.png](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/9ee7d314-a2d7-459a-9fdc-53550549c614/ApproverDetail.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20210212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20210212T022309Z&X-Amz-Expires=86400&X-Amz-Signature=3796e6e677448f2ee4be95018a9a289cde1c0a01f993635db801aaaa5522d05a&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22ApproverDetail.png%22)

`Admin`: If you are an admin, this user will get into **Workflow for Admin App**
You can view all the workflow as well as add or delete different roles in this workspace.
![3df68224.png](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/73dd1b80-6378-41cf-9ee2-004429b13acc/AdminOverview.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20210212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20210212T022322Z&X-Amz-Expires=86400&X-Amz-Signature=e3f434e5d3683f6e0671e419e0d2790f8406270af16af27317f55b08744aaa71&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22AdminOverview.png%22)
![85000656.png](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/02ea8f59-f24a-4a24-bf24-578b523360e0/AddMember.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20210212%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20210212T022335Z&X-Amz-Expires=86400&X-Amz-Signature=1016704079a1f25ab291a6056865828c93667875d1224d3705d54c51d9b835e9&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22AddMember.png%22)




