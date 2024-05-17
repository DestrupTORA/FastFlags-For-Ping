# FastFlags-For-Better-Ping v1
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
