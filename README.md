# Deploying-task-sequences


 Follow the steps below to distribute Task Sequences as well as Applications in Microsoft Endpoint Configuration Manager.
  
<b> *NOTE*: Through testing it appears that freshly creating a device collection and distribution group for distributing an application or task sequence prevents error code 0x87D00607(-2016410105) from appearing.</b>

<b> *NOTE*: It may be tedious but I recommend going through the entire process documented for a successful deployment...</b>

- Under Software Library, select the desired task sequence and right-click.
- Select Deploy.
- Select your collection, then click OK.
- Click Next.

<p align="center">
<img src="https://i.imgur.com/BMGtpIy.png" height="80%" width="80%"/>

- Set Purpose to available for deployment to appear in Software Center on devices.
- If you set it to required you will have to specify a time for the deployment to download to the device. Then you need to select a time for the deployment to begin installation on the device.
- Select Make available to Configuration Manager Clients, media, and PXE to cover all bases.
- Click Next.

<p align="center">
<img src="https://i.imgur.com/OE6hrGK.png" height="80%" width="80%"/>

- Click Next.

<p align="center">
<img src="https://i.imgur.com/OpPnfYs.png" height="80%" width="80%"/>

- Check off Software Installation, System restart, and Allow task sequence to run for client on the internet.
- Click Next.

<p align="center">
<img src="https://i.imgur.com/JINN995.png" height="80%" width="80%"/>

- Click Next.

<p align="center">
<img src="https://i.imgur.com/Ed8cQiC.png" height="80%" width="80%"/>

- Lastly, click next to finalize Deployment.

<p align="center">
<img src="https://i.imgur.com/s7vhLQm.png" height="80%" width="80%"/>

Congratulations!👍 You successfully Deployed content!

