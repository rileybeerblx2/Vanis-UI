# Vanis UI
This documentation is for Vanis UI Credit To The Owner

## Booting the Vanis UI Library
```lua
local library = loadstring(game:HttpGet('https://raw.githubusercontent.com/cypherdh/VanisUILIB/main/.gitignore'))()
```




## Creating a Vanis UI Window
```lua
local Window = library:CreateWindow("Name", "Version", 10044538000)
```

## Creating a Tab
```lua
local Tab = Window:CreateTab("Scripts")
```

## Creating a Page / Section
```lua
local Page = Tab:CreateFrame("Page 1")
```

## Creating a Button
```lua
Button = Page:CreateButton("Button", "Description", function()
CreateNotification("Title", "Description", function(value)
if value == true then
print(true)
else
print(false)
end
end)
end)
```

## Creating a Toggle
```lua
Toggle = Page:CreateToggle("Toggle", "Description", function(arg)
Toggle:UpdateToggle("New Title", "New Description")
print(arg)
end)
```

## Creating a Bind
```lua
Bind = Page:CreateBind("KeyBind", "F", function(arg)
Bind:UpdateBind("New Title")
print(arg)
end)
```

## Creating a Textbox
```lua
TextBox = Page:CreateBox("TextBox", 10044538000, function(arg)
TextBox:UpdateBox("New Title")
print(arg)
end)
```

## Creating a Slider
```lua
Page:CreateSlider("Slider", 16, 500,function(arg)
   print(arg)
end)
```

## Creating a Label
```lua
Label = Page:CreateLabel("Label")
```

## Creating a Update Label
```lua
Label:UpdateLabel("New Title")
```
