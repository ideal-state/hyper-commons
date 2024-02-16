# Hyper Commons

![Gradle](https://img.shields.io/badge/Gradle-v8%2E5-g?logo=gradle&style=flat-square)
![Zulu JDK](https://img.shields.io/badge/Zulu%20JDK-8-blue?style=flat-square)
![GitHub License](https://img.shields.io/github/license/ideal-state/hyper-commons?style=flat-square)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/ideal-state/hyper-commons?style=flat-square&logo=github)
![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/ideal-state/hyper-commons/release.yml?style=flat-square)
![GitHub Release](https://img.shields.io/github/v/release/ideal-state/hyper-commons?style=flat-square)
![Discord](https://img.shields.io/discord/1191122625389396098?style=flat-square&logo=discord)

------------------------------------------------------

> 提供一些基础的公共工具类

### 在 Maven 项目中使用

```xml
<dependency>
    <groupId>team.idealstate.hyper</groupId>
    <artifactId>hyper-commons-base</artifactId>
    <version>${version}</version>
</dependency>
```

### 在 Gradle 项目中使用

```groovy
dependencies {
    implementation "team.idealstate.hyper:hyper-commons-base:${version}"
}
```

```kotlin
dependencies {
    implementation("team.idealstate.hyper:hyper-commons-base:${version}")
}
```

### 在哪下载 ?

> 前往 [releases](https://github.com/ideal-state/hyper-commons/releases) 页

### 如何构建

```shell
git clone https://github.com/ideal-state/hyper-commons.git
```

```shell
cd ./hyper-commons
```

```shell
./gradlew.bat :clean :hyper-commons-base:jar
```

或

```shell
./gradlew :clean :hyper-commons-base:jar
```

> 等待构建完成，在 ./build/libs 下会生成 .jar 工件

### 关于开发配置

> [`local.properties`](./local.properties)

### 怎样成为贡献者 ?

在贡献之前，你需要了解相应的规范。[前往查看](https://github.com/ideal-state)

