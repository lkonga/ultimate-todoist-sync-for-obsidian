# Ultimate Todoist Sync for Obsidian

It should be the best Obsidian plugin for synchronizing Todoist tasks so far.

## Demonstration

### Demo Usage
![Alt Text](/attachment/demo.gif)

### Settings page
<img src="/attachment/settings.png" width="500">

### Sync Button 
<img src="/attachment/Syncbutton.png" width="500">

## Features 

### Sync from Obsidian to Todoist
| Functionality           | Manual Sync | Auto Sync |
|------------------------|-------------|-----------|
| Add task                |  ✅          | ✅          |
| Modify task content     | ✅           | ✅         |
| Modify task due date    | ✅           | ✅         |
| Modify task labels/tags | ✅           | ✅         |
| Mark task as completed  | ✅           | ✅         |
| Mark task as uncompleted  | ✅           | ✅         |
| Modify project          | 🔜          | 🔜        |

### Sync from Todoist to Obsidian
| Functionality           | Manual Sync | Auto Sync |
|------------------------|-------------|-----------|
| Add task                | 🔜            | 🔜         |
| Modify task content     | ✅           | 🔜         |
| Modify task due date    | ✅           | 🔜          |
| Modify task labels/tags | 🔜          | 🔜        |
| Mark task as completed  | ✅           |          |
| Mark task as uncompleted  | ✅           | 🔜         |
| Modify project          | 🔜          | 🔜        |

> **Some plugins may modify the current view, such as Kanban, which causes the automatic synchronization function to fail. You need to manually click the sync button.**


## Installation

1. Download the latest release of the plugin from the [Releases](https://github.com/username/repo/releases) page.
2. Extract the downloaded zip file and copy the entire folder to your Obsidian plugins directory.
3. Enable the plugin in the Obsidian settings.

## Configuration

1. In the Obsidian settings, click on the "Plugins" tab and then click the gear icon next to the "Ultimeta Todoist Sync for Obsidian" plugin.
2. Enter the Todoist API..

## Usage


New tasks will be added to the default project, and you can change the default project in the settings or use a tag with the same name to specify a particular project. Tasks marked with #todoist will be added to Todoist, while tasks without the **#todoist** tag will not be processed.

| Syntax | Description | Example |
| --- | --- | --- |
|#todoist|Tasks marked with #todoist will be added to Todoist, while tasks without the **#todoist** tag will not be processed.| `- [ ] task #todoist`|
| 🗓️YYYY-MM-DD | The date format is 🗓️YYYY-MM-DD, indicating the due date of a task. | `- [ ] task content 🗓️2025-02-05 #todoist` |
| #projectTag | New tasks will be added to the default project(For example,  inbox .), and you can change the default project in the settings or use a tag with the same name to specify a particular project. | `- [ ]taskA 🗓️2024-02-04  #todoist` will be added to inbox.`- [ ]taskB 🗓️2024-02-04 #tag #testProject #todoist` will be added to testProject.|
| #tag | Note that all tags without a project of the same name are treated as normal tags | `- [ ] task #tagA #tagB #tagC #todoist` |



### Syncing Tasks

 


## Disclaimer

This plugin is for learning purposes only. The author makes no representations or warranties of any kind, express or implied, about the accuracy, completeness, or usefulness of this plugin and shall not be liable for any losses or damages resulting from the use of this plugin.

The author shall not be responsible for any loss or damage, including but not limited to data loss, system crashes, computer damage, or any other form of loss arising from software problems or errors. Users assume all risks and are solely responsible for any consequences resulting from the use of this product.

By using this plugin, you agree to be bound by all the terms of this disclaimer. If you have any questions, please contact the author.

## Contributing

Contributions are welcome! If you'd like to contribute to the plugin, please read our [contributing guidelines](CONTRIBUTING.md) and submit a pull request.

## License

This plugin is released under the [MIT License](LICENSE).

