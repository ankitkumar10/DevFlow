## Entities

- User
- Project
- Comment
- Task
- ProjectMember
- Activity
- Attachment
- Notification

## User

### Description

Represents a person who can access and collaborate within DevFlow.

### Responsibilities

- Create and manage personal account
- Create projects
- Join projects
- Be assigned tasks
- Create and edit tasks (subject to permissions)
- Comment on tasks
- Upload attachments
- Receive notifications
- Update profile information

### Attributes

- id
- name
- email
- password
- avatarUrl
- bio (optional)
- createdAt
- updatedAt

### Relationships

- Belongs to many Projects
- Owns many Projects
- Is assigned many Tasks
- Creates many Comments
- Receives many Notifications
- Uploads many Attachments
