# gitdemo

https://vscode-auth.github.com/?browser_session_id=b954ef05d1bd88ac80970ab03493699218b24237b9c3ce52c803537a1b98e11d&code=7fb90b0b0e1a06ddfb90&state=ExwUactzv3hTq707JOaxJ4DQ4pg%2FeyJhdXRoU2VydmVyIjoiaHR0cHM6Ly9naXRodWIuY29tIiwiY2FsbGJhY2tVcmkiOiJ2c2NvZGU6Ly92c2NvZGUuZ2l0aHViLWF1dGhlbnRpY2F0aW9uL2RpZC1hdXRoZW50aWNhdGU_d2luZG93aWQ9MSIsInJlc3BvbnNlVHlwZSI6ImNvZGUiLCJzdGF0ZSI6ImRjNTBiNDRkLTRhODktNDljMS05M2ZiLTE2OTY3YmZkM2QwZCIsImlkIjoiOjpmZmZmOjEwLjQ3LjIyMS4yMjcifQ
Authorization was successful. You will be redirected back to Visual Studio Code

Didn't work?
If you aren't redirected, you can add the token manually.

Your authorization token:
vscode://vscode.github-authentication/did-authenticate?windowid=1&code=7fb90b0b0e1a06ddfb90&state=dc50b44d-4a89-49c1-93fb-16967bfd3d0d


1. Copy the token.
2. Switch back to VS code.
3. Click Signing in to github.com... in the status bar.
4. Paste the token and hit enter.

git 在Visual Studio Code运行日志如下： --jiajunhua20210329
Windows PowerShell
版权所有 (C) Microsoft Corporation。保留所有权利。

尝试新的跨平台 PowerShell https://aka.ms/pscore6

PS D:\gitdemo> git init
Initialized empty Git repository in D:/gitdemo/.git/
PS D:\gitdemo> git add 1.txt
PS D:\gitdemo> git add .\1.txt
PS D:\gitdemo> git commit -m ="添加了1.txt"


  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"
Omit --global to set the identity only in this repository.

[master (root-commit) 85e256f] =添加了1.txt                            .(none)')
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 1.txt
PS D:\gitdemo> git remote add origin https://github.com/jiajunhua/gitdemo.git
PS D:\gitdemo> git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/jiajunhua/gitdemo.git'
PS D:\gitdemo> git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/jiajunhua/gitdemo.git'
PS D:\gitdemo> git config --global user.name "jiajunhua"
PS D:\gitdemo> git config --global user.email "939634770@qq.com"
PS D:\gitdemo> git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/jiajunhua/gitdemo.git'
PS D:\gitdemo> git pull --rebase origin master
fatal: unable to access 'https://github.com/jiajunhua/gitdemo.git/': OpenSSL SSL_read: Connection was reset, errno 10054
PS D:\gitdemo> git push -u origin master
Logon failed, use ctrl+c to cancel basic credential prompt.
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 218 bytes | 218.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/jiajunhua/gitdemo.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.
PS D:\gitdemo>



