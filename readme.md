## ⌛ Project Essentials: CooldownAPI

[![](https://jitpack.io/v/projectessentials/ProjectEssentials-Cooldown.svg)](https://jitpack.io/#projectessentials/ProjectEssentials-Cooldown)
![GitHub](https://img.shields.io/github/license/ProjectEssentials/ProjectEssentials-Cooldown)

> ## Cooldown API for Forge mod commands.

#### ❗ Compatibility with forge `28.0.X` version.

## 🧐 Install using Gradle (for developers):
> ##### If your project uses Gradle as Build Tool, then use the code below to add dependencies:

```groovy
repositories {
    maven { url("https://jitpack.io") }
}

dependencies {
    compile(
        group: "com.github.projectessentials",
        name: "ProjectEssentials-Cooldown",
        version: "v1.14.4-1.0.1.0"
    )
}
```

## 🤔 Install using Maven (for developers):
> ##### If your project uses Maven as Build Tool, then use the code below to add dependencies:

```xml
<repositories>
    <repository>
        <id>jitpack.io</id>
        <url>https://jitpack.io</url>
    </repository>
</repositories>

<dependency>
	<groupId>com.github.projectessentials</groupId>
	<artifactId>ProjectEssentials-Cooldown</artifactId>
	<version>v1.14.4-1.0.1.0</version>
</dependency>
```

## 🎮 Installation instruction (for playing):
> ##### Just move Project Essentials Cooldown-1.14.4-1.X.X.X.jar to mods directory:

> ##### Important note: don't forget install mod dependencies!
  - core: https://github.com/ProjectEssentials/ProjectEssentials-Core/releases
  - permissions: https://github.com/ProjectEssentials/ProjectEssentials-Permissions/releases

```
.
├── assets
├── config
├── libraries
├── mods (that's how it should be)
│   ├── Project Essentials Core-MOD-1.14.4-1.X.X.X.jar.
│   ├── Project Essentials Permissions-1.14.4-1.X.X.X.jar.
│   └── Project Essentials Cooldown-1.14.4-1.X.X.X.jar.
└── ...
```

```
Additional information:
    - kotlin-std lib version: 1.3.50
    - kotlinx serialization version: 0.12.0
    - target jvm version: 1.8
```

### After you got the dependencies and the library itself:

# [getting started with read the documentation](./documentation/in-using.md)

### **Note:** this library is written in kotlin, but in java you can work with this API too, but there may be some not beautiful moments. One of these points is that you will see all the properties and fields with internal modifiers (in my library).

> ## Made with 💕 by [MairwunNx](https://mairwunnx.github.io/)
