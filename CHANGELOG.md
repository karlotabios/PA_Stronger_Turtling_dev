# 🛠️ Version 1.0 Initial Build

> All changes mentioned here refer to increases/reductions/etc. to the original values of the stats of units from the base PA:T game as of Build 120799

### 🔫 Laser Defense Towers
- **All Laser Defense Towers**
  - 🔼 Firing Range increased by **50%**
    > laser_defense_single_tool_weapon.json "max_range":100 → 150

	> laser_defense_tool_weapon.json "max_range":110 → 165

	> laser_defense_adv_tool_weapon.json "max_range":120 → 180
  - 🔼 Projectile Speed increased by **50%**
    > laser_defense_single_ammo.json 
	> "initial_velocity":500 → 750
	> "max_velocity":500 → 750

	> laser_defense_ammo.json
	> "initial_velocity":500 → 750
	> "max_velocity":500 → 750

	> laser_defense_adv_ammo.json
	> "initial_velocity":500 → 750
	> "max_velocity":500 → 750

- **Single Laser Defense Tower**
  - 🔽 Damage reduced by **25%**
    > laser_defense_single_ammo.json "damage":40 → 30
  - 🔼 Rate of Fire increased by **100%**
    > laser_defense_single_tool_weapon.json "rate_of_fire":2 → 4

- **Double Laser Defense Tower**
  - 🔽 Damage reduced by **60%**
    > laser_defense_ammo.json "damage":75 → 30
  - 🔼 Rate of Fire increased by **300%**
    > laser_defense_tool_weapon.json "rate_of_fire":2 → 8

- **Advanced Triple Laser Defense Tower**
  - ➖ No change to Damage
  - 🔼 Rate of Fire increased by **66.67%**
    > laser_defense_adv_tool_weapon.json "rate_of_fire":3 → 5

---

### 🧨 Static Artillery (Pelter & Holkins)
- 🔼 Firing Range increased by **25%**
  > artillery_short_tool_weapon.json "max_range":260 → 325

  > artillery_long_tool_weapon.json "max_range":600 → 750
- 🔼 Splash Radius increased by **100%**
  > artillery_short_ammo.json 
  > "splash_radius":12 → 24
  > "full_damage_splash_radius":2 → 4

  > artillery_long_ammo.json 
  > "splash_radius":20 → 40
  > "full_damage_splash_radius":5 → 10

---

### 🎯 Static Anti-Air Defenses (Galata & Flak)
- 🔼 Firing Range increased by **100%**
  > air_defense_tool_weapon.json "max_range":150 → 300
  
  > air_defense_adv_tool_weapon.json "max_range":100 → 200

---

### 🛡️ Anti-Nuke
- 🔼 Firing Range increased by **50%**
  > anti_nuke_launcher_tool_weapon.json "max_range":300 → 450

---

### 💥 Catapult
- 🔽 Rate of Fire reduced by **40%**
  > tactical_missle_launcher_tool_weapon.json "rate_of_fire":0.25 → 0.15

  > tactical_missle_tool_antidrop.json "rate_of_fire":0.25 → 0.15
- 🔼 Damage increased by **30%**
  > tactical_missle_launcher_ammo.json "damage":1000 → 1300

  > tactical_missle_antidrop_ammo.json "damage":400 → 520
- 🔼 Firing Range increased by **100%**
  > tactical_missle_launcher_tool_weapon.json "max_range":240 → 480
  
  > tactical_missle_tool_antidrop.json "max_range":240 → 480
- 🆕 Now has **Splash Damage**
  > tactical_missle_launcher_ammo.json 
  > "splash_damage":0 → 1300
  > "splash_radius":0 → 25

  > tactical_missle_antidrop_ammo.json
  > "splash_damage":0 → 520
  > "splash_radius":0 → 10

---

### ☄️ Orbital Defenses

- **Umbrella**
  - 🔽 Rate of Fire reduced by **50%**
  > ion_defense_tool_weapon.json "rate_of_fire":2.5 → 1.25
  > ion_defense_tool_antidrop.json "rate_of_fire":2 → 1
  - 🔼 Damage increased by **100%**
  > ion_defense_ammo.json "damage":150 → 300
  > ion_defense_antidrop_ammo.json "damage":400 → 800
  - 🔼 Firing Range increased by **50%**
  > ion_defense_tool_weapon.json "max_range":300 → 450
  > ion_defense_tool_antidrop.json "max_range":180 → 270

- **Anchor**
  - 🔽 Rate of Fire reduced by **50%**
  > defense_satellite_tool_orbital.json "rate_of_fire":2.5 → 1.25
  > defense_satellite_tool_ground.json "rate_of_fire":2 → 1
  - 🔼 Damage increased by **100%**
  > defense_satellite_ammo_orbital.json "damage":65 → 130
  > defense_satellite_ammo_ground.json "damage":65 → 130
  - 🔼 Firing Range increased by **20%**
  > defense_satellite_tool_orbital.json "max_range":150 → 180
  > defense_satellite_tool_ground.json "max_range":100 → 120