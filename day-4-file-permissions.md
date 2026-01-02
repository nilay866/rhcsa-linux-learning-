# Day 4 – File Permissions Commands
# Today I practiced Linux file permission related commands.

# List files with permissions and details
ls -l

# Example permission output:
# -rw-r--r-- 1 user user 0 file.txt

# Change file permissions using numbers
chmod 755 file.txt
chmod 644 file.txt

# Change file permissions using symbols
chmod u+x file.txt      # add execute permission to owner
chmod g-w file.txt      # remove write permission from group

# Change file owner
chown user file.txt

# Change file group
chgrp group file.txt

# View detailed file information
stat file.txt

# Practice summary:
# 1 Checked permissions using ls -l
# 2 Changed permissions using chmod
# 3 Used symbolic permissions
# 4 Changed owner using chown
# 5 Changed group using chgrp
# 6 Viewed details using stat