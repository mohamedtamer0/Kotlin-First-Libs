# Kotlin-First-Libs

> Add in build.gradle.kts

```gradle
repositories {
    mavenCentral()
    maven("https://jitpack.io")
}
```


```gradle
dependencies {
    implementation("com.github.mohamedtamer0:Kotlin-Libs-Course:0.1")
}
```

> In Main Kotlin

```Kotlin
fun main(args: Array<String>) {
    println(Calculations().sum(5,20))
}
```
