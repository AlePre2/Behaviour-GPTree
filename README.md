# Behaviour-GPTree
 
This is a simple example project to integrate openai API in Unreal Engine.
This sample project shows how you can talk to NPCs and create their background using artifical intelligence.

QuickStart:

1) Open the CMD and paste this:
 git clone "https://github.com/openai/openai-quickstart-node.git
 (Make sure to have git installed)
 
2) Paste the directory of you'r unreal editor and use this command:
 "\UE_5.0\Engine\Binaries\ThirdParty\Python\Win64\python.exe" -m pip install openai
 
3) Open the project and go in to Content->GPT_Code->Blueprints->GPT_Component and set you'r openai API key, you can generate one here:
 "https://beta.openai.com/account/api-keys"

Now play and everything should work!


Additional:

-Remember to add the GPT_Component to the gamemode you are using

-You can set the player name from the GPT_Component

-If you need longer replies and they get truncated increase the max tof tokens from the Chat_GPT component

-Select the NPC in the world and from the details panel change his Name and NPC Info

-Tested on 5.0 and 5.1

Warnings:

-The pyton functions are not asynchronous so until you recive a reply the game will be frozen

-Be careful not to use too many credits if you have a paid openai account
