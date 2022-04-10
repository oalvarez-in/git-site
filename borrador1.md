Universal Git Authentication
“Authentication is hard. Hard to debug, hard to test, hard to get right.” – Me

These words were true when I wrote them back in July 2020, and they’re still true today. The goal of Git Credential Manager (GCM) is to make the task of authenticating to your remote Git repositories easy and secure, no matter where your code is stored or how you choose to work. In short, GCM wants to be Git’s universal authentication experience.

In my last blog post, I talked about the risk of proliferating “universal standards” and how introducing Git Credential Manager Core (GCM Core) would mean yet another credential helper in the wild. I’m therefore pleased to say that we’ve managed to successfully replace both GCM for Windows and GCM for Mac and Linux with the new GCM! The source code of the older projects has been archived, and they are no longer shipped with distributions like Git for Windows!

In order to celebrate and reflect this successful unification, we decided to drop the “Core” moniker from the project’s name to become simply Git Credential Manager or GCM for short.

Date: April 10
Ref:https://github.blog/2022-04-07-git-credential-manager-authentication-for-everyone/
