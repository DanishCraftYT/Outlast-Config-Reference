# DefaultGame.ini

## [Configuration]

BasedOn=..\Engine\Config\BaseGame.ini<br>
??<br>

## [Patches]

StruggleNoFail=False<br>
??<br>

## [OLGame.OLCheatManager]

bCheatsEnabled=false<br>
determines if cheats are enabled or not.<br>

bUnlimitedBatteries=false<br>
determines if the player has unlimited batteries or not.<br>

## [OLGame.OLGame]

bIsDemo=false<br>
??<br>

bForcePlayingDLC=false<br>
??<br>

DefaultMapName=Intro_Persistent<br>
??<br>

DemoMapName=Demo_Intro_Persistent<br>
??<br>

DLCInstalledMapName=DLC_Intro_Persistent<br>
??<br>

## [OLGame.OLDLCManager]

bFakeDLCInstalledLoose=true<br>
??<br>

bFakeDLCInstalledCooked=false<br>
??<br>

## [Engine.GameInfo]

DefaultGame=OLGame.OLGame<br>
??<br>

DefaultServerGame=OLGame.OLGame<br>
??<br>

PlayerControllerClassName=OLGame.OLPlayerController<br>
??<br>

DefaultGameType="OLGame.OLGame"<br>
??<br>

## [OLGame.OLTutorialManager]

bTutorialsEnabled=true<br>
??<br>

## [OLGame.OLHUD]

bShowCrosshair=true<br>
??<br>

NewObjectiveZoneRadius=350.0<br>
??<br>

bShowSubtitles=true<br>
??<br>

bForcePS4UI=false<br>
??<br>

## [OLGame.OLHero]

FirstFingerlessCheckpoint=Male_TortureDone<br>
??<br>

ShatteredCameraGlassCheckpoint=Female_LostCam<br>
??<br>

ITUniformCheckpoint=DLC_Lab_Start<br>
??<br>

PrisonerUniformCheckpoint=Hospital_Start<br>
??<br>

### Player Speed

NormalWalkSpeed=200<br>
determines how fast the player walks.<br>

NormalRunSpeed=450<br>
determines how fast the player runs.<br>

CrouchedSpeed=75<br>
determines how fast the player walks when crouched.<br>

WaterWalkSpeed=100<br>
determines how fast the player walks when in water.<br>

WaterRunSpeed=200<br>
determines how fast the player runs when in water.<br>

LimpingWalkSpeed=87.243<br>
determines how fast the player walks when limping.<br>

HobblingWalkSpeed=140<br>
determines how fast the player walks when hobbling.<br>

HobblingRunSpeed=250<br>
determines how fast the player runs when hobbling.<br>

ElectrifiedSpeed=100<br>
??<br>

SpeedPenaltyBackwards=0.35<br>
determines how much the player slows down when walking backwards.<br>

SpeedPenaltyStrafe=0.2<br>
determines how much the player slows down when strafing.<br>

### Player Jump

ForwardSpeedForJumpWalking=450<br>
??<br>

ForwardSpeedForJumpRunning=650<br>
??<br>

JumpClearanceWalking=200<br>
??<br>

JumpClearanceRunning=300<br>
??<br>

### ??

ExternalImpulseDecelCoeff=0.97<br>
??<br>

ExternalImpulseMinVel=60.0<br>
??<br>

ExternalImpulseMaxVel=1500.0<br>
??<br>

ExternalImpulseMaxVelCrouched=750.0f<br>
??<br>

### Fall Speed Damage

FallSpeedForDamage=1250.0<br>
??<br>

FallSpeedForDeath=1500.0<br>
??<br>

FallDamageExponent=1.5<br>
??<br>

### Ledges

JumpForwardFromLedgeWalkXYSpeed=400<br>
??<br>

JumpForwardFromLedgeWalkZSpeed=350<br>
??<br>

DropFromLedgeWalkXYSpeed=150<br>
??<br>

DropFromLedgeWalkZSpeed=300<br>
??<br>

### ??

LandingPenaltyDuration=1.0<br>
??<br>

LandingSpeedModifier=0.25<br>
??<br>

### ??

ElectrifiedJumpDelay=0.25<br>
??<br>

### Player FOV

DefaultFOV=90.0<br>
determines the default POV for the player.<br>

