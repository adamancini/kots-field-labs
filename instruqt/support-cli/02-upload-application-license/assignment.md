---
slug: upload-application-license
id: nvzqmncvbscc
type: challenge
title: Upload application license
teaser: Kotsadm load application licence
notes:
- type: text
  contents: Please wait while kotsadm is deployed..
tabs:
- title: Shell
  type: terminal
  hostname: kubernetes-vm
- title: KotsAdm
  type: website
  url: http://kubernetes-vm.${_SANDBOX_ID}.instruqt.io:8800
  new_window: true
difficulty: basic
timelimit: 1200
---

👋 Load the application license in kotadm UI
============================================

**In this exercise you will:**

 * Login to the kotsadm portal
 * Load the application license download from the vendor portal

***

### 1. Kotsadm UI Login

Launch the kotsadm and authenticate using `PARTICIPANT_ID` value from the Shell tab output as the password.

![supportcli-kotsadm-login1](../assets/supportcli-kotsadm-login.png)


### 2. Upload application license

Once authenticated to kotsadm, you will be prompted to upload a license, select or drag and drop a file and click Upload.

![supportcli-kotsadm-lic-ul1](../assets/supportcli-kotsadm-lic-ul1.png)
![supportcli-kotsadm-lic-ul2](../assets/supportcli-kotsadm-lic-ul2.png)

The application will then fully deploy and you will land on the dashboard and can see the application is not healthy.

![supportcli-kotsadm-dash-broken1](../assets/supportcli-kotsadm-dash-broken1.png)
![supportcli-kotsadm-status-broken](../assets/supportcli-kotsadm-status-broken.png)


***
Progress to the next challenge to investigate further.

Note: the application needs to be deployed before the challenge allows you to progress.

To complete this challenge, press **Check**.

