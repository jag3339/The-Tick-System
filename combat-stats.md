- STR: lbf to inflict damage. If it exceeds the lbf threshold of the target's def, the damage equals their difference
- DEF: lbf to resist damage. Can't be hurt if the threshold won't break
- SPD: mph of maximum movement speed. Can add to total damage
- REA: ms, µs, ns to react to stimuli. Can help DEF by offsetting the lbf, minimizing the damage. Or just dodging the attack entirely.
- END: Damage reduction. When the threshold breaks, how much can you take?
- VP: Verity pool. How much verity do you have?
- VC: Verity control. What percentage of efficiency can you use your verity with?
- CUT: psi of weapon or bullet. How sharp is it? SPD factors in as well.
- STAM: Stamina. 
- LP: Life pool.

Substats:
- DODGE: SPD and REA
- CUT RES: psi that your armor can take before being sliced into two

Defense Flow – “Can You Hurt Me?”

**Step 1 – DEF Check:**
- Compare attacker’s **STR (force)** vs. defender’s **DEF (force threshold)**.
- If STR ≤ DEF → no END damage (bullets ping off armor).
- If STR > DEF → excess force = raw damage potential.

**Step 2 – Dodge Score Check (REA + SPD):**
- If defender’s **REA** beats the attack’s _reaction threshold_ **and** their **SPD** can move them out of line in time → avoid entirely.
- If not → offsetted damage from the difference of the defender's REA and the attacker's SPD applies (modified by END).

**Step 3 – END & DUR Check:**
- Apply **END** (percentage damage reduction).
- Subtract result from **DUR (energy absorption)**.
- When DUR hits 0 → incapacitation/death.

Example Weapon PSI Ratings
- Kitchen knife (sharp): ~2,000 PSI
- Katana (very sharp): ~4,000 PSI
- Modern AP sniper round: ~25,000 PS
- Ascendant-tier Verity blade: 100,000+ PSI

Example CUT RES Ratings
- Ember leather armor: ~500 PSI
- Oathbound plate: ~5,000 PSI
- Vowguard advanced composite: ~20,000 PSI
- Ascendant/Disciple armor: 80,000+ PSI

Attack Resolution Flow
1. **Impact Check:**  
    If STR < DEF, no blunt damage.

2. **Penetration Check:**  
    If Weapon PSI > CUT RES, armor is bypassed.
    
3. **Dodge Check:**  
    REA + SPD vs. projectile/strike timing.
    
4. **Endurance Reduction:**  
    Apply END% to final DUR damage.
    

### **Force vs. Pressure**

- **Force (lbf or kN)** → How _hard_ you’re hitting.
    
    - Think sledgehammer, wrecking ball.
        
    - Good for crushing, breaking, knocking back.
        
- **Pressure (PSI)** → How much force is concentrated into a small area.
    
    - Think scalpel, needle, katana.
        
    - Good for slicing, piercing, cutting.
        

**Pressure = Force ÷ Contact Area**

That’s why:

- A heavy hammer (huge force, big contact area) smashes but doesn’t cut.
    
- A fine-tipped blade (smaller force, tiny contact area) slices deep even without massive muscle behind it.

### **In-World Example**

**Vowguard Armor:**

- DEF (force threshold) = 3,000 lbf
    
- CUT RES (pressure threshold) = 20,000 PSI
    

**Scenario A — Blunt Strike:**

- STR = 2,000 lbf → Can’t beat DEF → no damage.
    

**Scenario B — Sword Swing:**

- STR = 1,500 lbf but blade edge is 0.01 in² contact area →  
    Pressure = 1,500 ÷ 0.01 = 150,000 PSI → **Easily bypasses CUT RES**, penetration occurs.
    

---
Unified attack resolution:

- Step 1: Can I crush you? (**Force vs DEF**)
    
- Step 2: Can I cut/pierce you? (**PSI vs CUT RES**)
    
- Step 3: Can I even touch you? (**REA + SPD Dodge**)
    
- Step 4: Can you shrug it off? (**END & DUR**)

## **Unified Attack Resolution – Step by Step**

### **Step 0 — Context**

Before rolling anything, you already know:

- **Attacker’s STR** (force in lbf or kN)
    
- **Attacker’s Weapon PSI** (sharpness/penetration)
    
- **Defender’s DEF** (force threshold)
    
