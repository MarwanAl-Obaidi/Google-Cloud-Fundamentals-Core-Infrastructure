# Resources and Access in Google Cloud

### Select the option that displays IAM roles from general to specific.

- [ ] Predefined roles, custom roles, basic roles
- [ ] Custom roles, predefined roles, basic roles
- [X] Basic roles, predefined roles, custom roles

### Which statement best describes how Google Cloud resources are associated within the resource hierarchy?

- [ ] All Google Cloud resources are associated with an organization.
- [ ] All Google Cloud resources are associated with a folder.
- [ ] Google Cloud resources are not associated with the resource hierarchy.
- [X] All Google Cloud resources are associated with a project.

### Which way of accessing Google Cloud lets you control services through the code you write?

- [X] APIs
- [ ] The Cloud SDK and Cloud Shell
- [ ] The Cloud Console mobile app
- [ ] The Cloud Console

### How does the resource hierarchy control how IAM policies are inherited?

- [ ] IAM policies are only implemented at the project level; they cannot be amended by lower levels of the resource hierarchy.
- [X] IAM policies that are implemented by lower-level policies can override the policies defined at a higher level.
- [ ] IAM policies that are implemented higher in the resource hierarchy deny access that is granted by lower-level policies.

### What is the difference between Identity and Access Management (IAM) basic roles and IAM predefined roles?

- [ ] Basic roles only apply to the owner of the Google Cloud project. Predefined roles can be associated with any user.
- [ ] Basic roles only allow viewing, creating, and deleting resources. Predefined roles allow any modification.
- [ ] Basic roles can only be granted to single users. Predefined roles can be associated with a group.
- [X] Basic roles affect all resources in a Google Cloud project. Predefined roles apply to a specific service in a project.

### Consider a single hierarchy of Google Cloud resources. Which of these situations is possible? (Choose 3 responses.)

- [ ] There are two or more organization nodes.
- [X] There is an organization node, and there are no folders.
- [ ] There is no organization node, but there is at least one folder.
- [X] There is an organization node, and there is at least one folder.
- [X] There is no organization node, and there are no folders.

### Your company has two Google Cloud projects and you want them to share policies. What is the least error-prone way to set this up?

- [ ] Create shared resource policies on the common resources that are used in both projects.
- [X] Place both projects into a folder, and define the policies on that folder.
- [ ] Define the new shared policy in the organization node.
- [ ] Duplicate all the policies from one project onto the other.

### When would you choose to have an organization node? (Select two)

- [X] When you want to centrally apply organization-wide policies
- [ ] When you want to organize resources into projects
- [ ] There’s no choice; organization nodes are mandatory.
- [X] When you want to create folders