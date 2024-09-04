[![Stardew Valley](https://custom-icon-badges.demolab.com/badge/Stardew_Valley-FFD58E.svg?logo=stardewvalley)](https://stardewvalleywiki.com/Stardew_Valley)
[![Yet Another Content Patcher YAML](https://custom-icon-badges.demolab.com/badge/Yet_Another_Content_Patcher-YAML-CB171E.svg?logo=smapi)](https://github.com/linkoid/Stardew.YetAnother.ContentPatcher)
[![Space Core](https://custom-icon-badges.demolab.com/badge/Space_Core-gray?logo=smapi)](https://github.com/spacechase0/StardewValleyMods/tree/develop/SpaceCore)
[![Custom Tokens](https://custom-icon-badges.demolab.com/badge/Custom_Tokens-gray.svg?logo=smapi)](https://github.com/TheMightyAmondee/CustomTokens)


Content.yaml is restricted to Dynamic Tokens, Generic Mod Config Menu, included files, and blankloading to have edit/data for other .yamls

Edelweiss.yaml has the Data/Character layout with expansive comments


	NECESSARY FILES:

Blank.yaml is necessary for creating the initial space for your custom npc in specific files
	
Content.yaml is how Content Patcher reads your file entirely
	
Manifest.yaml is how Content Patcher sees your mod


	Questions:

"Can I put all of these other files into content.yaml?"
	
Of course! I've just separated them all for clarity (for myself) as well as if anyone had a peculiar question for one specific thing, I already had things set aside


	OPTIONAL FILES:

Default.yaml is not necessary for a custom NPC, but it is heavily incentivized for translation and clarity purposes
	
Birthday.yaml is not necessary for a custom NPC, this is my integration of a birthday event
	
Children.yaml is not necessary for a custom NPC, this is my integration for different children events
	
DeathInsurance.yaml is not necessary for a custom NPC, this is for my integration for the spouse to protect the farmer from passing out / fainting
	
Mail.yaml is not necessary for a custom NPC, you can go without creating a single letter for your custom NPC
	
SpaceCore.yaml is not necessary for a custom NPC, this is my integration for animationDescriptions.yaml to have sound effects, a custom warp totem, and any other things I wanted
	
SpecialOrders.yaml is not necessary for a custom NPC, this is if you wanted to integrate quests into your NPC
	
StringsFromCSFiles.yaml is not necessary as there is a vast list of strings to change and there are just a few strings that I wanted to have custom
	
TownComments.yaml is not necessary unless you'd like an expansive dialogue surrounding your custom NPC

TriggerActions.yaml is not necessary as you don't have to have repeating events, or special tokenized events for your NPC

WipedMemory.yaml is not necessary as you don't need to have specialization for your custom NPC if their memory is wiped after divorce
