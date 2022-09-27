---
slug: wordpress-install
id: k4hqsy7tfaft
type: challenge
title: wordpress-install
teaser: A short description of the challenge.
notes:
- type: text
  contents: Replace this text with your own text
tabs:
- title: Application Installer
  type: website
  url: http://kubernetes-vm.${_SANDBOX_ID}.instruqt.io:8800
  new_window: true
- title: Shell
  type: terminal
  hostname: kubernetes-vm
difficulty: basic
timelimit: 600
---
## Step 01

Go to the Application Installer tab, and login using the password you used in the previous step.

<p align="center"><img src="../assets/helm-login.png" width=600></img></p>

## Step 02

Upload the license for the `Helm Customer` you downloaded in Challenge #2

<p align="center"><img src="../assets/helm-license.png" width=600></img></p>

## Step 03

Set the initial blog name in Wordpress

<p align="center"><img src="../assets/helm-config.png" width=600></img></p>

## Step 04

Click `Continue` and watch the Preflights run. These preflights will validate the application environment.


Once the preflights are finished, you can check the results which will look like below


For now we will ignore the warnings and click `Continue`.

## Step 05

Once you clicked on `Continue`, the Application Installer will deploy the Wordpress Application.



If you want to check the Wordpress App, you can do so by clicking on `Open Wordpress`


It will open a new tab and you should see something similar like the screenshot below:


🏁 Finish
=========

If you've viewed the initial blog in Wordpress, congratulations! You've deployed your first application using the Replicated Application Installer. You can click **Check** to finish this track.