RunningFOV=100.0<br>
determines the FOV when the player is running.<br>

FOVApproachCoeffOpening=0.97<br>
??<br>

FOVApproachCoeffClosing=0.97<br>
??<br>

FOVApproachCoeffRun=0.4<br>
??<br>

FOVApproachCoeffWalk=0.97<br>
??<br>

#### Camera FOV

CamcorderMinFOV=15.0<br>
determines the minimum FOV for the camera.<br>

CamcorderNVMaxFOV=83.0<br>
??: determines the maximum FOV for the camera when Night Vision is on.<br>

CamcorderMaxFOV=83.0<br>
determines the maximum FOV for the camera.<br>

### Night Vision Light

NVLightZoomedInInnerAngle=2.0<br>
??<br>

NVLightZoomedInOuterAngle=5.0<br>
??<br>

NVLightZoomedInRadius=1500.0<br>
??<br>

NVLightZoomedInBrightness=0.025<br>
??<br>

### DarkLight

DarkLightBrightnessDefault=0.01<br>
??<br>

DarkLightRadiusDefault=100.0<br>
??<br>

DarkLightBrightnessNoCamcorder=0.03<br>
??<br>

DarkLightRadiusNoCamcorder=175.0<br>
??<br>

DarkLightBrightnessBothHandsNeeded=0.03<br>
??<br>

DarkLightRadiusBothHandsNeeded=125.0<br>
??<br>

DarkLightBrightnessAttacked=0.025<br>
??<br>

DarkLightRadiusAttacked=140.0<br>
??<br>

DarkLightBrightnessParrying=0.015<br>
??<br>

DarkLightRadiusParrying=140.0<br>
??<br>

### Battery Duration

NrmBatteryDuration=150.0<br>
determines how long batteries last on Normal difficulty.<br>

HardBatteryDuration=150.0<br>
determines how long batteries last on Hard difficulty.<br>
??: includes Nightmare and Insane difficulties?<br>

### Night Vision Glitch

NVGlitchTimeThreshold=25.0<br>
??<br>

NVGlitchMaxDelayStart=8.0<br>
??<br>

NVGlitchMaxDelayEnd=5.0<br>
??<br>

NVGlitchMinDuration=0.5<br>
??<br>

NVGlitchMaxDuration=3.0<br>
??<br>

NVGlitchMaxLevel=0.5<br>
??<br>

### Pickups

MinCosAngleForPickup=0.98<br>
??<br>

PickupInteractRadius=30.0<br>
??<br>

### Health Regeneration

HealthRegenDelay=10.0<br>
??<br>

HealthRegenRate=10.0<br>
??<br>

### Hobble

HobbleApproachRate=0.05<br>
??<br>

### Electric

ElectricEffectPeriod=0.4<br>
??<br>

ElectricEffectBase=0.4<br>
??<br>

ElectricEffectMode=2 ; 0: sine, 1: increasing sawtooth, 2: decreasing sawtooth<br>
??<br>

ElectricHurtSoundInterval=0.8<br>
??<br>

### Heat

HeatDamageDist=150.0<br>
??<br>

HeatDamageInterval=0.6<br>
??<br>

HeatDamagePerSec=15.0<br>
??<br>

HeatMaxBlurDist=75.0<br>
??<br>

HeatMinBlurDist=250.0<br>
??<br>

HeatMinBlurAmount=0.8<br>
??<br>

HeatBlurApproachCoeffIn=0.99<br>
??<br>

HeatBlurApproachCoeffOut=0.5<br>
??<br>

### Death Screen

DeathScreenDuration=7.5<br>
??<br>

### Footsteps

NumBloodyFootsteps=12<br>
??<br>

### Look Back Camera Offset

LookBackCamRotOffset=155.0<br>
??<br>

LookBackCamBackOffset=60.0<br>
??<br>

LookBackCamSideOffset=20.0<br>
??<br>

### Lean Speed

LeanSpeedThreshold=25.0<br>
??<br>

### Door Loudness

DoorOpenInstantLoudness=0.6<br>
??<br>

DoorOpenPartialLoudness=0.3<br>
??<br>

DoorCloseFastLoudness=0.3<br>
??<br>

DoorEnterLockerLoudness=0.2<br>
??<br>

DoorExitLockerLoudness=0.2<br>
??<br>

DoorRunThroughLoudness=1.0<br>
??<br>

