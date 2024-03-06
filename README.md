Join our [discord](https://discord.gg/stozu) or submit an issue (or a pull request fixing it!)

[![Stozu](https://i.imgur.com/P1m0hoi.png)](https://stozu.net/)

### Note: The incompatibilities listed are for the mods featured in this list only, and does not take into consideration any mods not featured here.

## Fabric API
Despite being a toolkit for modding functionality, Fabric API actually contains some optimizations and bugfixes. Even if you aren't planning to run any content mods, I recommend that you still use it. [Download it from GitHub](https://github.com/FabricMC/fabric).

## Rendering
| <div style="color:white">Name</div> | <div style="width:290px; color:white">Description</div> | <div style=" color:white">Developer</div> | <div style="color:white">Incompatibilities</div> | <div style="width:150px; color:white">GitHub Link</div> |
| --- | --- | --- | --- | --- |
| Sodium | A rendering engine replacement designed to boost your framerate and reduce random stuttering. | CaffeineMC | Canvas | [<div style="color:white; text-decoration: underline">INSTALL</div>](https://github.com/jellysquid3/sodium-fabric) |
| Canvas | A shader-oriented rendering engine replacement. Focuses on functionality over raw performance. | Grondag | Sodium | [<div style="color:white; text-decoration: underline">INSTALL</div>](https://github.com/grondag/canvas) |
| Cull Particles | This mod adds culling to particles. Redundant if using Sodium, as Sodium has its own implementation, but this should be used by Canvas or Vanilla users. | Tfarcenim | Sodium (redundant) | [<div style="color:white; text-decoration: underline">INSTALL</div>](https://github.com/Tfarcenim/CullParticlesFabric) |
| Enhanced Block Entities | Replaces most block entities with baked models. Also allows more customization using JSON. Depends on FRAPI and thus requires [Indium](https://github.com/comp500/Indium) if using Sodium. | FoundationGames | Unknown | [<div style="color:white; text-decoration: underline">INSTALL</div>](https://github.com/FoundationGames/EnhancedBlockEntities) |

## Server
| <div style="color:white">Name</div> | <div style="width:290px; color:white">Description</div> | <div style="color:white">Developer</div> | <div style="color:white">Incompatibilities | <div style="width:200px; color:white">GitHub Link</div> |
| --- | --- | --- | --- | --- |
| Lithium | A mod that optimizes some aspects of Minecraft's server, while maintaining behavior identical to vanilla. Works in singleplayer. | CaffeineMC | Unknown | [<div style="color:white; text-decoration: underline">INSTALL</div>](https://github.com/jellysquid3/lithium-fabric) |

## Lighting
| <div style="color:white">Name | <div style="width:290px; color:white">Description</div> | <div style="color:white">Developer | <div style="color:white">Incompatibilities | <div style="width:200px; color:white">GitHub Link |
| --- | --- | --- | --- | --- |
| Phosphor | A smaller mod that makes Minecraft's bulky and slow lighting engine much faster. | Jellysquid | Starlight | [<div style="color:white; text-decoration: underline">INSTALL</div>](https://github.com/jellysquid3/phosphor-fabric) |
| Starlight | **WARNING: Uses non-free Mojang mappings!**<br>An experimental mod that can speed up lighting calculations by 26x compared to Phosphor (according to the developer). | Spottedleaf | Phosphor | [<div style="color:white; text-decoration: underline">INSTALL</div>](https://github.com/Spottedleaf/Starlight) |

## Memory
| <div style="color:white">Name</div> | <div style="width:290px; color:white">Description</div> | <div style="color:white">Developer</div> | <div style="color:white">Incompatibilities</div> | <div style="width:200px; color:white">GitHub Link</div> |
| --- | --- | --- | --- | --- |
| Hydrogen | Reduces RAM usage of Minecraft by compacting models and other misc. data. More effective with more content mods. | CaffeineMC | DashLoader | [<div style="color:white; text-decoration: underline">INSTALL</div>](https://github.com/jellysquid3/hydrogen-fabric) |
| FerriteCore | **WARNING: Uses non-free MCP mappings!**<br>A mod similar to Hydrogen that employs more memory-efficient logic. Works very well with Hydrogen. | malte0811 | Unknown | [<div style="color:white; text-decoration: underline">INSTALL</div>](https://github.com/malte0811/FerriteCore) |

## Network
| <div style="color:white">Name</div> | <div style="width:290px; color:white">Description</div> | <div style="color:white">Developer</div> | <div style="color:white">Incompatibilities</div> | <div style="width:230px;color:white">GitHub Link</div> |
| --- | --- | --- | --- | --- |
| Krypton | Optimizations for Minecraft's general networking. If you're at a bandwidth bottleneck then this can help. | astei | Unknown | [<div style="color:white; text-decoration: underline">INSTALL</div>](https://github.com/astei/krypton) |

## Start-up
| <div style="color:white">Name</div> | <div style="width:290px; color:white">Description</div> | <div style="color:white">Developer</div> | <div style="color:white">Incompatibilitie</div> | <div style="width:200px; color:white">GitHub Link</div> |
| --- | --- | --- | --- | --- |
| LazyDFU | Prevents DFU from being built until it is needed. | astei | Unknown | [<div style="color:white; text-decoration: underline">INSTALL</div>](https://github.com/astei/lazydfu) |
| DashLoader | Builds caches to load the game much faster. Works with LazyDFU but is extremely invasive and incompatible with many mods. | alphaqu | Hydrogen | [<div style="color:white; text-decoration: underline">INSTALL</div>](https://github.com/alphaqu/DashLoader) |

## Extras
### These mods are extras that do not improve game performance.
| <div style="width:150px; color:white">Name</div> | <div style="width:290px; color:white">Description</div> | <div style="color:white">Developer</div> | <div style="color:white">Incompatibilities</div> | <div style="width:100px; color:white">GitHub Link</div> |
| --- | --- | --- | --- | --- |
| Sodium Extra Fabric (Requires Sodium) | Adds more graphical settings to Sodium, similar to OptiFine's. | FlashyReese | Unknown | [<div style="color:white; text-decoration: underline">INSTALL</div>](https://github.com/FlashyReese/sodium-extra-fabric/) |
| Dynamic FPS | Slows down Minecraft's rendering when Minecraft is minimized or in the background to improve performance in other applications. | juliand665 | Unknown | [<div style="color:white; text-decoration: underline">INSTALL</div>](https://github.com/juliand665/Dynamic-FPS) |
