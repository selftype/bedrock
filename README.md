# bedrock

A general-purpose extensible semantic notation framework


## Concept

- Each thought is an object.
- Each object has identifier through which other objects can refer to it


## Implementation

- Object representation: file.
- Markup language: Markdown + YAML frontmatter.
- State sync: git?
- Service: programs executed during CI
- Tools: text editor, CLI client


## Applications

- note-taking
- task management
- documentation


## Features

### Object Subscription

Whenever an object is updated or referred in other objects subscribers should receive a notification.  
This feauture is useful for purposes such as task management (e.g. user receives notifiction whenever he/she is mentioned in a task, contextual discussion in tasks).


## Problems

### Ownership

Sometimes common access is undesirable

### Sync

Git seems inappropriate tool for fast data transfer