### Player Loudness

WalkingLoudness=0.3<br>
??<br>

CrouchLoudness=0.1<br>
??<br>

RunningLoudness=1.0<br>
??<br>

WalkingWaterLoudness=0.45<br>
??<br>

CrouchWaterLoudness=0.1<br>
??<br>

FallingHighLoudness=1.0<br>
??<br>

FallingMedLoudness=0.5<br>
??<br>

FallingLowLoudness=0.2<br>
??<br>

HobblingWalkLoudness=0.4<br>
??<br>

HobblingRunLoudness=1.0<br>
??<br>

#### Landing Loudness

LandingBigLoudness=0.8<br>
??<br>

LandingSmallLoudness=0.3<br>
??<br>

LandingBigWaterLoudness=1.0<br>
??<br>

LandingSmallWaterLoudness=0.5<br>
??<br>

### Moving Noise

MovingNoiseStartTime=1.75<br>
??<br>

MovingNoiseClearTime=1.0<br>
??<br>

## [OLGame.OLPlayerController]

DefaultSoundOcclusion=0.65<br>
??<br>

bEnableShadowOptimisation=true<br>
??<br>

bEnableLightOptimisation=true<br>
??<br>

ForceFeedbackManagerClassName="WinDrv.XnaForceFeedbackManager"<br>
??<br>

bEnableForceFeedbackManager=true<br>
??<br>

FirstSoldierFindableCheckpoint=Sewer_start<br>
??<br>

FirstSurgeonFindableCheckpoint=Male_surgeon<br>
??<br>

### Struggle

StruggleInputThresholdForWin=50000.0<br>
??<br>

StruggleShakesThresholdForWin=2.0<br>
??<br>

StruggleInputThresholdForWinNoFail=15000.0<br>
??<br>

StruggleShakesThresholdForWinNoFail=5.0<br>
??<br>

### Number Of Batteries

DefaultNumBatteries=2<br>
??<br>

NrmMaxNumBatteries=10<br>
??<br>

HardMaxNumBatteries=5<br>
??<br>

NightmareMaxNumBatteries=2<br>
??<br>

### Chase Music Delay

AIChaseMusicTimeDelay=0.5f<br>
??<br>

## [OLGame.OLHeroCamera]

CameraBoneName=Hero-Camera<br>
??<br>

ViewLimitsSoftZone=20.0<br>
??<br>

SoftZoneStiffness=1000.0<br>
??<br>

## [Engine.WorldInfo]

DefaultGravityZ=-850.0<br>
??<br>

## [OLGame.OLVoiceManager]

??<br>

## [OLGame.OLSoundEnvironmentManager]

bEnableSoundVirtualization=true<br>
??<br>

OcclusionApproachCoeff=0.99<br>
??<br>

ObstructionApproachCoeff=0.95<br>
??<br>

MaxPathingDist=1200.0; max search above the direct distance<br>
??<br>

FreePathingDist=500.0; we give some distance free of occlusion after the direct dist<br>
??<br>

ObstructionRatioInSameVolume=0.5<br>
??<br>

LockerOcclusion=0.2<br>
??<br>

LockerReverbEnvironment=Locker_Space<br>
??<br>

## [OLGame.OLDmgType]

SpeedPenaltyPctOnDamage=0.75<br>
??<br>

SpeedPenaltyDuration=0.75<br>
??<br>

## [OLGame.OLDmgType_GenericHit]

SpeedPenaltyPctOnDamage=0.75<br>
??<br>

SpeedPenaltyDuration=0.75<br>
??<br>

## [OLGame.OLDmgType_Fell]

SpeedPenaltyPctOnDamage=0.75<br>
??<br>

SpeedPenaltyDuration=1.5<br>
??<br>

## [OLGame.OLDmgType_SoldierPunch]

SpeedPenaltyPctOnDamage=0.75<br>
??<br>

SpeedPenaltyDuration=0.75<br>
??<br>

## [OLGame.OLDmgType_NanoFog]

SpeedPenaltyPctOnDamage=0.0<br>
??<br>

SpeedPenaltyDuration=0.5<br>
??<br>

## [OLGame.OLDmgType_Fire]

SpeedPenaltyPctOnDamage=0.5<br>
??<br>

SpeedPenaltyDuration=0.5<br>
??<br>
