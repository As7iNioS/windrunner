
########### next target ###############

SET(game_STAT_SRCS
   AccountMgr.cpp
   AccountMgr.h
   AddonHandler.cpp
   AddonHandler.h
   AggressorAI.cpp
   AggressorAI.h
   AOEAI.cpp
   AOEAI.h
   ArcherAI.cpp
   ArcherAI.h
   ArenaTeam.cpp
   ArenaTeam.h
   ArenaTeamHandler.cpp
   AuctionHouseHandler.cpp
   AuctionHouseMgr.cpp
   AuctionHouseMgr.h
   Bag.cpp
   Bag.h
   BattleGround.cpp
   BattleGroundAA.cpp
   BattleGroundAB.cpp
   BattleGroundAV.cpp
   BattleGroundBE.cpp
   BattleGroundEY.cpp
   BattleGroundNA.cpp
   BattleGroundRL.cpp
   BattleGroundWS.cpp
   BattleGround.h
   BattleGroundAA.h
   BattleGroundAB.h
   BattleGroundAV.h
   BattleGroundBE.h
   BattleGroundEY.h
   BattleGroundNA.h
   BattleGroundRL.h
   BattleGroundWS.h
   BattleGroundHandler.cpp
   BattleGroundMgr.cpp
   BattleGroundMgr.h
   Cell.h
   CellImpl.h
   Channel.cpp
   Channel.h
   ChannelHandler.cpp
   ChannelMgr.h
   CharacterHandler.cpp
   ChargeMovementGenerator.cpp
   ChargeMovementGenerator.h
   Chat.cpp
   Chat.h
   ChatHandler.cpp
   CombatHandler.cpp
   ConditionMgr.cpp
   ConditionMgr.h
   ConfusedMovementGenerator.cpp
   ConfusedMovementGenerator.h
   Corpse.cpp
   Corpse.h
   CreatureAI.cpp
   CreatureAI.h
   CreatureAIImpl.h
   CreatureAINew.cpp
   CreatureAINew.h
   CreatureAIRegistry.cpp
   CreatureAIRegistry.h
   CreatureAISelector.cpp
   CreatureAISelector.h
   Creature.cpp
   Creature.h
   CreatureGroups.cpp
   CreatureGroups.h
   CreatureTextMgr.cpp
   CreatureTextMgr.h
   CreatureScript.h
   Debugcmds.cpp
   DestinationHolder.cpp
   DestinationHolder.h
   DestinationHolderImp.h
   DuelHandler.cpp
   DynamicObject.cpp
   DynamicObject.h
   DynamicTree.cpp
   DynamicTree.h
   FleeingMovementGenerator.cpp
   FleeingMovementGenerator.h
   Formulas.h
   GameEvent.cpp
   GameEvent.h
   GameObject.cpp
   GameObject.h
   GameObjectAI.cpp
   GameObjectAI.h
   GameObjectModel.cpp
   GameObjectModel.h
   GlobalEvents.cpp
   GlobalEvents.h
   GossipDef.cpp
   GossipDef.h
   GridDefines.h
   GridNotifiers.cpp
   GridNotifiers.h
   GridNotifiersImpl.h
   GridStates.cpp
   GridStates.h
   Group.cpp
   Group.h
   GroupHandler.cpp
   GuardAI.cpp
   GuardAI.h
   Guild.cpp
   Guild.h
   GuildHandler.cpp
   HomeMovementGenerator.cpp
   HomeMovementGenerator.h
   HostilRefManager.cpp
   HostilRefManager.h
   IdleMovementGenerator.cpp
   IdleMovementGenerator.h
   InstanceData.cpp
   InstanceData.h
   InstanceSaveMgr.cpp
   InstanceSaveMgr.h
   Item.cpp
   Item.h
   ItemEnchantmentMgr.cpp
   ItemEnchantmentMgr.h
   ItemHandler.cpp
   ItemPrototype.h
   Language.h
   Level0.cpp
   Level1.cpp
   Level2.cpp
   Level3.cpp
   LFGHandler.cpp
   LootHandler.cpp
   LootMgr.cpp
   LootMgr.h
   Mail.cpp
   Mail.h
   Map.cpp
   Map.h
   MapInstanced.cpp
   MapInstanced.h
   MapManager.cpp
   MapManager.h
   MiscHandler.cpp
   MotionMaster.cpp
   MotionMaster.h
   MoveMap.cpp
   MoveMap.h
   MoveMapSharedDefines.h
   MovementGenerator.cpp
   MovementGenerator.h
   MovementGeneratorImpl.h
   MovementHandler.cpp
   NPCHandler.cpp
   NPCHandler.h
   NullCreatureAI.cpp
   NullCreatureAI.h
   ObjectAccessor.cpp
   ObjectAccessor.h
   Object.cpp
   ObjectDefines.h
   ObjectGridLoader.cpp
   ObjectGridLoader.h
   Object.h
   ObjectMgr.cpp
   ObjectMgr.h
   Opcodes.cpp
   Opcodes.h
   OutdoorPvP.cpp
   OutdoorPvP.h
   OutdoorPvPEP.cpp
   OutdoorPvPEP.h
   OutdoorPvPHP.cpp
   OutdoorPvPHP.h
   OutdoorPvPMgr.cpp
   OutdoorPvPMgr.h
   OutdoorPvPNA.cpp
   OutdoorPvPNA.h
   OutdoorPvPObjectiveAI.cpp
   OutdoorPvPObjectiveAI.h
   OutdoorPvPSI.cpp
   OutdoorPvPSI.h
   OutdoorPvPTF.cpp
   OutdoorPvPTF.h
   OutdoorPvPZM.cpp
   OutdoorPvPZM.h
   Path.h
   PathFinder.cpp
   PathFinder.h
   PetAI.cpp
   PetAI.h
   Pet.cpp
   Pet.h
   PetHandler.cpp
   PetitionsHandler.cpp
   Player.cpp
   Player.h
   PlayerDump.cpp
   PlayerDump.h
   PointMovementGenerator.cpp
   PointMovementGenerator.h
   PossessedAI.cpp
   PossessedAI.h
   QueryHandler.cpp
   QuestDef.cpp
   QuestDef.h
   QuestHandler.cpp
   RandomMovementGenerator.cpp
   RandomMovementGenerator.h
   RegularGrid.h
   ReactorAI.cpp
   ReactorAI.h
   ScriptCalls.cpp
   ScriptCalls.h
   SharedDefines.h
   SkillHandler.cpp
   SmartAI.cpp
   SmartAI.h
   SmartScript.cpp
   SmartScript.h
   SmartScriptMgr.cpp
   SmartScriptMgr.h
   SpellAuraDefines.h
   SpellAuras.cpp
   SpellAuras.h
   Spell.cpp
   SpellEffects.cpp
   Spell.h
   SkillDiscovery.cpp
   SkillDiscovery.h
   SkillExtraItems.cpp
   SkillExtraItems.h
   SpellHandler.cpp
   SocialMgr.cpp
   SocialMgr.h
   SpectatorAddon.cpp
   SpectatorAddon.h
   SpellMgr.cpp
   SpellMgr.h
   SpellScript.h
   StatSystem.cpp
   TargetedMovementGenerator.cpp
   TargetedMovementGenerator.h
   TaxiHandler.cpp
   TemporarySummon.cpp
   TemporarySummon.h
   TicketHandler.cpp
   Tools.cpp
   Tools.h
   TotemAI.cpp
   TotemAI.h
   Totem.cpp
   Totem.h
   TradeHandler.cpp
   Transports.cpp
   Transports.h
   ThreatManager.cpp
   ThreatManager.h
   Traveller.h
   Unit.cpp
   Unit.h
   UnitEvents.h
   UpdateData.cpp
   UpdateData.h
   UpdateFields.h
   UpdateMask.h
   VoiceChatHandler.cpp
   WaypointManager.cpp
   WaypointManager.h
   WaypointMovementGenerator.cpp
   WaypointMovementGenerator.h
   Weather.cpp
   Weather.h
   World.cpp
   World.h
   WorldLog.cpp
   WorldLog.h
   WorldSession.cpp
   WorldSession.h
   WorldSocket.cpp
   WorldSocket.h
   WorldSocketMgr.cpp
   WorldSocketMgr.h
   FollowerReference.cpp
   FollowerReference.h
   FollowerRefManager.h
   GroupReference.cpp
   GroupReference.h
   GroupRefManager.h
   WardenBase.cpp
   WardenBase.h
   WardenDataStorage.cpp
   WardenDataStorage.h
   WardenMac.cpp
   WardenMac.h
   WardenModuleMac.h
   WardenModuleWin.h
   WardenWin.cpp
   WardenWin.h
    ../scripts/ScriptMgr.cpp
    ../scripts/ScriptMgr.h
)

IF(UNIX)
add_definitions(-D_TRINITY_SCRIPT_CONFIG='"${CONF_DIR}/trinitycore.conf"')
add_definitions(-fopenmp)
ELSEIF(WIN32 AND MSVC)
add_definitions(/openmp)
ENDIF()
add_library(game STATIC ${game_STAT_SRCS})
ADD_DEPENDENCIES(game revision.h)
target_link_libraries(
game
scripts
detour
recast
)
