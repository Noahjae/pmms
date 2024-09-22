This resource allows you to host your own version of the pmms-dui server which is required for pmms, this script allows you to automatically update the pmms config with the correct URL or do it yourself. Simply drop the pmms-dui folder into your resources and add `start pmms-dui` !!BELOW!! wherever you have `start pmms` to your server.cfg. 

You can also start this resource while your server is running, once you put the resource into your files, go to the live console page in txAdmin and run the commands: `refresh`, `start pmms-dui` and it should prompt you to type `updateconfig` to automatically update the pmms config file and then restart the pmms resource.

The name of the resource MUST BE `pmms-dui` and your pmms resource must be running when you start this. So make sure to add `start pmms-dui` UNDERNEATH where you `start pmms`
