# **Wyrd Waters Public Test**

## **Best Practices for QA Testing**

### **1. Test Methodically**
- **Explore Thoroughly**: Play the game as intended but also try actions that might break it. Test features systematically (e.g., menu interactions, combat mechanics).
- **Reproduce Issues**: Before reporting a bug, attempt to recreate it multiple times to confirm consistency.

---

### **2. Document Issues Clearly**
When reporting bugs, use the GitHub issue tracker and follow these guidelines:

#### **2.1 Use a Descriptive Title**
- **Good**: "Boat falls through the map after moving under the bridge."
- **Bad**: "Weird bug with falling."

#### **2.2 Provide Reproduction Steps**
Write step-by-step instructions to help developers replicate the bug. Example:

1. Launch the game.
2. Load the "Kraken" map.
3. Move under the bridge with any ship.
4. Observe the ship falling through the terrain.

#### **2.3 Include Expected vs. Actual Behavior**
- **Expected**: What you believe should have happened (I sailed under the bridge and passed under it from one side to the other.
- **Actual**: What actually occurred (I sailed under the bridge and fell through the map. I was unable to progress).

#### **2.4 Attach Evidence**
- **Screenshots**: Highlight visual bugs or incorrect UI elements.
- **Videos**: Provide context for animation or timing issues.
- **Logs**: If the game produces crash logs, attach them to the issue.

#### **2.5 Specify Environment Details in Description Section**
- **Game version or build number**.
- **Platform**: PC, Mac, etc.
- **Operating system**: Windows 11, macOS Monterey, etc.
- **Hardware**: CPU, GPU,
- **Game settings**: Resolution.

#### **2.6 Assign Labels**
Use GitHub's labeling system to categorize issues:
- **Critical**: Game crashes or unplayable scenarios.
- **High Priority**: Severe bugs but not game-breaking.
- **Medium Priority**: Moderate issues, such as visual glitches.
- **Low Priority**: Minor inconsistencies or polish issues.

---

### **3. Focus on Technical Issues**
Your goal is to identify **technical problems**, not design critiques. Examples of technical bugs include:

#### **Performance Issues**:
- Frame rate drops.
- Game stuttering or freezing.
- Excessive load times.

#### **Gameplay Bugs**:
- Incorrect physics behavior (e.g., floating objects).
- Missing or incorrect collision detection.
- Broken quests or objectives.

#### **Visual Issues**:
- Texture clipping or stretching.
- Missing assets or invisible models.

#### **Audio Problems**:
- Missing sound effects or music.
- Audio playing at incorrect times or volumes.

#### **UI/UX Problems**:
- Buttons that don’t respond.
- Text overlapping or out of bounds.

#### **Networking Bugs**:
- Multiplayer desyncs.
- Connection issues.

Avoid commenting on subjective design choices (e.g., "I don’t like how this character looks" or "This level is too hard"). Instead, focus on objective issues.

---

### **4. Use GitHub Effectively**
- **Search First**: Before creating a new issue, check if the bug has already been reported. Add comments or additional details to existing issues if necessary.
- **Be Concise**: Avoid long narratives. Stick to the relevant facts about the issue.
- **Stay Respectful**: Avoid blaming or criticizing developers. QA testing is about collaboration, not judgment.

---

### **5. Stay Organized**
- **Maintain a personal checklist** of areas you've tested to avoid duplication.
- **Rotate your focus** between game features (e.g., start with combat, then test exploration, then the UI).
- **Collaborate with fellow testers** by discussing issues and clarifications.

---

### **Example GitHub Issue Report**

**Title**: "Crash when opening inventory during combat in Build 1.2.4"

**Reproduction Steps**:
1. Start a new game and progress to the first battle.
2. During combat, press "I" to open the inventory.
3. The game freezes and crashes.

**Expected Behavior**: The inventory should open without crashing.

**Actual Behavior**: The game freezes and crashes to the desktop.

**Environment**:
- **Game Version**: 1.2.4
- **Platform**: PC
- **OS**: Windows 11
- **Hardware**: Intel i7, 16GB RAM, NVIDIA RTX 3060

**Attachments**:
- Screenshot of error message.
- Crash log file.

**Labels**: Critical, Gameplay Bug

---

### **6. Final Tips**

- **Be Curious**: Try unusual actions to uncover edge cases (e.g., what happens if you open the menu during a cutscene?).
- **Be Patient**: Some bugs are hard to reproduce; don’t give up too quickly.
- **Be Thorough**: Explore all possible interactions with objects, NPCs, and menus.

---

Thank you for your hard work and dedication to improving *Wyrd Waters*! Together, we’ll create an exceptional game.

