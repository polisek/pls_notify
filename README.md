# pls_notify - Easy notifications for RedM

Simple notifications for RedM

# Example

Default notification

Client
```
exports["pls_notify"]:Notification({  
        type="success", 
        title="Notification test",
        text="Notification description", 
        timeout=5000,
}) 
```

Server
```
TriggerClientEvent("pn:Notification", src, {  
        type="success", 
        title="Notification test",
        text="Notification description", 
        timeout=5000,
})
```

Custom notification

Client
```
exports["pls_notify"]:CustomNotification({  
        type = "success",
        title="Notification test", 
        text="Notification description",
        timeout=5000,
        class = "earleblack",
        showicon = true,
        stype = 3, 
}) 
```

Server
```
TriggerClientEvent("pn:CustomNotification", src, {  
        type = "success",
        title="Notification test", 
        text="Notification description",
        timeout=5000,
        class = "earleblack",
        showicon = true,
        stype = 3, 
})
```

# Custom classes
add to class = 

cordovan,
earleblack,
champane,
tealblue,
mdgreen,
pink1,


# Screenshot

![image](https://user-images.githubusercontent.com/107623238/188313328-9cc1836d-c92c-4f1e-8023-aa5d033e769c.png)


# Used library

https://github.com/simple-notify/simple-notify



# Support
- discord : https://discord.gg/VvRGG6rPCc
- email : polismanovicp@gmail.com
- support: https://paypal.me/Polisek?country.x=CZ&locale.x=cs_CZ

