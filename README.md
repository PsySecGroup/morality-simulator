# Morality Simulator

**🚀 [Try the Live Demo](https://psysecgroup.github.io/morality_simulator.html)**

A dynamic simulation that demonstrates the complex, unintended consequences of moral rules and behavioral dictates in interconnected systems. While disguised as a "temperature" system, this simulator reveals how simple moral imperatives can create chaotic, emergent behaviors that often contradict their intended purpose.

![Morality Simulator Demo](https://img.shields.io/badge/demo-live-brightgreen) ![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow) ![License](https://img.shields.io/badge/license-MIT-blue)

## 🎯 Purpose

People often believe they can solve complex social problems with simple moral rules: _"Just be kind," "Always tell the truth," "Help others first,"_ etc. This simulator demonstrates why such approaches frequently backfire by showing how:

- **Simple rules create complex behaviors** - Even basic moral imperatives generate unpredictable emergent patterns
- **Context matters more than rules** - The same moral rule can have opposite effects depending on the surrounding "moral climate"
- **Moral systems are chaotic** - Small changes in interpretation or application can lead to dramatically different outcomes
- **Unintended consequences are inevitable** - Well-intentioned rules often produce results opposite to their goals

## 🧠 The Metaphor

| Simulation Element | Real-World Parallel |
|-------------------|---------------------|
| **Nodes** | Individual people or groups |
| **Values (0.0-1.0)** | Moral/behavioral states |
| **Categories** | Behavioral classifications based on current state |
| **Connections** | Social relationships and influence networks |
| **Rules** | Moral imperatives and behavioral expectations |
| **Chaos Level** | Unpredictability in human behavior |
| **Convergence** | How quickly people adapt to social pressure |

## 🎮 How It Works

### Dynamic Moral Categories

Individuals automatically shift between behavioral categories based on their current "moral temperature":

- **🧊 Cold (0.00-0.25)** - Withdrawn, defensive, rigid
- **⚖️ Stable (0.25-0.50)** - Balanced, moderate behavior  
- **💜 Default (0.50-0.75)** - Normal social engagement
- **🔥 Hot (0.75-1.00)** - Passionate, activist, extreme

### Behavioral Rules

Create moral imperatives that govern how different groups influence each other:

- **Attract** - "Be more like virtuous people" (often creates conformity pressure)
- **Repel** - "Avoid bad influences" (can create polarization)
- **Amplify** - "Encourage good behavior" (may cause overreaction)
- **Dampen** - "Calm extremes" (might suppress legitimate passion)
- **Synchronize** - "Find common ground" (can lead to lowest-common-denominator thinking)

### Visual Feedback

- **Arrow directions** show each individual's current behavioral state (0° = withdrawn, 180° = moderate, ~360° = extreme)
- **Color coding** reveals current behavioral category
- **Connection lines** highlight when moral rules are actively influencing relationships
- **Real-time changes** demonstrate how quickly moral climates can shift

## 🧪 Experiments to Try

### 1. The Kindness Paradox
Set up rules where "kind" people try to help others become kinder. Watch how this can create:
- Moral superiority complexes
- Exclusion of those deemed "unkind"
- Pressure that drives people to extremes

### 2. The Tolerance Trap
Create rules promoting tolerance and acceptance. Observe how:
- Intolerance of intolerance emerges
- Moderate voices get drowned out
- "Tolerance" becomes another form of moral rigidity

### 3. The Purity Spiral
Implement rules that encourage moral purity. See how:
- Standards continuously escalate
- Previously acceptable behavior becomes "problematic"
- The system consumes its own adherents

### 4. The Stability Illusion
Try to create a perfectly balanced moral system. Notice how:
- Small perturbations create large swings
- Stability requires constant active management
- "Balance" often means suppressing natural variation

## 🎛️ Controls

### Global Settings
- **Chaos Level** - How unpredictable people are (spoiler: they're very unpredictable)
- **Convergence** - How quickly people conform to social pressure
- **Connection Density** - How interconnected your social network is
- **Node Count** - Population size

### Rule Creation
1. **Name your rule** - What moral imperative are you implementing?
2. **Source category** - Which group initiates the behavioral influence?
3. **Target category** - Which group is being influenced? (optional - can affect everyone)
4. **Rule type** - How does the influence work?
5. **Strength** - How forcefully is this rule applied?

### Pre-built Templates
- **🌡️ Temperature System** - Basic thermal dynamics (good for understanding the mechanics)
- **⚖️ Stability System** - Rules designed to create balance (watch them fail)
- **🌊 Wave System** - Resonance and interference patterns in moral behavior

## 🛠️ Technical Details

- **Pure JavaScript** - No frameworks, runs entirely in the browser
- **Real-time simulation** - 60fps animation with dynamic rule application
- **Responsive design** - Works on desktop and mobile devices
- **No data collection** - Everything runs locally in your browser

## 🤝 Contributing

This simulator is designed to provoke thought about the unintended consequences of moral systems. Contributions that add new rule types, behavioral patterns, or analytical tools are welcome.

### Ideas for Enhancement
- **Historical scenarios** - Recreate famous moral panics or social movements
- **Network topology options** - Different social connection patterns
- **Moral memory** - Nodes that remember past moral states
- **Institutional actors** - Special nodes representing organizations or governments
- **Cultural transmission** - Rules that evolve and mutate over time

## 📚 Further Reading

- *The Righteous Mind* by Jonathan Haidt
- *Moral Politics* by George Lakoff  
- *The Road to Hell: The Ravaging Effects of Foreign Aid and International Charity* by Michael Maren
- *Seeing Like a State* by James C. Scott
- *The Fatal Conceit* by Friedrich Hayek
