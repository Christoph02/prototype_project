# prototype_project
public prototype project

Problem: Block command line pushes that expose my email

[Solution]: (https://stackoverflow.com/questions/43378060/meaning-of-the-github-message-push-declined-due-to-email-privacy-restrictions#44099011)  

Change the global user e-mail address setting to be your GitHub noreply address:
git config --global user.email {ID}+{username}@users.noreply.github.com
