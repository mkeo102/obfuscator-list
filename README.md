# obfuscator-list
* [Ackerun](https://github.com/YumeGod/AckerunObfOpenSource) - FOSS. Light/Heavy obfuscator depanding on your cfg. Has some basic and simple features with nothing unknown in it.
* [Allatori](http://www.allatori.com/) - Commericial. Somewhat popular choice in industry.
* [Ambien](https://github.com/iiiiiiiris/Ambien) - FOSS. New obfuscator that is getting actively developed. Has some cool features. Can contain some bugs/issue.
* [Avaj](https://github.com/cg-dot/avaj) - FOSS. Has a nice way of generating decryption subroutines on string constants. Also has some CFG flattening which is always nice to see.
* [BisGuard](http://www.bisguard.com/) - Commercial. Relies entirely on class encryption (last time I checked, at least) so protection has quite a bit of room for improvement.
* [Black](https://github.com/CodingGay/BlackObfuscator) - FOSS. Black Obfuscator is an obfuscator for Android APK DexFile, it can help developer to protect source code by control flow flattening, and make it difficult to analyze the actual program control flow.
* [Bozar](https://github.com/vimasig/Bozar) - Points for FOSS. Has some cheap tricks that I have seen being used in the Minecraft community. Can be deobfuscated using [Narumii](https://github.com/narumii/Deobfuscator).
* [Branchlock](https://branchlock.net/) - Commercial. Obfuscator mainly used for its AntiDebug features. Shows up a bit in the Minecraft community. Outdated and deobfable.
* [Caesium](https://github.com/sim0n/Caesium) - FOSS. Has a transformer that implements a well-known HTML injection into any Java reverse-engineering tool that parses HTML tags. Shows alot in Minecraft community. Can be deobfuscated using [Narumii](https://github.com/narumii/Deobfuscator)/[JavaDeobfuscator](https://github.com/java-deobfuscator/deobfuscator). 
* [CheatBreaker](https://github.com/CheatBreaker/Obf) - FOSS. Decent obfuscation that looks similar to Caesiums (Prob. Skidded). Obfuscation is overall decent. Shows in Minecraft community. Can be deobfuscated using [JavaDeobfuscator](https://github.com/java-deobfuscator/deobfuscator)
* [ClassGuard](https://zenofx.com/classguard/) - Commercial. Relies mostly on class encryption with hardcoded AES keys in native libs. Pretty easy IDA/Binary Ninja/Ghidra exercise if you want to flex on your blog on something. Can be deobfuscated using [JavaDeobfuscator](https://github.com/java-deobfuscator/deobfuscator).
* [DashO](https://www.preemptive.com/products/dasho/overview) - Commercial. Shows up a bit in industry and has some interesting ideas (albeit probably outdated) in flow obfuscation. Can be deobfuscated using [JavaDeobfuscator](https://github.com/java-deobfuscator/deobfuscator).
* [DexGuard](https://www.guardsquare.com/dexguard) - Commercial. Mainly used for obfuscating Android apps. Never saw any samples. Can be deobfuscated using [JavaDeobfuscator](https://github.com/java-deobfuscator/deobfuscator).
* [Eskid](https://github.com/PlutoSolutions/EskidRewrite) - Commercial. Decent obfuscator based on [HsGuard](https://github.com/3000IQPlay/HsGuard-Obfuscator)/[Scuti](https://github.com/netindev/scuti/tree/master). Shows alot in Minecraft community. Could be possibly deobfuscated using [Ackeruns](https://github.com/AckerRun1337) Eskid deobfuscator trasnformer. Got cracked by [PlutoSolution](https://github.com/PlutoSolutions).
* [Grunt](https://github.com/SpartanB312/Grunt) - Obfuscator written in Kotlin. Can be used as main obfuscator all tho there are missing some features such as Crasher or Flow obfuscation. Overall has very good features that are compatible with each other. Mainly known in Minecraft Comunity for it's mixin support renamer, native candidates and compatibilty with obfuscating Forge mods/Plugins. Contains some features that can be found in paid obfuscators.
* [HsGuard](https://github.com/3000IQPlay/HsGuard-Obfuscator) - FOSS. Obfuscator developed by Chinese ppl. Bad skid of Scuti with minimal additions. Can be deobfuscated using [Narumii](https://github.com/narumii/Deobfuscator).
* [JNIC](https://jnic.dev) - Commercial. One of not so many Java Native Interface Compilers that offers String Encryption, Control Flow with Flattening and their famous Native compiler. This obfuscator is mainly used for the Native compiling and does a really good job doing so. You can often see JNIC in Intent/1.8 cheat clients. Be aware that the Native obfuscation could cause lag or slow down the processes made in the application. If you would decide to use JNIC for obfuscation then make sure to not use it on it's own and instead use something with it.
* [JBCO](http://www.sable.mcgill.ca/JBCO/) - FOSS. Some interesting flow obfuscation techniques that still work in modern Java. Based on the [Soot](https://github.com/soot-oss/soot) library which is also something worthwhile checking out.
* [JObf](https://github.com/superblaubeere27/obfuscator) - FOSS. Pretty outdated. Some of the transformations done show up in the Minecraft community. Can be easily deobfuscated with no effort using [Narumii](https://github.com/narumii/Deobfuscator)/[JavaDeobfuscator](https://github.com/java-deobfuscator/deobfuscator).
* [JObfuscator](https://www.pelock.com/products/jobfuscator) - Commericial. Never seen this used before so I cannot really give any comments.
* [Mosey](https://github.com/Hippo/Mosey) - FOSS. Outdated obfuscator mainly coded in Scala. Overall is no recommended for use since the obfuscation is very light and is easy to deobfuscate. Mainly used for 2+. layer obfuscation. Can be deobfuscated using [Narumii](https://github.com/narumii/Deobfuscator).
* [MyJ2C](https://github.com/MyJ2c/Open-MyJ2c) - FOSS. Obfuscator made by chinese ppl that managed to skid some of Allatoris parts such as String Enc. and some other things into their project. Overall only recommend using it when u have nothing else to use. Can be partically deonfuscated using Allatori deobfuscator. Has a interesting feature called "Confusing CallSites".
* [NeonObf](https://github.com/MoofMonkey/NeonObf) - FOSS.  Made up of the easier to defeat obfuscation techniques.  NeonObf is also the name inspiration for Radon.
* [Obzcure](https://obzcu.re/) - [Discord](https://discordapp.com/invite/fUCPxq8) (Dead) - Commericial. Web-based obfuscation service with some inspiration taken from Radon and [SkidSuite2](https://github.com/GenericException/SkidSuite/tree/master/archive/skidsuite-2). Used to go by the name "SpigotProtect" so you might see some Spigot plugins using the obfuscation from this product if you look around hard enough. Can be deobfuscated using [JavaDeobfuscator](https://github.com/java-deobfuscator/deobfuscator). 
* [Paramorphism](https://paramorphism.dev/) - [Discord](https://discordapp.com/invite/k9DPvEy) (Dead) - Commerical. Was one of the most unusual and unique obfuscators at the time it was an active project in that relied a lot more on the JVM's unusual way of loading JAR archives including zip entries with duplicated names and the [fake directory trick](https://github.com/x4e/fakedirectory). Used to be more commonly used before people started ripping ideas from Paramorphism. Can be deobfuscated using [JavaDeobfuscator](https://github.com/java-deobfuscator/deobfuscator).
* [qProtect](https://mdma.dev/) - Commericial. Big skid. Got cracked many times. Implements a lot of the more common obfuscation techiques into a single tool. Shows up a bit in the Minecraft community.
* [Radon](https://github.com/ItzSomebody/radon) - FOSS. Abandoned experimentational obfuscator. Easy to deobfuscate using [JavaDeobfuscator](https://github.com/java-deobfuscator/deobfuscator).
* [Sandmark](http://sandmark.cs.arizona.edu) - FOSS. Really old obfuscator research project led by Christian Collberg at the University of Arizona. Some interesting ideas in watermarking are here and some of the flow obfuscation ideas are good.
* [Scuti](https://github.com/netindev/scuti) - FOSS. Outdated obfuscator. Only recomended using as 2+. layer obfuscator or if u have no other options to use. Can be deobfuscated using [Narumii](https://github.com/narumii/Deobfuscator).
* [Sentinel](https://cdn.discordapp.com/attachments/972906162641076317/972942077669310556/SentinelObf-1.0-SNAPSHOT-all-obf.jar) - [Discord](https://discord.gg/hHdkA2RuF6) - FOSS. Obfuscator mainly known in Minecraft community. Don`t have anything to say about this obfuscator.
* [Skidfusctor](https://github.com/skidfuscatordev/skidfuscator-java-obfuscator) - [Discord](https://discord.gg/srFPwUPFX3) - FOSS/Commericial. Skidfuscator is known obfuscator for its simplicity, ease of use, and effectiveness in protecting Java applications from reverse engineering and tampering. You can get free version having overall strong obfuscation. Paid (Enterprises) version has Native obfuscation with some other features. Has it's own [documentary website](https://skidfuscator.dev/docs/). Requires libraries (Doesn't have max depth). Shows alot in Minecraft community.
* [SkidSuite2](https://github.com/GenericException/SkidSuite/tree/master/archive/skidsuite-2) - FOSS. Some pretty basic obfuscation techniques, nothing too special.
* [Stringer](https://jfxstore.com/stringer/) - Commericial. Pretty infamous for its complicated AES-based encryption/decryption routines and price. Does not really offer a whole lot of protection, but sometimes does show up in industry.  
* [yGuard](https://www.yworks.com/products/yguard) - FOSS. Functionally equivalent to ProGuard as far as I can tell.
* [zProtect](https://github.com/JessSystemV/zProtect) - [Discord](https://discord.com/invite/dnGKGuwvGH) - Commercial. Stupid Binscure skid. Not recomended for use. SRC of it has been leaked and their obfuscation could be possibly deobfuscated using [darklols](https://github.com/darklol9) zProtect deobfuscator or using Binscure deobfuscator to semi deobfuscate it.
* [ZKM (Zelix Klass Master)](https://github.com/JessSystemV/zProtect) - Commericial. Zelix KlassMaster Obfuscator is known for its robust obfuscation techniques and strong obfuscation capabilities and is used by many companies to protect their Java applications from reverse engineering and tampering.
* [Zortfuscator (Discord)](https://discord.gg/A3wsGKWGSc) - Commericial. Dead, not so known obfuscator. Can tell that it has good obfuscation techniques from the look at the samples they have on their discord server.
