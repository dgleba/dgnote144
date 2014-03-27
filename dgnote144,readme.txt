
2014-03-24_Mon_13.04-PM

Question:

Attached is an example of multiple autocomplete module that is written  for one specific lookup table and field.

It works, but the code is written such that is doesn't use xataface methods in the action_mac.php that is called by the macjs.js.

Can someone help me with ideas of how it can be written to use xataface methods? I want to use xataface functions, tools and resources in the action_mac.php 

Maybe I could re-write the action_mac.php to be a xataface action that is called through the index.php? If that can be done, I don't know how to get started.

Can someone help?

Screen shots are attached.

--

Info:

There is a sql file that can be used to create the mysql database for the example.

The attached example is a complete xataface application that uses the included module.

The xataface files are to be supplied by yourself and should be located in a folder beside the application folder.

eg:
C:\p2\xampp\htdocs\dgnote144
C:\p2\xampp\htdocs\xataface

You can always edit the index.php to suit the location where you keep your copy of the xataface files.

Put your database credentials in config.dbc and configphp.dbc. There examples of these files in the app files attached.

--