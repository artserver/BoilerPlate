# BoilerPlate
PaperMC 플러그인 개발을 쉽게 해주는 보일러플레이트

### 주의!
주의사항을 입력합니다\

## 사용 방법
```java
//이렇게 하면 자바 문법으로 하이라이트가 들어갈겁니다.
```

## 예제
```java
package kr.artserver.boilerplatetest;

import org.bukkit.event.EventHandler;
import org.bukkit.event.Listener;
import org.bukkit.event.player.PlayerJoinEvent;
import org.bukkit.plugin.java.JavaPlugin;

public final class BoilerPlateTest extends JavaPlugin implements Listener {

    public ConfigSession config;

    @Override
    public void onEnable() {
        
    }

    @EventHandler
    public void onJoin(PlayerJoinEvent event){

    }

    @Override
    public void onDisable() {
        
    }
}
```

## Jar 다운로드
```out/artifacts/BoilerPlate/BoilerPlate.jar```

## 추가할 기능
- 