# java-docs


Remove your SSH keys from ~/.ssh (or where you stored them).

Remove your user settings:
git config --global --unset user.name
git config --global --unset user.email
git config --global --unset credential.helper

git init
git config user.name ""
git config user.email ""

