Project in progress...

# Description

Base code of Croogo engine: [tree][1]

# Install 

In the admin panel: Menu-> Extensions-> Locales, 
link Upload, download [rus.zip][2] and activate the language.

Need to take into account the permission to the directory **locale**.

# Install - manual

Put **rus** folder in **locale** folder. 

Reactivate the language in the admin panel: Menu-> Extensions-> Locales.

# Note

Also, in order to avoid has expanding the admin menu , you need to make changes to the file **webroot/css/admin.css** line 126:

    #nav ul li a { margin-right: 20px; }

change the **20px** on **2px**.


  [1]: http://github.com/croogo/croogo/tree/8b0ab6bc5cc842940ab0a202cce81e47ecf875ba
  [2]: http://github.com/downloads/vksee/croogo-russian-translation/rus.zip