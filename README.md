# Tower defense game

Gameplay video: https://youtu.be/4asb3rRyqhg.
</br>Project created in Unity 2022.3, run on MacBook Air M1 2020

</br>Screenshot:

![Tower defense game screenshot](https://github.com/ilialek/Resources/blob/main/Tower%20defense%20game.png)

## 🎮 Key Features
- **Dynamic Waves**: 
  - 5+ waves of enemies, each progressively harder.
  - Fully customizable in the Unity Editor (enemy types, amounts, delays, and more).
- **Strategic Towers**: 
  - Three distinct tower types:
    - **Single Target Attack**
    - **AOE Attack**
    - **Debuff Attack** (e.g., slows enemies, effects don’t stack).
  - Towers are upgradeable with visual changes for different levels.
  - Damage, range, and attack interval are displayed to players before purchase.
- **Challenging Enemies**: 
  - Enemies follow non-straight paths to the goal.
  - Unique properties: health, speed, and carried money.
  - When destroyed, money gained is shown near the enemy.
- **Intuitive GUI**: 
  - Displays essential information:
    - Wave number
    - Total money
    - Time left for building/upgrade phase
    - Enemy health bars
    - Remaining enemies before game over
    - Final game state (win/lose).
  - Fully resolution-independent UI.
- **Smooth Gameplay**:
  - Adjustable game speed using `Time.timeScale`.
  - No exceptions or warnings in the console.
  - Seamless restart without restarting the application.

## 💡 Technical Highlights
- **Software Patterns**:
  - **Singletons** for managing global state.
  - **Observer Pattern** for event-driven behavior.
  - **Scriptable Objects** for configurable, reusable data.
- **Editor Configurability**:
  - Game elements (waves, enemies, towers) can be modified directly in the Unity Editor without changing the code.
- **Project Organization**:
  - Clear hierarchy and descriptive scene/asset names for maintainability.
