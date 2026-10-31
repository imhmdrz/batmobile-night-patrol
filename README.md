# Batmobile Night Patrol

A Unity driving simulation with wheel physics, stealth and alert modes, and a dynamic Bat-Signal.

[راهنمای فارسی](README.fa.md)

## Highlights

- WheelCollider-based driving, steering, and boost.
- Three vehicle modes: Normal, Stealth, and Alert.
- Mode-dependent lighting and an alert siren.
- A toggleable, animated Bat-Signal.

**Stack:** Unity 6 · C# · WheelCollider

## Run in Unity

1. Clone this repository and add its folder to Unity Hub.
2. Install **Unity 6000.2.10f1**, the version recorded in `ProjectSettings/ProjectVersion.txt`.
3. Open `Assets/Scenes/SampleScene.unity`.
4. Press **Play** and focus the Game view.

## Controls

| Action | Key |
| --- | --- |
| Accelerate / reverse | W / S or arrow keys |
| Steer | A / D or arrow keys |
| Boost | Shift |
| Toggle Stealth mode | C |
| Toggle Alert mode | Space |
| Toggle Bat-Signal | B |

## Code map

| Path | Responsibility |
| --- | --- |
| `Assets/Scripts/CarController.cs` | Driving, vehicle modes, lighting, audio, and Bat-Signal |
| `Assets/Scripts/CameraFollow.cs` | Camera following |
| `Assets/Scenes/SampleScene.unity` | Playable scene |

The original Persian project explanation is preserved in [README.fa.md](README.fa.md).
