-- song lyrics
local lyrics = {
 "OH",
 "OH OH",
 "OH OH OH", 
 "OH OH OH OHIO",
 "welcome to my skibidi toilet"
 "OH",
 "OH OH",
 "OH OH OH", 
 "OH OH OH OHIO",
 "please dont leave...",
 "i have no gyatt🥺🥺🥺🗣️🗣️🗣️🗣️🗣️",
 "OH",
 "OH OH",
 "OH OH OH", 
 "OH OH OH OHIO",
 "lets go sigma", 
 "LET ME RIZZ YA",
 "OH",
 "OH OH",
 "OH OH OH", 
 "OH OH OH OHIO",
 "HAHA I PRAYED TODAY"
}
-- Chat function
local function singLyrics()
    for _, lyric in ipairs(lyrics) do
        game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(lyric, "All")
        wait(2.5) -- Adjust the delay as desired
    end
end

-- Start singing
singLyrics()
