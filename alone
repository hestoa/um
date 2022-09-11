#include <sourcemod> 
#include <zombiereloaded>

public Action:ZR_OnClientInfect(&client, &attacker, &bool:motherInfect, &bool:respawnOverride, &bool:respawn) 
{ 
        new players = GetClientCount(true); 
          
        if (players <= 3) 
        { 
                PrintToChatAll("[ZR] There aren't enough players to create a zombie."); 
                return Plugin_Handled; 
        } 
          
        return Plugin_Continue; 
} 
