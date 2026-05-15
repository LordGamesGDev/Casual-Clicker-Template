# Casual Clicker Template - Quick Preview

**Full idle/clicker framework for Unity**

> Full documentation is included inside the asset as a PDF.  
> Buy now on Unity Asset Store: <https://assetstore.unity.com/preview/338962/1137608>

---

## Quick Start

1. Add `GameBootstrapper.cs` and `EventSystemBootstrap.cs` to your scene.
2. Assign prefabs in the Inspector:
   - `AudioManager`
   - `EnemyManager`
   - `CanvasGame`
3. Make sure the scene has a camera tagged `MainCamera`.
4. Press **Play**.

## Core Features

| Feature | Ready |
| --- | --- |
| Click and passive income system | Yes |
| Player level and EXP progression | Yes |
| Upgrade panel with editable upgrade entries | Yes |
| Enemy and boss pool system | Yes |
| Save/load with PlayerPrefs and JSON | Yes |
| Audio manager for music and SFX | Yes |
| Coroutine-based animations | Yes |
| TextMeshPro UI | Yes |
| Custom editor tools | Yes |
| New Input System and legacy input support | Yes |

## API Snippet

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

## Editor Tools

- `Project Setup` - checks TextMeshPro package setup and TMP Essentials.
- `UpgradePanelManagerEditor` - add, remove, select, reorder and update upgrades.
- `EnemyManagerEditor` - edit enemy pools, boss pools, HP, rewards and sprites.
- `UpgradeEditor` - update UI text for individual upgrades.

## Tech Stack

- Unity 2022.3 LTS or newer
- Built-in Render Pipeline and URP compatible assets
- C# gameplay architecture
- TextMeshPro
- Unity built-in coroutine-based animation logic
- No required third-party runtime dependencies

---

Made by Lord Games  
Support: lordgames.contact@gmail.com

**Preview notice:** This is a public preview. Full source code, documentation and editor tools are available to purchasers through the Unity Asset Store.
