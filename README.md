[![Carthage compatible](https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat)](https://github.com/Carthage/Carthage)

### JSQMessagesViewController ###
[Carthage](https://github.com/Carthage/Carthage) support for https://github.com/jessesquires/JSQMessagesViewController.

The dependencies [JSQMessagesViewController](https://github.com/jessesquires/JSQMessagesViewController) and [JSQSystemSoundPlayer](https://github.com/jessesquires/JSQSystemSoundPlayer) are added as git subtree modules. This allows us to easily pull in newer changes to JSQMessagesViewController.

### Usage ###
Add ```github "hemantasapkota/JSQMessagesViewController"``` to your ```cart``` file.
Execute ```carthage update```

### Update Dependencies ###

You might want to update the dependencies to pull in newer changes. To do so:

```
git subtree pull --prefix JSQMessagesViewController https://github.com/jessesquires/JSQMessagesViewController master --squash

git subtree pull --prefix JSQSystemSoundPlayer https://github.com/jessesquires/JSQSystemSoundPlayer master --squash
```
