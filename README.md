# Projects
## Active Directory Lab
- Installed VMware software. Installed Windows Server 2019 iso file. Installed Windows 10 iso file.
  - Went to Microsoft and VMware websites to download and install all software required for this lab. Setup iso files in VMware workstations to use for this lab.
![Installing Software 1](https://user-images.githubusercontent.com/78772836/222373149-84f4e00f-3b31-450e-bcfe-c0125149cf83.png)

- Renamed computers and assigned static IP addresses.
  - I renamed the computer by going to system in control panel. Pressing change settings and changed information on computer name/domain change tab.
  - To set the static IP address I first went to network and sharing center in control panel. I then pressed change adapter settings and right clicked Ethernet0 for properties. I seen IPv4 and clicked properties to set the static IP address manually.
  ![Computer name and static ip](https://user-images.githubusercontent.com/78772836/222377325-c6051fb0-a66c-4cf6-8777-2a7a36e6c9d7.png)

- Installed Active Directory and created users, groups and organizational units. 
  - I installed AD users and computers from opening server manager and clicking add roles and features. I selected the server roles needed for this lab.
  - To create users/groups and organizational units in AD I first opened AD users and computers. I then created the IT organizational unit by right clicking the domain name and adding new organizational unit. I created the user Chris by right clicking and adding new user filling out the info i needed to. I created a security group named HR by right clicking users and adding security group. I then added Chris to HR group.
![AD users groups](https://user-images.githubusercontent.com/78772836/222380565-f7f5e609-c8b8-4a7c-834b-7aa5fdfc3655.png)

- Updated default domain password policy in group policy and created share folders. 
  - I went to group policy management and opened settings on the default domain policy. From there I could see the account policies set. To change policies I right clicked default domain policy and pressed edit. Under security settings and account policies I was able to edit password length/age/history and update as needed.
  - Created a share folder by going to server manager storage tab. Then clicking shares and opening TASKS dragdown I could add a new share folder. I set a custom location, name and permissions.
![share folders and group policy](https://user-images.githubusercontent.com/78772836/222386146-014777b8-6bb8-4233-bf81-38a5c6f510a4.png)

- Mapped personal and network drives. Remotely connected second virtual machine.
  - To map drives I right clicked on this PC and selected map network drive. Selected the drive letter and paste the destination I want to map.
  - I remotely connected to desktop1 by opening remote desktop connection. I typed in the name of the computer I want to connect to and press connect.
![rdp map drives](https://user-images.githubusercontent.com/78772836/222390597-3ad556fd-9c3c-440c-b438-f46a2711dd94.png)

- Installed RSAT tools for user. 
  - To install RSAT tools I opened apps and features in settings from the start menu. Clicked optional features and check the box for the files I would install for the user.
![APPS and RSAT tools](https://user-images.githubusercontent.com/78772836/222392174-d495f9e2-6fc6-42ae-a931-79738086fee7.png)

### From this lab I accomplished setting up Active Directory for my server and computer connected. I was able to create multiple users, groups, organizational units and edit the group policy. I mapped drives for users. I was able to remotely connect to a desktop and install RSAT tools in optional features.

