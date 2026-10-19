# 操作
## シーンの作成
* File → New Scene
    * 「Basic(URP)」　をおすすめ。
    * File → Build Profiles を押す。Add Open Scenesでシーンを追加する必要がある。

# シーンの切り替え
```csharp
SceneManager.LoadScene("RunningScene");
```

# 入力
```csharp
        if (Keyboard.current == null) return;
        if (Keyboard.current.spaceKey.isPressed) {
            
        }
```
