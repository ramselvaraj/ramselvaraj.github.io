---
permalink: /emacs-config/
title: "Emacs Config"
author_profile: true 
---

{% include base_path %}
```lua
-- Define a table
local person = {
  name = "John Doe",
  age = 30,
  occupation = "Software Engineer"
}

-- Function to greet the person
function greet(person)
  print("Hello, my name is " .. person.name .. " and I'm a " .. person.occupation .. ".")
end

-- Call the greet function
greet(person)

-- Iterate over a table
local numbers = {1, 2, 3, 4, 5}
for i, num in ipairs(numbers) do
  print(num)
end

-- Perform a calculation
local a = 5
local b = 10
local sum = a + b
print("The sum of " .. a .. " and " .. b .. " is " .. sum .. ".")

-- Define a simple module
local myModule = {}

function myModule.sayHello()
  print("Hello from the myModule!")
end

return myModule
```

