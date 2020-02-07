# ReclaimPro

[![N|Solid](<https://img.icons8.com/ios/50/000000/ios-photos--v2.png>)](https://discord.gg/CGB2pmD)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

In this information page you will see

  - How tu use the plugin
  - Important things to keep in mind
  - Examples

#### Adding a custom reclaim
To add a custom reclaim there's need to be some steps that have to be followed
1. In your '***Configuration.yml***', under '***Claims***' create your own section with a name of your interest.
2. Under that section you just created you will need to create more sections to define that certain reclaim.Under your custom Reclaim, create a section named '***Permission***'.
3. On '***Permission:***' choose a custom permission you want a certain user to have to be able to use that reclaim.
4. Above '***Permission:***' create a section named '***Delay:***'. Set the value of '***Delay:***' to a number of your choice. This number will define how long a user has to wait (in minutes) before they can reclaim that certain claim you created.
5. On the line under '***Delay:***', create a section named '***Commands:***' This section should contain a list of lines of commands that will be executed once the player reclaims this claim you created.
6. After this line, you will create another section named '***Items:***'. This will be another list that you will require two parameters for this to work. The first parameter will be the Item name, you can find all the items here: **https://github.com/proxytimeout/PlayerRespect/blob/master/Items**. After you have choosen an item, you will need to set a value to it. To set a value you will just have to type the item name and add a space which will define that the next number will be the amount of that item that should be given to the command sender.
7. On the line following this one, you will have to include another list which will be named '***Broadcast:***'. This section will contain a list with all the messages that will be sent to every player once a user uses this reclaim.

8. At the end, you should have something that looks like this:
*NewExample:
    Permission: Reclaim.use.example
    Delay: 10
    Commands:
    - -say it works!
    - -say this is cool!
    - -tell proxyGaming17 Hi dude!
    Items:
    - -DIAMOND 1
    - -APPLE 1
    Messages:
    - --x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x
    - -''
    - -'%prefix% You have received A Diamond, Enjoy %player%.'
    - -''
    - --x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x
    Broadcast:
    - -'%player% received A Diamond.'*
9. After this, you're almost done. Now you just need to realod the plugin and your new reclaim will be ready to use. To do this, use the command ***/ReclaimAdmin reload***
    
    
