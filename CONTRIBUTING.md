Contributing to Software AG Open Source Project
We do not want to bother you with too much legalese, but there are two pages you have to read carefully, this page and the CONTRIBUTOR LICENSE AGREEMENT.

Signing the CONTRIBUTOR LICENSE AGREEMENT
Each Contribution to Software AG's Open Source Projects must be accompanied by a sign-off indicating acceptance of current version of the CONTRIBUTOR LICENSE AGREEMENT, which is derived from the Apache Foundation's Individual Contributor License Agreement, sign-off time stamp relates to corresponding version of the CONTRIBUTOR LICENSE AGREEMENT maintained here on GitHub as well. Sign-Off and acceptance of the CONTRIBUTOR LICENSE AGREEMENT is declared by using  the option "-s" in

git commit -s

which will automatically generate a sign-off statement in the form: 

Signed-off-by: Max Mustermann <MaxM@developer.lieschen-mueller.org>

By adding this sign-off statement, you are certifying:

By signing-off on this Submission, I agree to be bound by the terms of the then current CONTRIBUTOR LICENSE AGREEMENT located at https://github.com/SoftwareAG/contributing, which I have read and understood and I agree that this Submission constitutes a "Contribution" under this Agreement.

Note on Privacy
Please note that this project and any contributions to it are public and that a record of all contributions (including any personal information submitted with it, including a sign-off) is maintained indefinitely and may be redistributed consistent with this project or the open source license(s) involved.

In addition to GitHub's privacy statement extracting personal data from these projects for any other use than maintaining the projects and communication related to it is prohibited, explicitly prohibited is extracting email addresses for unsolicited bulk mails.

If you'd like to keep your personal email address private, you can use a GitHub-provided no-reply email address as your commit email address. You can choose which verified email address to author changes with when you edit, delete, or create files or merge a pull request on GitHub. If you enabled email address privacy, then the commit author email address cannot be changed and is <username>@users.noreply.github.com by default. 

See setting your commit email address on GitHub.

In the upper-right corner of any page, click your profile photo, then click Settings.

In the left sidebar, click Emails.
In "Add email address", type your email address and click Add.
Verify your email address.
In the "Primary email address" list, select the email address you'd like to associate with your web-based Git operations.
To keep your email address private when performing web-based Git operations, click Keep my email address private.
You can use the git config command to change the email address you associate with your Git commits.

See setting your commit email address in Git.



Open Git Bash.
Set an email address in Git. You can use your GitHub-provided no-reply email addressor any email address.

$ git config --global user.email "email@example.com"

Confirm that you have set the email address correctly in Git:

$ git config --global user.email
email@example.com

Add the email address to your account on GitHub, so that your commits are attributed to you and appear in your contributions graph.


Release date: 2021-03-29
