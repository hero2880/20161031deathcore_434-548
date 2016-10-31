# Copyright (C) 2016 DeathCore <http://www.noffearrdeathproject.org/>
#
# This file is free software; as a special exception the author gives
# unlimited permission to copy and/or distribute it, with or without
# modifications, as long as this notice is preserved.
#
# This program is distributed in the hope that it will be useful, but
# WITHOUT ANY WARRANTY, to the extent permitted by law; without even the
# implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

file(GLOB_RECURSE scripts_Custom Custom/*.cpp Custom/*.h)
source_group(Custom FILES ${scripts_Custom})

set(scripts_STAT_SRCS
  ${scripts_STAT_SRCS}
 # ${scripts_Custom}
 
Custom/anti_divulgador.cpp
Custom/auto_quest_complete.cpp
Custom/comando_fake_players.cpp
Custom/comando_vip.cpp
Custom/morphs_npc.cpp
Custom/npc_visualweapon.cpp
Custom/sistema_gold.cpp
Custom/token_vip_30d.cpp
Custom/VIP_Item_60d.cpp
Custom/token_vip_120d.cpp
Custom/token_vip_240d.cpp
Custom/token_vip_480d.cpp
Custom/VIP_Item_960d.cpp
Custom/VIP_NPC.cpp
)

message("  -> Prepared: Custom")
