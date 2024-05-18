<h1 align="center"><img src="https://github.com/DestrupTORA/RobloxPingReloader/assets/157624868/92fa1b1b-d5a9-4391-a063-e5aa85afabf2" alt="0eeeb19633422b1241f4306419a0f15f39d58de9" width="100">
  
  
  
##### FastFlags-For-Better-Ping v1
## How to use FastFlags without Bloxtrap:
###### You can also do Roblox Studio
1. **Navigate to your Roblox Installation directory. Typically found at `%localappdata%\Roblox\Versions\` for Windows or `C:\Program Files (x86)\Roblox\Versions`.**
2. **Identify the folder `version-xxxxxxxxxxxxxxxx` ~~containing `RobloxPlayerBeta.exe`~~ You can do this for Roblox Studio too.**
3. **Create a new folder named `ClientSettings`. Inside this folder, place the file `ClientAppSettings.json`.**
4. **Paste the JSON into `ClientAppSettings.json`. (You can utilize ChatGPT to format multiple JSONs for clarity if needed)**
5. **Save and your good to go!**
###### Do note that after roblox updates you have to paste in your fflags again.
# Optimize Ping Transport ( Makes ping spikes smaller )
```json
{
  "FFlagOptimizeNetwork": "True",
  "FFlagOptimizeNetworkRouting": "True",
  "FFlagOptimizeNetworkTransport": "True",
  "FFlagOptimizeServerTickRate": "True",
  "DFIntServerPhysicsUpdateRate": "60",
  "DFIntServerTickRate": "60",
  "DFIntMinimalNetworkPrediction": "0.1",
  "DFIntOptimizePingThreshold": "50",
  "DFIntNetworkPrediction": "120",
  "DFIntNetworkLatencyTolerance": "1",
  "FFlagDontCreatePingJob": true,
  "DFIntConnectionMTUSize": 900
  }
```
## Removes ping spikes or makes them a little smaller, also press ALT+ENTER to reduce input lag and ping
```json
{
"FFlagDebugSimIntegrationStabilityTesting": true,
"FFlagHandleAltEnterFullscreenManually":"False",
"FIntRakNetResendBufferArrayLength": "128",
"FFlagDebugDisableTelemetryEphemeralCounter": "True",
"FFlagDebugDisableTelemetryEphemeralStat": "True",
"FFlagDebugDisableTelemetryEventIngest": "True",
"FFlagDebugDisableTelemetryPoint": "True",
"FFlagDebugDisableTelemetryV2Counter": "True",
"FFlagDebugDisableTelemetryV2Event": "True",
"FFlagDebugDisableTelemetryV2Stat": "True",
"FIntDefaultMeshCacheSizeMB": 256,
"DFIntHttpCurlConnectionCacheSize": 134217728,
"DFFlagHttpCacheCleanBasedOnMemory": true,  
"DFFlagEnableHttpCacheForceRevalidate2": false,
"DFFlagQueueDataPingFromSendData": true,
"FIntMeshContentProviderForceCacheSize": 268435456,
"DFIntAnimatorTelemetryCollectionRate": 0,
"SimBodyPositionPDFix": "true",
"FFlagDebugCamVisualizer": true,
"DFIntLargePacketQueueSizeCutoffMB": "1000",
"DFIntMaxProcessPacketsJobScaling": "10000",
"DFIntMaxProcessPacketsStepsAccumulated": "0",
"DFIntMaxProcessPacketsStepsPerCyclic": "5000",
"DFIntMegaReplicatorNetworkQualityProcessorUnit": "10",
"FFlagFixGraphicsQuality": "True",
"DFIntBufferCompressionThreshold": "100",
"DFIntPerformanceControlFrameTimeMax": "1",
"DFIntPerformanceControlFrameTimeMaxUtility": "-1",
"FFlagPushFrameTimeToHarmony": "True",
"FFlagUISUseLastFrameTimeInUpdateInputSignal": "True",
"DFIntAnimatorThrottleMaxFramesToSkip": "1",
"DFIntNumFramesAllowedToBeAboveError": "1",
"DFIntVisibilityCheckRayCastLimitPerFrame": "10",
"DFIntNetworkSchemaCompressionRatio": "100",
}
```
just make light theme in roblox
