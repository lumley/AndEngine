# AndEngine

This is a fork from the original AndEngine project (GLES2-AnchorCenter) as of 27-07-2012 version. This fork's aim is to make a stable version (without new functionality) and document as far as I can manage to understand.

## Other forked parts of AndEngine
 * [`AndEngineMODPlayerExtension`][URI_AndEngineMODPlayerExtension_Forked]
 * [`AndEngineMultiplayerExtension`][URI_AndEngineMultiplayerExtension_Forked]
 * [`AndEngineMultiTouchExtension`][URI_AndEngineMultiTouchExtension_Forked]
 * [`AndEnginePhysicsBox2DExtension`][URI_AndEnginePhysicsBox2DExtension_Forked]
 * [`AndEngineRobotiumExtension`][URI_AndEngineRobotiumExtension_Forked]
 * [`AndEngineScriptingExtension`][URI_AndEngineScriptingExtension_Forked]
 * [`AndEngineSVGTextureRegionExtension`][URI_AndEngineSVGTextureRegionExtension_Forked]
 * [`AndEngineTexturePackerExtension`][URI_AndEngineTexturePackerExtension_Forked]
 * [`AndEngineTMXTiledMapExtension`][URI_AndEngineTMXTiledMapExtension_Forked]

Original readme:
## Building

### Eclipse
 * AndEngine has to be build with ADT-17 or higher!

### IntelliJ IDEA
 * AndEngine relies on ADT to auto-generate a "BuildConfig" class. IntelliJ IDEA (as of 11.1.1) has not fully integrated with ADT-17+. In order to build AndEngine with IntelliJ IDEA, you can simply add the following class yourself in the root package (org.andengine): 
  
```java
package org.andengine;

public final class BuildConfig { 
    public final static boolean DEBUG = true;
}
```


## Branches

 * GLES2: 'GLES2'
    * Active development. 
    * Support: [> 93% of all Android devices ([Apr. 2012](http://developer.android.com/resources/dashboard/platform-versions.html))
 * GLES1: 'master'
    * Not in active development.
    * Support: > 99.0% of all Android devices ([Apr. 2012](http://developer.android.com/resources/dashboard/platform-versions.html))

## Examples

 * [`AndEngineExamples`][URI_AndEngineExamples]
 * [`AndEngineRobotiumExtensionExample`][URI_AndEngineRobotiumExtensionExample]

## Tests
 * [`AndEngineTest`][URI_AndEngineTest]
 * [`AndEngineRobotiumExtensionExampleTest`][URI_AndEngineRobotiumExtensionExampleTest]

## Extensions

 * [`AndEngineAugmentedRealityExtension`][URI_AndEngineAugmentedRealityExtension]
 * [`AndEngineLiveWallpaperExtension`][URI_AndEngineLiveWallpaperExtension]
 * [`AndEngineMODPlayerExtension`][URI_AndEngineMODPlayerExtension]
 * [`AndEngineMultiplayerExtension`][URI_AndEngineMultiplayerExtension]
 * [`AndEngineMultiTouchExtension`][URI_AndEngineMultiTouchExtension] (Merged into the 'GLES2' branch.)
 * [`AndEnginePhysicsBox2DExtension`][URI_AndEnginePhysicsBox2DExtension]
 * [`AndEngineRobotiumExtension`][URI_AndEngineRobotiumExtension]
 * [`AndEngineScriptingExtension`][URI_AndEngineScriptingExtension]
 * [`AndEngineScriptingExtensionGenerator`][URI_AndEngineScriptingExtensionGenerator]
 * [`AndEngineSVGTextureRegionExtension`][URI_AndEngineSVGTextureRegionExtension]
 * [`AndEngineTexturePackerExtension`][URI_AndEngineTexturePackerExtension] (Merged into the 'GLES2-AnchorCenter' branch.)
 * [`AndEngineTMXTiledMapExtension`][URI_AndEngineTMXTiledMapExtension] (Merged into the 'GLES1' branch.)


[URI_AndEngineExamples]: https://github.com/nicolasgramlich/AndEngineExamples
[URI_AndEngineRobotiumExtensionExample]: https://github.com/nicolasgramlich/AndEngineRobotiumExtensionExample
[URI_AndEngineTest]: https://github.com/nicolasgramlich/AndEngineTest
[URI_AndEngineRobotiumExtensionExampleTest]: https://github.com/nicolasgramlich/AndEngineRobotiumExtensionExampleTest
[URI_AndEngineAugmentedRealityExtension]: https://github.com/nicolasgramlich/AndEngineAugmentedRealityExtension
[URI_AndEngineLiveWallpaperExtension]: https://github.com/nicolasgramlich/AndEngineLiveWallpaperExtension
[URI_AndEngineMODPlayerExtension]: https://github.com/nicolasgramlich/AndEngineMODPlayerExtension
[URI_AndEngineMultiplayerExtension]: https://github.com/nicolasgramlich/AndEngineMultiplayerExtension
[URI_AndEngineMultiTouchExtension]: https://github.com/nicolasgramlich/AndEngineMultiTouchExtension
[URI_AndEnginePhysicsBox2DExtension]: https://github.com/nicolasgramlich/AndEnginePhysicsBox2DExtension
[URI_AndEngineRobotiumExtension]: https://github.com/nicolasgramlich/AndEngineRobotiumExtension
[URI_AndEngineScriptingExtension]: https://github.com/nicolasgramlich/AndEngineScriptingExtension
[URI_AndEngineScriptingExtensionGenerator]: https://github.com/nicolasgramlich/AndEngineScriptingExtensionGenerator
[URI_AndEngineSVGTextureRegionExtension]: https://github.com/nicolasgramlich/AndEngineSVGTextureRegionExtension
[URI_AndEngineTexturePackerExtension]: https://github.com/nicolasgramlich/AndEngineTexturePackerExtension
[URI_AndEngineTMXTiledMapExtension]: https://github.com/nicolasgramlich/AndEngineTMXTiledMapExtension

[URI_AndEngineMODPlayerExtension_Forked]: https://github.com/lumley/AndEngineMODPlayerExtension
[URI_AndEngineMultiplayerExtension_Forked]: https://github.com/lumley/AndEngineMultiplayerExtension
[URI_AndEngineMultiTouchExtension_Forked]: https://github.com/lumley/AndEngineMultiTouchExtension
[URI_AndEnginePhysicsBox2DExtension_Forked]: https://github.com/lumley/AndEnginePhysicsBox2DExtension
[URI_AndEngineRobotiumExtension_Forked]: https://github.com/lumley/AndEngineRobotiumExtension
[URI_AndEngineScriptingExtension_Forked]: https://github.com/lumley/AndEngineScriptingExtension
[URI_AndEngineSVGTextureRegionExtension_Forked]: https://github.com/lumley/AndEngineSVGTextureRegionExtension
[URI_AndEngineTexturePackerExtension_Forked]: https://github.com/lumley/AndEngineTexturePackerExtension
[URI_AndEngineTMXTiledMapExtension_Forked]: https://github.com/lumley/AndEngineTMXTiledMapExtension