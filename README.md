# 📦 ISEL GT Maven Repository

This is a GitHub Pages based custom Maven repository for distributing private or internal Java/Kotlin artifacts.

Hosted at:  
👉 [https://isel-gt.github.io/ISEL-GT-MAVEN/](https://isel-gt.github.io/ISEL-GT-MAVEN/)

---

## 🧪 Available Artifacts

| Group ID     | Artifact ID              | Version          | Type   |
|--------------|--------------------------|------------------|--------|
| `isel.leic`  | usbPort                  | `1.0.0`          | `.jar` |
| `isel.leic`  | rouletteGame             | `1.0.0`          | `.jar` |
| `robot.ev3`  | RobotLegoEV3             | `1.0.0`          | `.jar` |
| `javax`      | bluecove-2.1.1-SNAPSHOT  | `1.0.0`          | `.jar` |
---

### Maven Repository Reference

```xml
<repositories>
  <repository>
    <id>github-repo</id>
    <url>https://isel-gt.github.io/ISEL-GT-MAVEN/</url>
    <layout>default</layout>
  </repository>
</repositories>
```

### USB Port
```xml
<dependency>
  <groupId>isel.leic</groupId>
  <artifactId>usbPort</artifactId>
  <version>1.0.0</version>
</dependency>
```

### rouletteGame
```xml
<dependency>
  <groupId>isel.leic</groupId>
  <artifactId>rouletteGame</artifactId>
  <version>1.0.0</version>
</dependency>
```

### RobotLegoEV3
```xml
<dependency>
  <groupId>robot.ev3</groupId>
  <artifactId>RobotLegoEV3</artifactId>
  <version>1.0.0</version>
</dependency>
```

### bluecove
```
<dependency>
    <groupId>javax</groupId>
    <artifactId>bluecove</artifactId>
    <version>2.1.1-SNAPSHOT</version>
</dependency>
```


