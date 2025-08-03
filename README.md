# CoreEngine

**CoreEngine** ist eine modulare und minimalistische Game-Engine für 2D- und 3D-Spiele. Ziel ist es, eine eigenständige Engine zu entwickeln, die moderne Rendering-Techniken, ein Entity-Component-System (ECS) und ein skalierbares Framework für eigene Spieleprojekte bietet.

> 📌 Hinweis: Dieses Repository ist **öffentlich einsehbar**, aber **nicht Open Source**.  
> Eine **Nutzung, Veränderung oder Weitergabe ist ausschließlich mit schriftlicher Genehmigung** des Eigentümers erlaubt.  
> Der Inhalt dieses README ist **nicht final** und wird regelmäßig erweitert.

---

## 🚀 Projektüberblick

| Komponente           | Beschreibung                                  |
|----------------------|-----------------------------------------------|
| **Rendering**         | OpenGL/Vulkan-basiertes Echtzeit-Rendering    |
| **ECS**              | Flexibles Entity-Component-System              |
| **2D/3D Unterstützung** | Aufbauend auf Vektoren, Meshes und Texturen  |
| **Scene-Graph**      | Hierarchiebasierter Aufbau von Spielobjekten  |
| **Input-System**     | Plattformunabhängige Maus/Tastatur-Logik      |
| **Audio-Modul**      | Erste Integration für Sound-Management        |

---

## 📦 Struktur

```bash
CoreEngine/
├── src/               # Engine Source Code (C++ oder Rust)
├── examples/          # Beispielspiele und Demos
├── docs/              # Projektdokumentation
├── shaders/           # GLSL/HLSL Shader
├── tools/             # Interne Tools (z. B. Map-Editor)
└── build/             # Build-Ausgaben
```

## 🎯 Zielgruppe

Dieses Projekt richtet sich an:

- 🔧 Entwickler:innen, die sich mit dem Aufbau von Game Engines vertraut machen möchten
- 🎓 Studierende oder Selbstlerner:innen, die tiefes technisches Verständnis aufbauen möchten
- 💼 Bewerber:innen, die ein starkes, technisch anspruchsvolles Projekt für ihr Portfolio suchen
- 🧪 Experimentierfreudige, die eigene Tools, Spiele oder Prototypen unabhängig entwickeln wollen

---

## 🛣️ Roadmap

| Phase | Ziel                                                   | Status         |
|-------|--------------------------------------------------------|----------------|
| 1     | Initiales Setup & Projektstruktur                      | ⬜ Geplant       |
| 2     | OpenGL-Renderer & Shaderpipeline                       | ⬜ Geplant       |
| 3     | Eigenes ECS-System (Basisstruktur)                     | ⬜ Geplant       |
| 4     | Input-System & Windowing                               | ⬜ Geplant       |
| 5     | Audio-System (Basisintegration)                        | ⬜ Geplant       |
| 6     | Ressourcenverwaltung & Szenenstruktur                  | ⬜ Geplant       |
| 7     | GUI & Editor-Tooling                                   | ⬜ Geplant       |
| 8     | Erste Demo-Spiele & Buildsystem                        | ⬜ Geplant       |

---

## 🧪 Build & Tools

| Tool / Sprache     | Nutzung                        |
|--------------------|--------------------------------|
| CMake              | Build-System für C++           |
| Cargo (optional)   | Falls Rust verwendet wird      |
| OpenGL / Vulkan    | Grafik-Rendering               |
| SDL / GLFW         | Plattformunabhängige Fenster   |
| stb_image / Assimp | Asset-Lader                    |
| ImGui (optional)   | Debug-UI & Tooling             |

---

## 📚 Dokumentation

Alle technische Dokumentation wird in Markdown unter `docs/` gepflegt.  
Eine spätere Migration auf **Doxygen**, **MkDocs** oder ein vergleichbares System ist angedacht.

---

## 🧾 Lizenz & Rechtliches

> Dieses Repository ist **nicht unter einer Open Source Lizenz** verfügbar.  
> Jegliche Form der Nutzung, Vervielfältigung, Veränderung oder Weitergabe ist nur mit  
> **schriftlicher Genehmigung des Eigentümers** erlaubt.  
> Die Inhalte dienen ausschließlich Demonstrations- und Bildungszwecken.

---

## 📝 Lizenz
Dieses Projekt unterliegt einer benutzerdefinierten Lizenz.  
Details findest du in der Datei [LICENSE.md](./LICENSE.md).  
**Eine Nutzung oder Verbreitung ist nur mit ausdrücklicher Genehmigung erlaubt.**

---

⏳ Dieses Dokument wird regelmäßig überarbeitet.  
Letzte Bearbeitung: 03.08.2025
