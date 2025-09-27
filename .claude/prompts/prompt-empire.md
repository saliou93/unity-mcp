# Prompt Empire - Unity MCP Command Center

## 🏛️ Empire Overview
**Prompt Empire** is a comprehensive prompt management system for Unity MCP operations. This centralized command center provides structured prompts for various Unity development scenarios using the MCP (Model Context Protocol) bridge.

## 🎯 Mission Directives

### Core Objectives
1. **Streamline Unity Development** - Provide efficient, tested prompts for common Unity tasks
2. **Standardize MCP Interactions** - Ensure consistent communication with Unity Editor
3. **Accelerate Prototyping** - Rapid iteration through pre-built prompt templates
4. **Maintain Code Quality** - Built-in validation and best practices

## 🛠️ Available Prompt Modules

### Module Alpha: Scene Management Empire
```
Context: Unity scene operations and hierarchy management
Tools: manage_scene, manage_gameobject, manage_asset
Focus: Creating, organizing, and optimizing Unity scenes
```

### Module Beta: Script Generation Empire  
```
Context: C# script creation and modification
Tools: manage_script, script_apply_edits, validate_script
Focus: Component creation, gameplay mechanics, Unity patterns
```

### Module Gamma: Asset Pipeline Empire
```
Context: Asset import, processing, and management  
Tools: manage_asset, manage_shader, execute_menu_item
Focus: Textures, models, materials, and asset optimization
```

### Module Delta: Testing & Validation Empire
```
Context: Code validation and testing workflows
Tools: validate_script, read_console, apply_text_edits  
Focus: Error checking, performance validation, automated testing
```

## 📋 Prompt Templates

### Template: 3D Player Controller Creation
```markdown
**Objective**: Create a comprehensive 3D player controller
**MCP Tools Required**: manage_script, manage_gameobject, validate_script
**Parameters**: 
- Movement speed, jump height, ground detection
- Input handling (WASD/Arrow keys, mouse look)
- Physics integration (Rigidbody, Collider)

**Execution Pattern**:
1. Generate PlayerController.cs script with proper Unity structure
2. Create player GameObject with required components
3. Validate script for syntax and Unity best practices
4. Test movement functionality
```

### Template: Shader Creation and Application
```markdown  
**Objective**: Generate custom shader and apply to materials
**MCP Tools Required**: manage_shader, manage_asset, manage_gameobject
**Parameters**:
- Shader type (Unlit, Standard, Custom)
- Visual properties (color, transparency, effects)
- Material application target

**Execution Pattern**:
1. Create shader file with specified properties
2. Generate material using the shader
3. Apply material to target GameObjects
4. Preview and validate visual results
```

### Template: Scene Setup and Lighting
```markdown
**Objective**: Configure scene environment and lighting
**MCP Tools Required**: manage_scene, manage_gameobject, manage_asset  
**Parameters**:
- Environment type (indoor, outdoor, abstract)
- Lighting setup (directional, point, spot lights)
- Skybox and atmosphere settings

**Execution Pattern**:
1. Load/create target scene
2. Add and configure lighting GameObjects  
3. Set skybox and environment settings
4. Validate scene performance and visual quality
```

## 🎪 Empire Command Patterns

### Pattern: Rapid Prototyping
```
1. Scene initialization with manage_scene
2. Core GameObject creation with manage_gameobject  
3. Script attachment with manage_script
4. Material and visual setup with manage_asset
5. Testing and validation with validate_script
```

### Pattern: Asset Integration
```
1. Asset import and processing with manage_asset
2. Material creation and assignment with manage_shader
3. GameObject instantiation and setup with manage_gameobject
4. Scene integration with manage_scene
5. Quality validation with read_console
```

### Pattern: Code Enhancement  
```
1. Script analysis with validate_script
2. Structured edits with script_apply_edits
3. Syntax validation with validate_script
4. Functional testing through Unity console
5. Performance optimization iteration
```

## 🚀 Quick Start Commands

### Game Object Creation Empire
```
"Create a [OBJECT_TYPE] with [SPECIFIC_PROPERTIES] in the current scene"
- OBJECT_TYPE: cube, sphere, player, enemy, platform, etc.
- SPECIFIC_PROPERTIES: color, size, position, components, behavior
```

### Script Generation Empire
```
"Generate a [SCRIPT_TYPE] script that handles [FUNCTIONALITY]"  
- SCRIPT_TYPE: MonoBehaviour, ScriptableObject, Editor, Custom
- FUNCTIONALITY: movement, interaction, data management, UI, etc.
```

### Material & Shader Empire
```
"Create a [MATERIAL_TYPE] material with [VISUAL_PROPERTIES]"
- MATERIAL_TYPE: Standard, Unlit, Custom shader-based
- VISUAL_PROPERTIES: color, texture, transparency, emission, etc.
```

## 🔧 Advanced Empire Operations

### Batch Processing Commands
- **Multi-Object Creation**: "Create 10 enemy prefabs with varying properties"
- **Scene Population**: "Fill scene with environmental objects using provided assets"  
- **Material Assignment**: "Apply weather-damaged materials to all building objects"

### Workflow Automation
- **Build Pipeline**: Automated asset processing and scene setup
- **Testing Suite**: Comprehensive script validation and error checking
- **Optimization Pass**: Performance analysis and improvement suggestions

## 📊 Empire Analytics & Reporting

### Success Metrics
- Script validation pass rate
- Asset processing efficiency  
- Scene setup completion time
- Error detection and resolution

### Quality Assurance
- Unity best practices compliance
- Performance benchmarking
- Code structure analysis
- Asset optimization verification

## 🛡️ Empire Safeguards

### Error Prevention
- Pre-execution validation checks
- Rollback capabilities for failed operations
- Resource conflict detection
- Performance impact assessment

### Best Practices Enforcement
- Unity coding standards compliance
- Proper component usage patterns
- Efficient resource management
- Maintainable code structure

## 🎖️ Empire Achievements

### Mastery Levels
- **Initiate**: Basic Unity operations and simple scripts
- **Architect**: Complex scene setup and advanced scripting  
- **Emperor**: Full project automation and advanced workflows
- **Legend**: Custom tool creation and empire expansion

---

*Welcome to the Prompt Empire - Where Unity development meets AI efficiency!*

**Version**: 1.0.0  
**Compatible with**: Unity MCP Bridge v1.0+  
**Last Updated**: December 2024