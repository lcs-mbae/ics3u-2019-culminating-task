# ICS3U 2019 Culminating Task

Use this repository to complete your culminating task.

Be sure to **fork** this repository before cloning.

Be sure to commit your work frequently; as discussed in class, this is a major part of the expectations for the culminating task.

## Install the shortcut

To use the `./acp` shortcut, copy and paste these commands into your Terminal window after cloning:

```
cd ics3u-2019-culminating-task
rm -rf acp
echo -e 'acp' >> .gitignore
echo -e '#!/bin/bash' >> acp
echo -e 'git add *' >> acp
echo -e 'git commit -m "$1"' >> acp
echo -e 'git push -u origin master' >> acp
chmod +x acp
```
