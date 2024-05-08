loadstring(game:HttpGet("https://raw.githubusercontent.com/elproplayer9341341/NotificationLibrary/main/CreateLib"))()

local NotificationText = "hi" -- Notification Title
local NotificationDescription = "Hi Exmaple_!" -- Notification Description
local ActionText = "Ok :3" -- Notification Close Button Text

NewNotification(NotificationText, NotificationDescription, ActionText, function() -- Create a New Notification
    warn("New Notification!!") -- function to make after of player clicked Close Button
end)  
