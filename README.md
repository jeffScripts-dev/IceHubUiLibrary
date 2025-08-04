# Ice Hub Ui Library
Ice hub Ui library thats Everyone and Finally Created

## 📥 Load Library  
```lua
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/jeffScripts-dev/jeffScripts-dev/main/IceHubUILibrary"))()
```

## 🪟 Create Window  
```lua
local Window = Library:CreateWindow("IceHub - Brookhaven")
```

## 📁 Create Tabs  
```lua
local NameTab = Window:CreateTab("Name tab")
```

## 📦 Sections  
```lua
MainTab:CreateSection("Settings")
```

## Labels
```lua
MainTab:CreateLabel("Welcome to IceHub!")
```

## 🔘 Buttons  
```lua
MainTab:CreateButton("Print", function()
    print("Button Clicked!")
end)
```

## ✅ Toggles  
```lua
MainTab:CreateToggle("Ativar Modo Turbo", false, function(state)
    print("Modo Turbo:", state)
end)
```

## 📝 Textbox  
```lua
MainTab:CreateTextbox("Digite seu nome", function(text)
    print("Nome digitado:", text)
end)
```

## 🔽 Dropdown  
```lua
MainTab:CreateDropdown("Choose you want", {"1", "2", "Nothing"}, function(option)
    print("I Choose:", option)
end)
```

---

I hope this helps you create your own script! 💻✨
