# NOTES

**File-Copy-Functionality**: It's possible to copy files from the role's file directory to the destination directory specified. The idea is to use this for config files that are not part of the git repository. Obviously they should not be part of this role's git repository either. But we have the options to encrypt these files later!

# TO DO

- Encrypt config files and secrets so that they may be part of the git repository

# LINKS

- https://docs.ansible.com/ansible/latest/collections/ansible/builtin/git_module.html