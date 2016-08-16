# ESBPII-VMware-ESXi

VMware ESXi

VMware ESXi is an enterprise-class, bare-metal hypervisor developed by VMware for deploying and serving virtual computers. As a bare-metal hypervisor, ESXi is not a software application that installs in an operating system.

<img width="393" alt="screenshot 2015-01-14 15 04 58" src="https://cloud.githubusercontent.com/assets/17094710/17689938/d1519cba-63a8-11e6-8c27-5aa8435b6767.png">

Install VMware ESXi Server

Pre-requirements
        * VMware ESXi DVD iso image
        * VMware workstation
        * Good Internet connection
        * Kali Linux iso image

01. Create virtual machine for install VMware ESXi server in VMware workstation according to the requirements.

![1](https://cloud.githubusercontent.com/assets/17094710/17689542/30bd6c7c-63a6-11e6-9ee6-74877a38b267.png)

![2](https://cloud.githubusercontent.com/assets/17094710/17689545/310467ee-63a6-11e6-97f8-872edd07a749.png)

![3](https://cloud.githubusercontent.com/assets/17094710/17689544/3103f8fe-63a6-11e6-937c-7b18ed754a95.png)

![4](https://cloud.githubusercontent.com/assets/17094710/17689546/310ad2dc-63a6-11e6-9b56-f90d23d99eff.png)

![5](https://cloud.githubusercontent.com/assets/17094710/17689547/310e8634-63a6-11e6-8180-8f27a08244c7.png)

![6](https://cloud.githubusercontent.com/assets/17094710/17689548/31117e16-63a6-11e6-82f8-fe1d406ac57b.png)

![7](https://cloud.githubusercontent.com/assets/17094710/17689543/30e4d7da-63a6-11e6-8757-e3be70b9cc54.png)

![8](https://cloud.githubusercontent.com/assets/17094710/17689549/3114963c-63a6-11e6-867e-7ff4dc62cb73.png)

02. Insert the VMware ESXi DVD image to the server and Boot from it. Then ESXi installer will load the necessary files for installation.

![9](https://cloud.githubusercontent.com/assets/17094710/17689550/312b050c-63a6-11e6-8363-1775cd8dc257.png)

![10](https://cloud.githubusercontent.com/assets/17094710/17689551/312e1486-63a6-11e6-9b91-0642bda90b01.png)

03. Once all the modules are loaded successfully, Installation will prompt below screen with server configuration.

![11](https://cloud.githubusercontent.com/assets/17094710/17689553/31381f30-63a6-11e6-9401-2833de50c6e0.png)

04. Continue the installation by just pressing enter key.

![12](https://cloud.githubusercontent.com/assets/17094710/17689552/3136cf18-63a6-11e6-8b15-dcbb47d87b91.png)

05. Accept the license to continue the installation by pressing F11.

![13](https://cloud.githubusercontent.com/assets/17094710/17689554/314ffccc-63a6-11e6-8b7d-5c5f430feab5.png)

06. Select the disk in which would like to install VMware ESXi. Enter to continue.

![14](https://cloud.githubusercontent.com/assets/17094710/17689555/31530570-63a6-11e6-930b-b155546a727a.png)

07. Select preferred keyboard layout.

![15](https://cloud.githubusercontent.com/assets/17094710/17689556/3156784a-63a6-11e6-9f40-4d8c77956e42.png)

08. Enter strong root password for the VMware ESXi server and Press Enter to continue.

![16](https://cloud.githubusercontent.com/assets/17094710/17689557/31584cb0-63a6-11e6-903e-09b0a4e69d4e.png)

09. The Installer gathers the system information before start copying the files to the disk.

![17](https://cloud.githubusercontent.com/assets/17094710/17689558/315ea470-63a6-11e6-8187-c5936a0632ea.png)

10. Installer will prompt final confirmation. Press F11 to continue the installation.

![18](https://cloud.githubusercontent.com/assets/17094710/17689559/3165dc54-63a6-11e6-8194-22ec2ff5d259.png)

11. Installation begins.

![19](https://cloud.githubusercontent.com/assets/17094710/17689560/317d073a-63a6-11e6-87a8-d25eb18e4cce.png)

12. Reboot the system to complete the installation.

![20](https://cloud.githubusercontent.com/assets/17094710/17689561/31804bd4-63a6-11e6-952b-96387c4f618f.png)

![21](https://cloud.githubusercontent.com/assets/17094710/17689563/31866974-63a6-11e6-9515-0e5ccf500553.png)

13. Now VMware ESXi server will boot from hard disk.

![22](https://cloud.githubusercontent.com/assets/17094710/17689562/3185d342-63a6-11e6-9cf8-44503db1805f.PNG)

14. Press F2 to login to the system. Then system will prompt Authentication window to enter username and the password.

![23](https://cloud.githubusercontent.com/assets/17094710/17689564/3188798a-63a6-11e6-9ec8-8474fb841cfe.PNG)

15. After login to the system, user can view the system configurations and logs. Also it provide troubleshooting options.

![24](https://cloud.githubusercontent.com/assets/17094710/17689565/3191c922-63a6-11e6-8c87-f2732ab64b70.PNG)

![25](https://cloud.githubusercontent.com/assets/17094710/17689566/31b6dd70-63a6-11e6-9202-6333df332d49.PNG)

16. After installing VMware ESXi server successfully, User has to connect to the ESXi server via vSphere client to manage. For that user should install vSphere client software. By browsing IP address of the ESXi server, Users can download vSphere client software.

![26](https://cloud.githubusercontent.com/assets/17094710/17689567/31ba3c7c-63a6-11e6-8ff6-e96562ee69a4.png)

![27](https://cloud.githubusercontent.com/assets/17094710/17689568/31bcf53e-63a6-11e6-8f47-368e620f80c7.png)

17. Users can access the ESXi server via vSphere client by using their credentials.

![28](https://cloud.githubusercontent.com/assets/17094710/17689570/31c3e86c-63a6-11e6-9df6-9e58f0a2b449.PNG)

![29](https://cloud.githubusercontent.com/assets/17094710/17689569/31c2ce50-63a6-11e6-9149-32a1fb91db94.PNG)

Creating Kali Linux virtual machine.

![30](https://cloud.githubusercontent.com/assets/17094710/17689571/31d128f6-63a6-11e6-9a60-a861dfa45e4b.PNG)

![31](https://cloud.githubusercontent.com/assets/17094710/17689573/3219e3e8-63a6-11e6-9efc-c9f8ffc49dc9.png)

![32](https://cloud.githubusercontent.com/assets/17094710/17689572/32171f0a-63a6-11e6-8db0-b62ed87361b9.png)

![33](https://cloud.githubusercontent.com/assets/17094710/17689574/321c90ca-63a6-11e6-8628-00762b163f86.png)

![34](https://cloud.githubusercontent.com/assets/17094710/17689575/321dfa1e-63a6-11e6-969d-1770183a71f7.png)

![35](https://cloud.githubusercontent.com/assets/17094710/17689576/32297e5c-63a6-11e6-9861-6ca03171626d.png)

![36](https://cloud.githubusercontent.com/assets/17094710/17689577/322e67dc-63a6-11e6-8ce6-d2df2520f804.png)

![37](https://cloud.githubusercontent.com/assets/17094710/17689578/326d9196-63a6-11e6-83cc-5fadb093e1b5.png)

![38](https://cloud.githubusercontent.com/assets/17094710/17689580/3274cf92-63a6-11e6-9ab3-b878f7c1c421.png)

![39](https://cloud.githubusercontent.com/assets/17094710/17689579/32745dfa-63a6-11e6-9375-113a363807c8.png)

![40](https://cloud.githubusercontent.com/assets/17094710/17689581/3276f920-63a6-11e6-8891-52f1915cee33.png)

![41](https://cloud.githubusercontent.com/assets/17094710/17689582/327eff44-63a6-11e6-8bc9-93be2e42dfee.png)


