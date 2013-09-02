# Complete Digital Signage System optimized for Raspberry Pi

The visio of this project is to offer a complete digital signage solution for “everybody” needs.

## Modules

### Display Screen

The most viewed module is a display screen. It is a single page application running under a web browser like Firefox. This module is optimized for Raspberry Pi because of its low cost and space.

To have one display screen more you need a TV or a display you want and a Raspberry Pi with an Internet connection through a built-in Ethernet port or a separately sold USB adapter. You can have as many display screens you need and where you need.

### Content Editor

With a content editor you can edit all the content shown in each display screens. You can edit both the changing content and static layout. The system is content oriented. This is you firstly create a content and then schedule it to shown in some screens in an appropriate time.

### Admin Tool

With an admin tool you can configure/manage both your server and screens. The potential use cases for the admin tool are setting up a new screen, configuring existing screens and setting up a watch dog to listen faults on screens! With the admin tool you can configure content editor settings such as user interface language. You can also update the software on the fly and force updates to display screens remotely.

### Server

The hearth of the system is a server. It handles all requests from screens and editors as the content storage. All the data is backed in a database, of course.

It is recommended to run the server on a real server. But if you need only one screen with an almost static content you may think to have the server alongside the screen in a one Pi. There is no technical restrictions for the server hardware. So if your server can run in a small shared device without notable issues, why not to do so?