- **Defender’s CUT RES** (pressure threshold)
    
- **Defender’s REA & SPD** (dodge ability)
    
- **Defender’s END & DUR** (damage reduction & HP)
    

---

### **Step 1 — Impact Check (Force vs DEF)**

- If **STR ≤ DEF** → no blunt damage (attacks bounce off).
    
- If **STR > DEF** → _Excess Force_ = STR – DEF → potential blunt damage amount.
    

---

### **Step 2 — Penetration Check (PSI vs CUT RES)**

- If **Weapon PSI > CUT RES**, armor is bypassed → DUR damage applies _regardless_ of DEF result.
    
- This allows low-force but extremely sharp weapons (e.g., high-tech mono-edge blades, Verity weapons) to still be lethal.
    

---

### **Step 3 — Dodge Window Check (REA + SPD)**

- Determine **reaction window** based on attack type (bullet, sword swing, beam, etc.).
    
- If REA is fast enough **and** SPD can move them clear in that time → dodge successful, no END/DUR damage taken.
    
- Formula example: 
	- Dodge Score = (REA factor x SPD factor) vs attacker's SPD
	- this ensures speedsters can live without armor, but slow tanks can't unless they have an unreal amount of LP

### **Step 4 — Endurance Mitigation (END%)**

- Apply END% reduction to any DUR damage that got through.
    
- END = how much of the blow you can “fight through” without losing combat effectiveness.
    

---

### **Step 5 — Durability Check (DUR in kJ)**

- Subtract remaining damage (converted to kJ) from DUR.
    
- DUR = total energy you can absorb before defeat.
    
- When DUR ≤ 0 → incapacitation or death.
    

---

## **Example — The Hunter vs. the Vowguard**

**Hunter:**

- STR: 1,200 lbf
    
- Weapon PSI: 35,000 PSI
    

**Vowguard:**

- DEF: 3,000 lbf
    
- CUT RES: 20,000 PSI
    
- REA: 80 ms, SPD: 67 mph (water-run)
    
- END: 30%
    
- DUR: 8 kJ
    

**Resolution:**

1. STR 1,200 < DEF 3,000 → blunt force fails.
    
2. PSI 35,000 > CUT RES 20,000 → penetration!
    
3. Vowguard REA/SPD check vs. bullet speed — fails due to distance.
    
4. END 30% cuts damage from 4 kJ → 2.8 kJ.
    
5. DUR 8 – 2.8 = 5.2 kJ → still in the fight, but armor is breached.
    

---

## **Why This Works**

- Makes **armor** and **dodging** separate but equal defense routes.
    
- Lets **tech or Verity** bypass raw DEF — “sharp beats strong” if the PSI is high enough.
    
- Preserves cinematic archetypes:
    
    - **Tanks** → high DEF + END + DUR
        
    - **Speedsters** → high REA + SPD
        
    - **Armor-piercers** → high Weapon PSI
        
    - **Glass Cannons** → high STR/PSI, low DEF/DUR

## **Crown Eclipse – Master Tier Combat Stats**

|Tier|SPD (mph / ft per 6s)|STR (lbf / kN)|DEF (lbf / kN)|CUT RES (PSI)|Weapon PSI Range*|REA (ms)|VRT (% Stability)|END (%)|DUR (kJ)|Notes|
|---|---|---|---|---|---|---|---|---|---|---|
|**Ember** _(Avg Human)_|12 / 106|150 / 0.67|100 / 0.45|500|100–1,000|250|5–10|5|0.3|Civilian baseline; pistols, crude blades|
|**Oathbound** _(Peak Human)_|28 / 246|500 / 2.22|400 / 1.78|5,000|500–5,000|150|15–25|10|0.8|Elite soldier; high-grade armor, pro marksman|
|**Vowguard**|67 / 590|3,000 / 13.34|2,500 / 11.12|20,000|5,000–50,000|80|40–60|30|8|Water-run threshold; composite armor; Verity sidearms|
|**Ascendant**|200 / 1,760|12,000 / 53.38|10,000 / 44.48|80,000|50,000–250,000|20|70–90|50|60|Island-to-island strike; mono-edge Verity weapons|
|**Disciple**|600 / 5,280+|60,000+ / 266+|50,000+ / 222+|250,000+|250,000–1M+|<5|95–100|
