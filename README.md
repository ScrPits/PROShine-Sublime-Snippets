# Text-Editor-Auto-Complete-PROShine
## Sublime Snippets, AutoComplete .lua functions. Built For PROShine
<hr>

# How each snippet looks
```
<snippet>
	<content><![CDATA[attack()]]></content>
	<description>Uses the most effective offensive move available.</description>
	<tabTrigger>attack</tabTrigger>
	<scope>source.lua</scope>
</snippet>
```

<hr>

## Full list for easy of view
```
    ["log"]
    ["fatal"]
    ["logout"] 
    ["stringContains"]
    ["playSound"]
    ["registerHook"] 
```
## General conditions
```
    ["getPlayerX"]
    ["getPlayerY"]
    ["getAccountName"] 
    ["getMapName"] 
    ["getPokedexOwned"] 
    ["getPokedexSeen"]
    ["getPokedexEvolved"] 
    ["getTeamSize"] 
    ["isAccountMember"]

    ["getPokemonId"] 
    ["getPokemonName"]
    ["getPokemonHealth"] 
    ["getPokemonHealthPercent"]
    ["getPokemonMaxHealth"]
    ["getPokemonLevel"]
    ["getPokemonTotalExperience"]
    ["getPokemonRemainingExperience"]
    ["getPokemonStatus"]
    ["getPokemonForm"] 
    ["getPokemonHeldItem"]
    ["getPokemonUniqueId"] 
    ["getRemainingPowerPoints"] 
    ["getPokemonMaxPowerPoints"]
    ["isPokemonShiny"]
    ["getPokemonMoveName"] 
    ["getPokemonMoveAccuracy"] 
    ["getPokemonMovePower"] 
    ["getPokemonMoveType"]
    ["getPokemonMoveDamageType"] 
    ["getPokemonMoveStatus"] 
    ["getPokemonNature"]
    ["getPokemonAbility"] 
    ["getPokemonStat"] 
    ["getPokemonEffortValue"]
    ["getPokemonIndividualValue"]
    ["getPokemonHappiness"]
    ["getPokemonRegion"]
    ["getPokemonOriginalTrainer"] 
    ["getPokemonGender"]
    ["getPokemonType"]
    ["getDamageMultiplier"] 
    ["isPokemonUsable"] 
    ["getUsablePokemonCount"] 
    ["hasMove"] 
    ["getActiveBattlers"] 
    ["getActiveDigSpots"]
    ["getActiveHeadbuttTrees"]
    ["getActiveBerryTrees"] 
    ["getDiscoverableItems"] 
    ["getNpcData"]

    ["hasItem"]
    ["getItemQuantity"] 
    ["hasItemId"] 
    ["getItemQuantityId"]

    ["hasPokemonInTeam"] 
    ["isTeamSortedByLevelAscending"] 
    ["isTeamSortedByLevelDescending"]
    ["isTeamRangeSortedByLevelAscending"]
    ["isTeamRangeSortedByLevelDescending"] 
    ["isNpcVisible"] 
    ["isNpcOnCell"]
    ["isShopOpen"] 
    ["getMoney"]
    ["isMounted"]
    ["isSurfing"]
    ["isPrivateMessageEnabled"]
    ["getTime"] 
    ["isMorning"]
    ["isNoon"] 
    ["isNight"]
    ["isOutside"]
    ["isAutoEvolve"] 
    ["isTeamInspectionEnabled"]

    ["isCurrentPCBoxRefreshed"]
    ["getCurrentPCBoxId"] 
    ["isPCOpen"] 
    ["getCurrentPCBoxId"] 
    ["getCurrentPCBoxSize"] 
    ["getPCBoxCount"] 
    ["getPCPokemonCount"] 

    ["getPokemonIdFromPC"]
    ["getPokemonNameFromPC"]
    ["getPokemonHealthFromPC"]
    ["getPokemonHealthPercentFromPC"] 
    ["getPokemonMaxHealthFromPC"] 
    ["getPokemonLevelFromPC"]
    ["getPokemonTotalExperienceFromPC"]
    ["getPokemonRemainingExperienceFromPC"] 
    ["getPokemonStatusFromPC"] 
    ["getPokemonTypeFromPC"] 
    ["getPokemonHeldItemFromPC"]
    ["getPokemonUniqueIdFromPC"] 
    ["getPokemonRemainingPowerPointsFromPC"] 
    ["getPokemonMaxPowerPointsFromPC"] 
    ["isPokemonFromPCShiny"] 
    ["getPokemonMoveNameFromPC"]
    ["getPokemonMoveAccuracyFromPC"]
    ["getPokemonMovePowerFromPC"] 
    ["getPokemonMoveTypeFromPC"]
    ["getPokemonMoveDamageTypeFromPC"]
    ["getPokemonMoveStatusFromPC"]
    ["getPokemonNatureFromPC"] 
    ["getPokemonAbilityFromPC"] 
    ["getPokemonStatFromPC"] 
    ["getPokemonEffortValueFromPC"] 
    ["getPokemonIndividualValueFromPC"] 
    ["getPokemonHappinessFromPC"] 
    ["getPokemonRegionFromPC"] 
    ["getPokemonOriginalTrainerFromPC"]
    ["getPokemonGenderFromPC"] 
    ["getPokemonFormFromPC"]

    ["getServer"]
```
## Battle conditions
```
    ["isOpponentShiny"]
    ["isAlreadyCaught"]
    ["isWildBattle"] 
    ["getActivePokemonNumber"]
    ["getOpponentId"] 
    ["getOpponentName"]
    ["getOpponentHealth"] 
    ["getOpponentMaxHealth"]
    ["getOpponentHealthPercent"]
    ["getOpponentLevel"]
    ["getOpponentStatus"]
    ["getOpponentForm"] 
    ["isOpponentEffortValue"]
    ["getOpponentEffortValue"]
    ["getOpponentType"]
```
## Path actions
```
    ["moveToCell"] 
    ["moveToMap"]
    ["moveToRectangle"]

    ["moveToNormalGround"] 
    ["moveToGrass"]
    ["moveToWater"]
    ["moveNearExit"] 
    ["talkToNpc"]
    ["talkToNpcOnCell"]
    ["usePokecenter"]
    ["swapPokemon"] 
    ["swapPokemonWithLeader"]
    ["sortTeamByLevelAscending"]
    ["sortTeamByLevelDescending"]
    ["sortTeamRangeByLevelAscending"]
    ["sortTeamRangeByLevelDescending"]
    ["buyItem"] 
    ["usePC"] 
    ["openPCBox"] 
    ["depositPokemonToPC"] 
    ["withdrawPokemonFromPC"]
    ["swapPokemonFromPC"] 
    ["giveItemToPokemon"] 
    ["takeItemFromPokemon"] 
    ["releasePokemonFromTeam"] 
    ["releasePokemonFromPC"] 
    ["enablePrivateMessage"] 
    ["disablePrivateMessage"] 
    ["enableAutoEvolve"]
    ["disableAutoEvolve"]
```
## Path functions
```
    ["pushDialogAnswer"]
```
## General actions
```
    ["useItem"] 
    ["useItemOnPokemon"]
```
## Battle actions
```
    ["attack"] 
    ["weakAttack"]
    ["run"]
    ["sendUsablePokemon"]
    ["sendAnyPokemon"] 
    ["sendPokemon"] 
    ["useMove"]
```
## Move learning actions
```
    ["forgetMove"] 
    ["forgetAnyMoveExcept"] 
```

## Custom option slider functions
> These Lua Functions are not added to the source yet.
```
    ["setOption"]
    ["getOption"]
    ["setOptionName"] 
    ["setOptionDescription"]
    ["removeOption"] 
```
## Custom text option functions
> These Lua Functions are not added to the source yet.
```
    ["setTextOption"]
    ["getTextOption"] 
    ["setTextOptionName"]
    ["setTextOptionDescription"] 
    ["removeTextOption"]
```
## File editing actions
> These Lua Functions are not added to the source yet.
```
    ["logToFile"]
    ["readLinesFromFile"]
    ["getInputDialog"]
```
## Taos
> These Lua Functions are not added to the source yet.
```
    ["getSpawnList"] 

    ["login"]
    ["relog"]
    ["startScript"] 
    ["invoke"]
    ["cancelInvokes"] 
 
    ["enableTrainerBattles"] 
    ["disableTrainerBattles"]
    ["disableTeamInspection"]
    ["enableTeamInspection"]
```
