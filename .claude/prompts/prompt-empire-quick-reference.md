# Prompt Empire - Quick Reference Guide

## 🎯 Essential Commands

### Scene Operations
```bash
# Scene creation and management
"Create a new scene with basic lighting setup"
"Load scene [SCENE_NAME] and prepare for editing"
"Save current scene as [SCENE_NAME] in [FOLDER_PATH]"
```

### GameObject Creation
```bash  
# Basic object creation
"Create a [OBJECT_TYPE] at position [X,Y,Z]"
"Duplicate [OBJECT_NAME] [COUNT] times in a [PATTERN]"
"Create a player character with movement controller"
```

### Script Generation
```bash
# Component scripts
"Generate a [COMPONENT_NAME] script for [PURPOSE]"
"Create a singleton manager for [SYSTEM_NAME]"
"Write a custom inspector for [SCRIPT_NAME]"
```

### Asset Management
```bash
# Asset operations
"Import [ASSET_TYPE] from [FILE_PATH]" 
"Create a material with [PROPERTIES]"
"Generate a skybox from [SOURCE]"
```

## 🔥 Power User Combinations

### Complete Player Setup
```markdown
1. "Create a capsule GameObject named 'Player'"
2. "Generate a PlayerController script with WASD movement"  
3. "Add Rigidbody and CapsuleCollider to Player"
4. "Create a follow camera script for third-person view"
5. "Test player movement and validate all scripts"
```

### Environment Creation
```markdown
1. "Create a plane GameObject scaled to 10x10 for ground"
2. "Generate a grass material and apply to ground"
3. "Create 5 cube obstacles randomly positioned"
4. "Add directional light with sunset colors"
5. "Set up skybox with evening atmosphere"
```

### UI System Setup  
```markdown
1. "Create a Canvas with proper scaling settings"
2. "Add a main menu with Start and Quit buttons"
3. "Generate a GameManager script for scene transitions"
4. "Create button click handlers and animations"
5. "Test all UI interactions and validate scripts"
```

## 🎨 Creative Prompt Templates

### Game Mechanics
- "Create a collectible system with particle effects"
- "Generate an inventory manager with UI integration"
- "Build a health system with visual feedback"
- "Design a scoring system with leaderboard"

### Visual Effects
- "Create a fire shader with animated flames"
- "Generate particle system for magic spells"
- "Build a day/night cycle with lighting transitions"
- "Design weather effects with audio integration"

### Audio Integration
- "Create an audio manager for background music"
- "Add sound effects to player actions"
- "Generate a 3D audio system for environment"
- "Build a music transition system for different areas"

## 🚀 Advanced Workflows

### Rapid Prototyping
```markdown
**Goal**: Playable prototype in 15 minutes
1. Scene setup (2 min)
2. Player controller (5 min)
3. Basic gameplay mechanic (5 min)
4. Simple UI (2 min)
5. Testing and polish (1 min)
```

### Asset Pipeline Automation
```markdown
**Goal**: Streamlined asset integration
1. Batch import assets with proper settings
2. Auto-generate materials from textures
3. Create prefabs from imported models
4. Set up LOD groups for performance
5. Validate all assets for build compatibility
```

### Code Quality Assurance
```markdown
**Goal**: Maintainable, error-free code
1. Generate scripts with proper structure
2. Validate syntax and Unity best practices
3. Add error handling and null checks
4. Create unit tests where appropriate
5. Document all public methods and classes
```

## 💡 Pro Tips

### Efficiency Boosters
- Use specific object names for better tracking
- Include validation steps in complex operations
- Leverage prefabs for reusable components
- Set up folder structure before asset creation

### Common Pitfalls to Avoid
- Don't skip script validation steps
- Avoid hardcoded values in generated scripts
- Remember to assign required component references
- Test functionality immediately after creation

### Performance Considerations  
- Use object pooling for frequently spawned objects
- Implement proper LOD systems for complex models
- Optimize materials for target platform
- Profile performance after major changes

---

*Prompt Empire Quick Reference - Your gateway to Unity MCP mastery!*