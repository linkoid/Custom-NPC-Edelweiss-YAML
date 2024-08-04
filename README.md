Content.json is restricted to Dynamic Tokens, Generic Mod Config Menu, included files, and blankloading to have edit/data for other .jsons
Edelweiss.json has the Data/Character layout with expansive comments

NECESSARY FILES:
Blank.json is necessary for creating the initial space for your custom npc in specific files
Content.json is how Content Patcher reads your file entirely
Manifest.json is how Content Patcher sees your mod

Questions:
"Can I put all of these other files into content.json?"
Of course! I've just separated them all for clarity (for myself) as well as if anyone had a peculiar question for one specific thing, I already had things set aside

OPTIONAL FILES:
Default.json is not necessary for a custom NPC, but it is heavily incentivized for translation and clarity purposes
Birthday.json is not necessary for a custom NPC, this is my integration of a birthday event
Children.json is not necessary for a custom NPC, this is my integration for different children events
DeathInsurance.json is not necessary for a custom NPC, this is for my integration for the spouse to protect the farmer from passing out / fainting
Mail.json is not necessary for a custom NPC, you can go without creating a single letter for your custom NPC
SpaceCore.json is not necessary for a custom NPC, this is my integration for animationDescriptions.json to have sound effects, a custom warp totem, and any other things I wanted
SpecialOrders.json is not necessary for a custom NPC, this is if you wanted to integrate quests into your NPC
StringsFromCSFiles.json is not necessary as there is a vast list of strings to change and there are just a few strings that I wanted to have custom
TownComments.json is not necessary unless you'd like an expansive dialogue surrounding your custom NPC
TriggerActions.json is not necessary as you don't have to have repeating events, or special tokenized events for your NPC
WipedMemory.json is not necessary as you don't need to have specialization for your custom NPC if their memory is wiped after divorce
