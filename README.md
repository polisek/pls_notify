# pls_notify

Simple notifications for RedM

# Example

Default notification

Client
exports["pls_notify"]:Notification({  
        type="success", 
        title="Notification test",
        text="Notification description", 
        timeout=5000,
}) 

Server
TriggerClientEvent("pn:Notification", src, {options})


Custom notification



# Screenshot

![image](https://user-images.githubusercontent.com/107623238/188313328-9cc1836d-c92c-4f1e-8023-aa5d033e769c.png)
