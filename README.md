# 操作
* Fキー：オブジェクトにフォーカスする
## シーンの作成
* File → New Scene
    * 「Basic(URP)」　をおすすめ。
    * File → Build Profiles を押す。Add Open Scenesでシーンを追加する必要がある。
## ViewOptions（右から3つ目）
* 2D　-　表示を2D/3D切り替えられる

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

# 文字（TextMeshPro）
## 日本語対応
* デフォルトでは日本語に対応することができないため、Window →　Font Asset Creator　を開く。事前にフォントファイルをAssetsに入れておく
* Charactor Set ： Unicode Range（Hex）
      * Character Sequence（Hex）に、3000-303F,3040-309F,30A0-30FF,31F0-31FF,FF00-FFEF,4E00-9FFF　と入れる
* Atlas Resolition：8192 、8192（他のサイズでもできるが、大きくしたときにボケるため、一番大きい8192を指定する）
* 設定が完了したら、Save as　→　保存（.assetとして保存される）。　そうすることで、Font Assetからカスタムフォントを選べる

# ライト

# オブジェクト
## 2D
* Triangle
* Square
* Capsule
* Circle
* Video Player

## 3D
* Cube：3Dの立体物
* Sphere：3Dの球
* Capsule：3Dのカプセル
* Cylinder：3Dの円柱
* Plane：3Dの厚みがない板ポリゴン
* Quad：3Dの深みがない板ポリゴン
* TextMeshPro：文字

# カメラ

# 当たり判定（コライダー）

# サウンド

# ビルド

# その他
## ログ
* Debug.Log
* Debug.LogError
* Debug.LogWarrning
