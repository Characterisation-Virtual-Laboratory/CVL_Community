---
layout: post
title:  "CVL on Wiener"
author: Paula
categories: [ champions, tutorial]
tags: [ wiener ]
image: assets/images/wiener/wiener_SelectWiener.png
featured: false
toc: true
---

How to login and use CVL on Wiener tutorial.

Last updated 12 November 2020

Please note that desktops on Wiener are in *Beta mode* and we appreciate your feedback to improve the system. For any enquiries or to report issues please send an email to QRISCloud helpdesk [support *at*  qriscloud.org.au](mailto:support@qriscloud.org.au).

## Get an account on Wiener
If you have University of Queensland credentials and have the need to use infrastructure resources such as HPC and GPUs you can request an account on Wiener.

1. Get a Wiener account by sending an email to [helpdesk QBI IT](mailto:helpdesk@qbi.uq.edu.au). The email should outline a short description, including your need to access CVL on Wiener, and request to be added to the **wiener-cvl** group.
    If you want to read more about Wiener read The University of Queensland Research Computing Centre (UQ RCC) [Wiener guide](https://rcc.uq.edu.au/wiener){:target="_blank"}.
2. If you have projects on UQRDM, you can also request to access your **'Q'** collections via Wiener, by sending your username and collections' ids. Note, only connections that are marked as HPC usage in your application can be accessible, those will start with a QXXXX.

## Access CVL @ wiener

Once your account and permissions are ready, you can log in to Wiener.

1. We recommend using Chrome, and navigate to [https://desktop.cvl.org.au](https://desktop.cvl.org.au){:target="_blank"}. From the drowpdown "Select remote system", select *CVL@Wiener (BETA)*.
   <details>
      <summary>Click to see the screenshot</summary>
      <img src="../assets/images/wiener/wiener_SelectWiener.png" alt="Select Wiener">
   </details><br>
1. Click the blue button "LOGIN".<br><br>
1. Authorisation is required for this step. When asked, please login with your institutional credentials through AAF. You can check the box to remember your details, or it will ask you every time you login.<br><br>
1. Click the blue button "I AGREE" to share your email to the system.<br><br>
1. Once you see a new window called "Strudel Web", click on **WIENER**
    <details>
       <summary>Click to see the screenshot</summary>
       <img src="../assets/images/wiener/wiener_ClickWieneronStrudel.png" alt="Click Wiener on Strudel">
    </details><br>
1. Then, to launch a new desktop, you can use the defaults options. Click on *Launch* and wait. You should see a message at the bottom right "Desktop #XXX Launched Successfully".
    <details>
      <summary>Click to see the screenshot</summary>
      <img src="../assets/images/wiener/wiener_LaunchDesktop.png" alt="Launch Desktop">
    </details><br>
    Note: you can modify the parameters. You can request at most 16 cores and 8G of memory (because the memory request is per core, for a total of 128G). The maximum hours you can request is 24 hours, your desktop will close after the time has reach its limit. You can only run one desktop at the time.<br>
1. A desktop will start when state is checked, and the **Show Desktop** is available
   <details>
     <summary>Click to see the screenshot</summary>
     <img src="../assets/images/wiener/wiener_ShowDesktop.png" alt="Show Desktop">
   </details><br>
1. A new tab will open and you **might** see shortly a message that says "Connecting to guacamole".<br><br>
    **There are known connection issues with this step and the team is working to fix this.**  
    **You may need to hit the *LOGOUT* button to *start* the desktop launch.**<br>
    <br>
      - If you see a blank screen with ‘No recent connections’, please click the top right dropdown menu and select ‘log-out’. This will take you to the desktop.
        <details>
        <summary>Click to see the screenshot</summary>
        <img src="../assets/images/wiener/wiener_norecentconnections.png" alt="ConnectionError">
           </details>
      - If this pop-up shows:
        <details>
        <summary>Click to see the screenshot</summary>
        <img src="../assets/images/wiener/wiener_ConnectionError.png" alt="ConnectionError">
        </details>
        try clicking on the logout button, sometimes the cache needs to be cleared, it will not kill your desktop session, just reset the browser cache. If you see this multiple times in one session please send an email to helpdesk.<br><br>       
1. Once you see the "CVL on Wiener" logo you are ready to use the tools.<br><br>
1. When you finish using the tools you need, you can shut down the desktop by closing the desktop tab and then, click "Stop desktop" from the launch tab.
    <details>
      <summary>Click to see the screenshot</summary>
      <img src="../assets/images/wiener/wiener_StopDesktop.png" alt="Stop Desktop">
    </details>

## Full List of applications available
For a full list of Software Tools available on the CVL@Wiener please look at [CVLWienerSoftware](../CVLWienerSoftware).

### Open Software Applications on the CVL@wiener

- **To access data collections** via Wiener go to File System and then click on afm01 and then look for your QXXX (look for the number of your project).
  <details>
    <summary>Click to see the screenshot</summary>
    <img src="../assets/images/wiener/wiener_FileSystem.png" alt="File System">
  </details>
  IF you can not access your collection, you need to send a request to [helpdesk QBI IT](mailto:helpdesk@qbi.uq.edu.au) stating your need to access UQRDM collections via the CVL@Wiener, your user name and collection's ID.
- **To open FIJI**, go to top menu Applications> CVL Neuroimaging, CVL Fiji
    <details>
      <summary>Click to see the screenshot</summary>
      <img src="../assets/images/wiener/wiener_FIJI-menu.png" alt="FIJI-menu">
      <br/>
      <img src="../assets/images/wiener/wiener_FIJI-Open.png" alt="FIJI-Open">
    </details>
- **To open the Terminal**, go to top menu click on the black box
    <details>
      <summary>Click to see the screenshot</summary>
      <img src="../assets/images/wiener/wiener_openterminal.png" alt="open terminal">
    </details>


## Contact details
For any inquires, feedback, software requests and to report user experience issues about the CVL@Wiener, please send an email to [QRISCloud helpdesk](mailto:support@qriscloud.org.au).



Last updated 12 November 2020
