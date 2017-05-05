# nagiosplugins
This repository has the customized nagios plugins in it. For now, I wrote a plugin based on our project requirement
Our Requirement for now is to create a plugin, that creates a file, opens the file, writes to it and then deletes it. This checks the health of the file system. This script uses "mktemp" and and "timeout" options not to get into deadlock scenario when the filesystem is in trouble and alerts the users appropriately.
