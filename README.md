# Rogue Heist: Name Pending

A dynamic and challenging roguelike game where you play as a robber trying to infiltrate high-security locations to make your escape. Use stealth, combat, and strategy to outsmart or defeat guards, but be careful — every decision has consequences. If you’re spotted, the whole place goes into lockdown, and you’ll have to fight your way out!

## 🚀 Features

- **Choose Your Character**: Select between two unique characters, each with their own playstyle.
  - **Layla**: A highly intelligent female robber who specializes in mechanics and hacking, offering a more brainiac approach.
  - **Lewis**: A stealthy, ninja-like male robber with enhanced athleticism and skills for evasion and sneaking.
- **Stealth Kills**: Take out guards silently to avoid triggering alarms.
- **Combat Mode**: If you're spotted, you can fight your way out, but guards will shoot back.
- **Lockdown**: If a guard finds a body, the entire facility goes into lockdown. Reinforcements spawn, and you must fight your way to escape.
- **Health System**: Heal or hide to recover from injuries.
- **AI Behavior**: Guard AI responds dynamically to player actions (searching for bodies, calling for reinforcements, etc.).
- **Multiple Playstyles**: You can choose between stealth, panther (tactical kills), or full combat.

## 🧠 Game Design

### 1. **Player Intent**
Rogue Heist encourages the player to experiment with different strategies — stealth, combat, or a mix of both. Every decision impacts the flow of the game, with a dynamic AI system that reacts to your actions.

### 2. **Core Mechanics**
- **Stealth Kills**: You can silently take down guards from behind (press [E] when close).
- **Alert System**: If a guard sees you or finds a body, an alert phase begins.
- **Lockdown Mechanic**: If bodies are found, the facility enters **lockdown**. You must escape or survive reinforcements.
- **Health and Healing**: Use limited resources to heal or hide when injured.

### 3. **Lockdown Feature**
- If a body is discovered, the alarm triggers and the facility enters **lockdown**.
- **Reinforcements** arrive, and you have limited time to fight or escape.
- The **exit is locked** until you disable the lockdown or survive the onslaught of guards.
- Players can **fight** through waves of guards or **escape** through hidden routes or by unlocking the exit.

### 4. **Character Selection**
- **Layla**: A brainiac who excels in hacking, mechanics, and problem-solving. Her perk allows her to interact with devices, hack doors, or disable security with ease.
- **Lewis**: A more athletic and stealthy character. His perk grants faster movement, climbing abilities, and more effective sneaking past guards without being detected.

### 5. **Failure States**
- If you’re killed, the run ends and you restart from the beginning.
- If the alarm reaches the highest level, the facility will lock down, and you must either escape or defeat all enemies to continue.

## 🎮 Gameplay Walkthrough

1. **Start Infiltration**: Begin the heist by sneaking through high-security rooms, avoiding guards, and collecting loot.
2. **Get Spotted**: If spotted by a guard, you can choose to fight or retreat. 
3. **Lockdown Triggered**: If you’re careless and leave bodies behind, the lockdown will trigger, and reinforcements will arrive.
4. **Escape or Fight**: Once in lockdown, your objective changes to either escaping or surviving until you can disable the lockdown.

## 📈 Progression

- **Difficulty Scaling**: As you progress, the AI becomes more aggressive, and guards become more difficult to take out.
- **Unlockables**: New gadgets (e.g., silent weapons, hacking tools) and health upgrades become available as you survive longer runs.

## 🛠️ How to Play

1. Clone or download the repository.
2. Run the game using **Godot Engine**.
3. Follow on-screen instructions to control your character (movement, stealth, combat).
4. Use **[E]** to perform stealth kills and avoid detection.
5. Survive through lockdowns or fight your way out!

## 💻 Technologies

- **Game Engine**: Godot Engine (2D)
- **Languages**: GDScript (Godot's scripting language)
- **Libraries**: Godot's built-in tools

## 🤝 Contributions

- Fork this repository to contribute your ideas, bug fixes, or additional features.
- Feel free to submit issues or pull requests.

## 📅 Milestones

- **Alpha 1.0**: Basic stealth mechanics, combat system, and lockdown feature.
- **Beta 1.0**: Full AI implementation, dynamic environments, and enhanced combat.

