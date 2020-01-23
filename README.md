# new-samp-callbacks
New SA-MP callbacks

Callbacks:

	    OnPlayerPause(playerid)
	    Description: Called when a player is paused.
	    OnPlayerResume(playerid, time)
	    Description: Called when a player has resumed.
	    OnPlayerHoldingKey(playerid, keys)
	    Description: Called when a player begins holding a specific key.
	    OnPlayerReleaseKey(playerid, keys)
	    Description: Called when a player releases a key.
	    OnPlayerFall(playerid, Float:damage)
	    Description: Called when a player falls and loses damage.
	    OnPlayerPacketLoss(playerid, Float:newpacket, Float:oldpacket)
	    Description: Called when a player experiences packet loss.
	    OnPlayerUseVending(playerid, type)
	    Description: Called when a player uses a vending machine.
	    OnPlayerCrashVehicle(playerid, vehicleid, Float:damage)
	    Description: Called when a player crashes a vehicle.
	    OnPlayerFPSChange(playerid, oldfps, newfps)
	    Description: Called when a player's FPS rate changes.
	    OnPlayerJackVehicle(playerid, targetid, vehicleid)
	    Description: Called when a player jacks another player's vehicle.
	    OnPlayerEmptyWeapon(playerid, weaponid)
	    Description: Called when a player depletes all ammo in a weapon.
	    OnPlayerFriendlyFire(playerid, targetid, weaponid)
	    Description: Called when a player shoots at a teammate.
	    OnPlayerTargetPlayer(playerid, targetid, weaponid)
	    Description: Called when a player targets a player with their weapon.
		  OnPlayerHideCursor(playerid, hovercolor)
	    Description: Called when a player cancels textdraw selection.
	    OnPlayerAntiReload(playerid, weaponid)
	    Description: Called when a player shoots without reloading their weapon.
	    OnPlayerAnimationPlay(playerid, animlib[], animname[])
	    Description: Called when an animation is played.
	    OnPlayerReloadWeapon(playerid, weaponid, ammo)
	    Description: Called when a player reloads their weapon.
      OnPlayerActionChange(playerid, oldaction, newaction)
	    Description: Called when a player's action change (see action list).
      OnPlayerRamPlayer(playerid, driverid, vehicleid, Float:damage)
	    Description: Called when a player rams another player.
		  OnPlayerSprayAtVehicle(playerid, vehicleid)
      Description: Called wehn a player is spraying at a vehicle.
	    OnPlayerStartBurn(playerid)
	    Description: Called when a player is burning from fire.
	    OnPlayerStopBurn(playerid)
	    Description: Called when a player stops burning.
	    OnPlayerStartAim(playerid, weaponid)
	    Description: Called when a player is aiming a weapon.
	    OnPlayerStopAim(playerid)
	    Description: Called when a player stops aiming.
	    OnPlayerUseCamera(playerid)
	  	Description: Called when a player snaps a picture with a camera (weapon ID: 43).
		  OnPlayerJump(playerid)
		  Description: Called when a player jumps (SHIFT key).
  		OnPlayerUseGarage(playerid, vehicleid, type)
	  	Description: Called when a player uses a Pay'n'Spray or bomb shop.
	  	OnVehicleCreated(vehicleid, color1, color2)
	  	Description: Called when a vehicle is created by the server.
	    Definitions:
	    POTENTIAL_CRASH_DAMAGE
	    Description: The maximum amount of damage a vehicle must take before being ruled as a crash.
		  MAX_ACCUMULATED_SHOTS
		  Description: The maximum amount of shots the player fired without reloading before calling OnPlayerAntiReload.
