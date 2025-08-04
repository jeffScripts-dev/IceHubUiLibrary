# Ice Hub Ui Library
Ice hub Ui library thats Everyone and Finally Created

## 📥 Load Library  
`local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/jeffScripts-dev/jeffScripts-dev/main/IceHubUILibrary"))()`

## 🪟 Create Window  
`local Window = Library:CreateWindow("IceHub - Brookhaven")`

## 📁 Create Tabs  
`local NameTab = Window:CreateTab("Name tab")`

## 📦 Sections  
`MainTab:CreateSection("Settings")`

## 🔘 Buttons  
`MainTab:CreateButton("Print", function() print("Button Clicked!") end)`

## ✅ Toggles  
`MainTab:CreateToggle("Ativar Modo Turbo", false, function(state) print("Modo Turbo:", state) end)`

## 📝 Textbox  
`MainTab:CreateTextbox("Digite seu nome", function(text) print("Nome digitado:", text) end)`

## 🔽 Dropdown  
`MainTab:CreateDropdown("Choose you want", {"1", "2", "Nothing"}, function(option) print("I Choose:", option) end)`

---

I hope this helps you create your own script! 💻✨
