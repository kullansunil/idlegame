# Define the path to the README.md file
readme_path = "/mnt/data/idlegame-main/idlegame-main/README.md"

# Define the Player's Guide content to add
players_guide_content = """
## Player's Guide

Welcome to **Idle Game**! This guide will help you understand the game mechanics and get started quickly.

### 1. Objective
The goal of the game is to accumulate resources by automating tasks, upgrading systems, and unlocking achievements.

### 2. How to Play
- **Start the game:**
  Run the following command:
  ```bash
  python run.py
Collect resources: Resources are generated over time.
Upgrade your systems: Use collected resources to buy upgrades and improve automation.
3. Game Features
Automation: Automate resource generation to optimize gameplay.
Upgrades: Unlock powerful upgrades to accelerate progress.
Achievements: Earn achievements as you hit milestones.
4. Tips for Success
Upgrade early: Automate tasks as soon as possible for faster growth.
Plan strategically: Manage resources carefully to maximize efficiency.
Save frequently: Ensure your progress is saved to avoid losing data. """
Read the original README.md, append the new content, and save it back
with open(readme_path, 'a') as readme_file: readme_file.write(players_guide_content)
