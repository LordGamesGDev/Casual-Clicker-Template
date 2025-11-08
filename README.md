# 🎮 Casual Clicker Template — **Quick Preview**  
**Full Idle/Clicker Framework for Unity**

> **Full documentation (PDF + HTML) is included inside the asset**  
> Buy now on Unity Asset Store → [**$24.5 Launch Sale!**](https://assetstore.unity.com/preview/338962/1137608)

---
## ☄️ Quick Start (2 Minutes)

1. Add `GameBootstrapper.cs` + `EventSystemBootstrap.cs` to your scene  
2. Assign prefabs in Inspector:  
   → AudioManager, EnemyManager, GameCanvas  
3. Press **Play** → Game runs!

## 🪄 Core Features
| Feature | Ready |
|---------|--------|
| ✅ Click & Passive Income System | Yes |
| ✅ Player Level + EXP Progression | Yes |
| ✅ Upgrade Panel (Dynamic, Editable) | Yes |
| ✅ Enemy + Boss Pool System | Yes |
| ✅ Save/Load (PlayerPrefs + JSON) | Yes |
| ✅ Audio Manager (Music + SFX) | Yes |
| ✅ DOTween Animations | Yes |
| ✅ TextMeshPro UI | Yes |
| ✅ Custom Editor Tools | Yes |
| ✅ Input System + Legacy Support | Yes |

## ☣️ API Snippet
```csharp
// Add gold
ClickManager.Instance.AddGold(100);

// Gain experience
ProgressionManager.Instance.GainExp(50);

// Play sound
AudioManager.Instance.PlaySFX("upgrade");

// Spawn next enemy
EnemyManager.Instance.SpawnNextEnemy();
```
## 🎨 Editor Tools (In-Inspector Magic)

* **UpgradePanelManagerEditor** → Add/Remove/Reorder upgrades visually
* **EnemyManagerEditor** → Edit HP, rewards, sprites — no code needed
* **Auto-sync UI** → Change cost/multiplier → UI updates instantly

## 🎸 Tech Stack
* Unity 2021–2025 / Unity 6
* URP & Built-in Render Pipeline
* SOLID Architecture
* Addressables Ready
* DOTween + TextMeshPro
* C# 10+ / .NET Standard

---

Made with ❤️ by Lord Games  
Support: lordgames.contact@gmail.com

‼️ *Warning: This is a preview only. Full source code, documentation, and editor tools are available only to purchasers via the Unity Asset Store.*
