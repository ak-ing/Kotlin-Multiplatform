## Start

https://www.jetbrains.com/help/kotlin-multiplatform-dev/multiplatform-getting-started.html

## Bug resolution

[Kotlin Multiplatform 依赖 kotlinx-datetime 库，任务“：kotlinStoreYarnLock”执行失败](https://juejin.cn/post/7390340749579223092)


[KotlinMultiplatform打包windows msi报错: External tool execution failed](https://juejin.cn/post/7393293636686676004)


### This is a Kotlin Multiplatform project targeting Android, iOS, Web, Desktop.

`/composeApp` is for code that will be shared across your Compose Multiplatform applications.
It contains several subfolders:

- `commonMain` is for code that’s common for all targets.
- Other folders are for Kotlin code that will be compiled for only the platform indicated in the folder name.
  For example, if you want to use Apple’s CoreCrypto for the iOS part of your Kotlin app,
  `iosMain` would be the right folder for such calls.

`/iosApp` contains iOS applications. Even if you’re sharing your UI with Compose Multiplatform,
you need this entry point for your iOS app. This is also where you should add SwiftUI code for your project.

Learn more about [Kotlin Multiplatform](https://www.jetbrains.com/help/kotlin-multiplatform-dev/get-started.html),
[Compose Multiplatform](https://github.com/JetBrains/compose-multiplatform/#compose-multiplatform),
[Kotlin/Wasm](https://kotl.in/wasm/)…