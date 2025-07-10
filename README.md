# 🌱 Shared Roots
---
<strong>Shared Roots</strong> is A unique 3D farm game from <strong>TinySeed Games</strong>.


---
# 🏛 Code Style Guide

Our team is committed to code quality. To ensure consistency and readability across the project, we follow a set of established rules and patterns.

## 📜 Naming Conventions
Consistent naming for scripts and assets is crucial for organization.

### C# Scripts 
- Classes, Structs, Enums: Use _PascalCase_.
    - Examples: PlayerController, GameState, Move()
      
- Public Variables & Properties: Use _PascalCase_ with and m_ prefix.
    - Examples: public int m_PlayerHealth, public float m_MoveSpeed { get; private set; }

- Private & Protected Variables: Use _camelCase_ with m_ prefix.
    - Examples: private float m_score, protected bool _isGrounded
  
- Booleans (bools): Use prefixes like _is_, _has_, _can_ for clarity.
    - Examples: isJumping, hasKey, canAttack

- Methods: Use _PascalCase_ and _verbs_
    - Examples: Move(), Jump(), DoSomething()

### Assets
To make assets easier to find and identify, they must have a _suffix_ indicating their type. The pattern is _AssetName_suffix_
- Material: __mat_ (Player_mat)
- Prefab: __prefab_ (Player_prefab)
- Audio (SFX): __sfx_ (Jump_sfx)
- Scriptable Object: __so_ (Settings_so)
- Texture: __tex_ (Grass_tex)
- Animation: __anim_ (PlayerRun_anim)
- Animator Controller: __ac_ (Player_ac)
- Visual Effect: __vfx_ (DirtParticle_vfx)
- Shader: __shader_ (Water_shader)

Unity Version: 2023.2.20f1
