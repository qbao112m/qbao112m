Got this error after new update. How would this be fixed?

<html>RuntimeException: Error parsing or using Mixin config fabric-block-view-api-v2.mixins.json for mod<br>fabric-block-view-api-v2</html>
<html>at net.fabricmc.loader.impl.launch.FabricMixinBootstrap.init(FabricMixinBootstrap.java:96)<br>at net.fabricmc.loader.impl.launch.knot.Knot.init(Knot.java:151)<br>at net.fabricmc.loader.impl.launch.knot.Knot.launch(Knot.java:68)<br>at net.fabricmc.loader.impl.launch.knot.KnotClient.main(KnotClient.java:23)</html>
MixinInitialisationError: Error initialising mixin config fabric-block-view-api-v2.mixins.json
<html>at org.spongepowered.asm.mixin.transformer.Config.create(Config.java:168)<br>at org.spongepowered.asm.mixin.Mixins.createConfiguration(Mixins.java:121)<br>at org.spongepowered.asm.mixin.Mixins.addConfiguration(Mixins.java:108)<br>at org.spongepowered.asm.mixin.Mixins.addConfiguration(Mixins.java:98)<br>at net.fabricmc.loader.impl.launch.FabricMixinBootstrap.init(FabricMixinBootstrap.java:94)<br>... 3 more</html>
<html>IllegalArgumentException: The requested compatibility level JAVA_21 could not be set. Level is not supported by the<br>active JRE or ASM version (Java 17.0, ASM 9.7.1 (ASM10_EXPERIMENTAL))</html>
<html>at org.spongepowered.asm.mixin.MixinEnvironment.setCompatibilityLevel(MixinEnvironment.java:1822)<br>at org.spongepowered.asm.mixin.transformer.MixinConfig.initCompatibilityLevel(MixinConfig.java:606)<br>at org.spongepowered.asm.mixin.transformer.MixinConfig.postInit(MixinConfig.java:551)<br>at org.spongepowered.asm.mixin.transformer.MixinConfig.onLoad(MixinConfig.java:479)<br>at org.spongepowered.asm.mixin.transformer.MixinConfig.create(MixinConfig.java:1398)<br>at org.spongepowered.asm.mixin.transformer.Config.create(Config.java:163)<br>... 7 more</html>
