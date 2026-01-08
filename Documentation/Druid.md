# Normal

## Key Q ✅

### Spell-stance table:

- :crossed_swords:     Balance     *spec:1*
```ts
╔═══╦═════════════╦═══════════════╗
║ 1 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ Sunfire       ║──┐
║ 1 ║ Bear        ║ Mangle        ║─┐│
║ 3 ║ Cat         ║ Mangle        ║─┘│
║ 5 ║ Moonkin     ║ Sunfire       ║──┘
╚═══╩═════════════╩═══════════════╝
```

- :leaves:     Restoration     *spec:2*
```ts
╔═══╦═════════════╦═══════════════╗
║ 1 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ Rejuvenation  ║
║ 1 ║ Bear        ║ Mangle        ║─┐
║ 3 ║ Cat         ║ Mangle        ║─┘
╚═══╩═════════════╩═══════════════╝
```

**Macro**:
```powershell
#showtooltip

/cast [spec:1,stance:1/3] Mangle; [spec:1,stance:0/5] Sunfire;

/cast [spec:2,stance:0] Rejuvenation; [spec:2,stance:1/3] Mangle;
```

## Key E ✅

### Spell-stance table:

- :crossed_swords:     Balance     *spec:1*
```ts
╔═══╦═════════════╦═══════════════╗
║ 1 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ Moonfire      ║─┐
║ 1 ║ Bear        ║ Maul          ║ │
║ 3 ║ Cat         ║ Rake          ║ │
║ 5 ║ Moonkin     ║ Moonfire      ║─┘
╚═══╩═════════════╩═══════════════╝
```

- :leaves:     Restoration     *spec:2*
```ts
╔═══╦═════════════╦═══════════════╗
║   ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ Regrowth      ║
║ 1 ║ Bear        ║ Maul          ║
║ 3 ║ Cat         ║ Rake          ║
╚═══╩═════════════╩═══════════════╝
```

Macro:
```powershell
#showtooltip

/cast [spec:1,stance:1] Maul; [spec:1,stance:3] Rake; [spec:1,stance:0/5] Moonfire;

/cast [spec:2,stance:0] Regrowth; [spec:2,stance:1] Maul; [spec:2,stance:3] Rake;
```

## Key R ✅

### Spell-stance table:

- :crossed_swords:     Balance     *spec:1*
```ts
╔═══╦═════════════╦═══════════════╗
║ 1 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ Starsurge     ║─┐
║ 1 ║ Bear        ║ ____          ║ │
║ 3 ║ Cat         ║ ____          ║ │
║ 5 ║ Moonkin     ║ Starsurge     ║─┘
╚═══╩═════════════╩═══════════════╝
```

- :leaves:     Restoration     *spec:2*
```ts
╔═══╦═════════════╦═══════════════╗
║   ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ ____          ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

Macro:
```powershell
#showtooltip

/cast [spec:1,stance:1]  ____; [spec:1,stance:3] ____; [spec:1,stance:0/5] Starsurge;

/cast [spec:2,stance:0] ____; [spec:2,stance:1] ____; [spec:2,stance:3] ____;
```

## Key F ✅

### Spell-stance table:

- :crossed_swords:     Balance     *spec:1*
```ts
╔═══╦═════════════╦═══════════════╗
║ 1 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ Rejuvenation  ║─┐
║ 1 ║ Bear        ║ ____          ║ │
║ 3 ║ Cat         ║ ____          ║ │
║ 5 ║ Moonkin     ║ Rejuvenation  ║─┘
╚═══╩═════════════╩═══════════════╝
```

- :leaves:     Restoration     *spec:2*
```ts
╔═══╦═════════════╦═══════════════╗
║ 2 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ Swiftmend     ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

Macro:
```powershell
#showtooltip

/cast [spec:1,stance:1] ____; [spec:1,stance:3] ____; [spec:1,stance:0/5] Rejuvenation;

/cast [spec:2,stance:0] Swiftmend; [spec:2,stance:1] ____; [spec:2,stance:3] ____;
```

## Key Tab ⚠️

### Spell-stance table:

- :crossed_swords:     Balance     *spec:1*
```ts
╔═══╦═════════════╦═══════════════╗
║ 1 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ ____          ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
║ 5 ║ Moonkin     ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

- :leaves:     Restoration     *spec:2*
```ts
╔═══╦═════════════╦═══════════════╗
║ 2 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ ____          ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

Macro:
```powershell
#showtooltip

/cast [spec:1,stance:1] ____; [spec:1,stance:3] ____; [spec:1,stance:0/5] ____;

/cast [spec:2,stance:0] ____; [spec:2,stance:1] ____; [spec:2,stance:3] ____;
```

## Key Caps Lock ⚠️

### Spell-stance table:

- :crossed_swords:     Balance     *spec:1*
```ts
╔═══╦═════════════╦═══════════════╗
║ 1 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ ____          ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
║ 5 ║ Moonkin     ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

- :leaves:     Restoration     *spec:2*
```ts
╔═══╦═════════════╦═══════════════╗
║ 2 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ ____          ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

Macro:
```powershell
#showtooltip

/cast [spec:1,stance:1] ____; [spec:1,stance:3] ____; [spec:1,stance:0/5] ____;

/cast [spec:2,stance:0] ____; [spec:2,stance:1] ____; [spec:2,stance:3] ____;
```

## Key Mouse 1 ⚠️

### Spell-stance table:

- :crossed_swords:     Balance     *spec:1*
```ts
╔═══╦═════════════╦═══════════════╗
║ 1 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ ____          ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
║ 5 ║ Moonkin     ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

- :leaves:     Restoration     *spec:2*
```ts
╔═══╦═════════════╦═══════════════╗
║ 2 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ ____          ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

Macro:
```powershell
#showtooltip

/cast [spec:1,stance:1] ____; [spec:1,stance:3] ____; [spec:1,stance:0/5] ____;

/cast [spec:2,stance:0] ____; [spec:2,stance:1] ____; [spec:2,stance:3] ____;
```

## Key Mouse 4 ⚠️

### Spell-stance table:

- :crossed_swords:     Balance     *spec:1*
```ts
╔═══╦═════════════╦═══════════════╗
║ 1 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ ____          ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
║ 5 ║ Moonkin     ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

- :leaves:     Restoration     *spec:2*
```ts
╔═══╦═════════════╦═══════════════╗
║ 2 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ ____          ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

Macro:
```powershell
#showtooltip

/cast [spec:1,stance:1] ____; [spec:1,stance:3] ____; [spec:1,stance:0/5] ____;

/cast [spec:2,stance:0] ____; [spec:2,stance:1] ____; [spec:2,stance:3] ____;
```

## Key Mouse 3 ⚠️

### Spell-stance table:

- :crossed_swords:     Balance     *spec:1*
```ts
╔═══╦═════════════╦═══════════════╗
║ 1 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ ____          ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
║ 5 ║ Moonkin     ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

- :leaves:     Restoration     *spec:2*
```ts
╔═══╦═════════════╦═══════════════╗
║ 2 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ ____          ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

Macro:
```powershell
#showtooltip

/cast [spec:1,stance:1] ____; [spec:1,stance:3] ____; [spec:1,stance:0/5] ____;

/cast [spec:2,stance:0] ____; [spec:2,stance:1] ____; [spec:2,stance:3] ____;
```

## Key Mouse 6 ⚠️

### Spell-stance table:

- :crossed_swords:     Balance     *spec:1*
```ts
╔═══╦═════════════╦═══════════════╗
║ 1 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ ____          ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
║ 5 ║ Moonkin     ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

- :leaves:     Restoration     *spec:2*
```ts
╔═══╦═════════════╦═══════════════╗
║ 2 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ ____          ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

Macro:
```powershell
#showtooltip

/cast [spec:1,stance:1] ____; [spec:1,stance:3] ____; [spec:1,stance:0/5] ____;

/cast [spec:2,stance:0] ____; [spec:2,stance:1] ____; [spec:2,stance:3] ____;
```

# Alt

## Key Alt-Q ✅

### Spell-stance table:

- :crossed_swords:     Balance     *spec:1*
```ts
╔═══╦═════════════╦═══════════════╗
║ 1 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ Wrath         ║─┐
║ 1 ║ Bear        ║ Growl         ║ |
║ 3 ║ Cat         ║ Swipe         ║ |
║ 5 ║ Moonkin     ║ Wrath         ║─┘
╚═══╩═════════════╩═══════════════╝
```

- :leaves:     Restoration     *spec:2*
```ts
╔═══╦═════════════╦═══════════════╗
║ 2 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ Nourish       ║
║ 1 ║ Bear        ║ Growl         ║
║ 3 ║ Cat         ║ Swipe         ║
╚═══╩═════════════╩═══════════════╝
```

Macro:
```powershell
#showtooltip

/cast [spec:1,stance:1] Growl; [spec:1,stance:3] Swipe; [spec:1,stance:0/5] Wrath;

/cast [spec:2,stance:0] Nourish; [spec:2,stance:1] Growl; [spec:2,stance:3] Swipe;
```

## Key Alt-E ✅

### Spell-stance table:

- :crossed_swords:     Balance     *spec:1*
```ts
╔═══╦═════════════╦════════════════╗
║ 1 ║ Stance Name ║ Spell          ║
╠═══╬═════════════╬════════════════╣
║ 0 ║ Default     ║ Starfire       ║
║ 1 ║ Bear        ║ Swipe          ║
║ 3 ║ Cat         ║ Ferocious Bite ║
║ 5 ║ Moonkin     ║ Starfire       ║
╚═══╩═════════════╩════════════════╝
```

- :leaves:     Restoration     *spec:2*
```ts
╔═══╦═════════════╦════════════════╗
║ 2 ║ Stance Name ║ Spell          ║
╠═══╬═════════════╬════════════════╣
║ 0 ║ Default     ║ Healing Touch  ║
║ 1 ║ Bear        ║ Swipe          ║
║ 3 ║ Cat         ║ Ferocious Bite ║
╚═══╩═════════════╩════════════════╝
```

Macro:
```powershell
#showtooltip

/cast [spec:1,stance:1] Swipe; [spec:1,stance:3] Ferocious Bite; [spec:1,stance:0/5] Starfire;

/cast [spec:2,stance:0] Healing Touch; [spec:2,stance:1] Swipe; [spec:2,stance:3] Ferocious Bite;
```

## Key Alt-R ⚠️

### Spell-stance table:

- :crossed_swords:     Balance     *spec:1*
```ts
╔═══╦═════════════╦═══════════════╗
║ 1 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ ____          ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
║ 5 ║ Moonkin     ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

- :leaves:     Restoration     *spec:2*
```ts
╔═══╦═════════════╦═══════════════╗
║ 2 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ ____          ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

Macro:
```powershell
#showtooltip

/cast [spec:1,stance:1] ____; [spec:1,stance:3] ____; [spec:1,stance:0/5] ____;

/cast [spec:2,stance:0] ____; [spec:2,stance:1] ____; [spec:2,stance:3] ____;
```

## Key Alt-F ⚠️

### Spell-stance table:

- :crossed_swords:     Balance     *spec:1*
```ts
╔═══╦═════════════╦═══════════════╗
║ 1 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ ____          ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
║ 5 ║ Moonkin     ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

- :leaves:     Restoration     *spec:2*
```ts
╔═══╦═════════════╦═══════════════╗
║ 2 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ ____          ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

Macro:
```powershell
#showtooltip

/cast [spec:1,stance:1] ____; [spec:1,stance:3] ____; [spec:1,stance:0/5] ____;

/cast [spec:2,stance:0] ____; [spec:2,stance:1] ____; [spec:2,stance:3] ____;
```

## Key Alt-Mouse Wheel Down ⚠️

### Spell-stance table:

- :crossed_swords:     Balance     *spec:1*
```ts
╔═══╦═════════════╦═══════════════╗
║ 1 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ ____          ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
║ 5 ║ Moonkin     ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

- :leaves:     Restoration     *spec:2*
```ts
╔═══╦═════════════╦═══════════════╗
║ 2 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ ____          ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

Macro:
```powershell
#showtooltip

/cast [spec:1,stance:1] ____; [spec:1,stance:3] ____; [spec:1,stance:0/5] ____;

/cast [spec:2,stance:0] ____; [spec:2,stance:1] ____; [spec:2,stance:3] ____;
```

## Key Alt-Mouse Wheel Up ⚠️

### Spell-stance table:

- :crossed_swords:     Balance     *spec:1*
```ts
╔═══╦═════════════╦═══════════════╗
║ 1 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ ____          ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
║ 5 ║ Moonkin     ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

- :leaves:     Restoration     *spec:2*
```ts
╔═══╦═════════════╦═══════════════╗
║ 2 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ ____          ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

Macro:
```powershell
#showtooltip

/cast [spec:1,stance:1] ____; [spec:1,stance:3] ____; [spec:1,stance:0/5] ____;

/cast [spec:2,stance:0] ____; [spec:2,stance:1] ____; [spec:2,stance:3] ____;
```

## Key Alt-Mouse 1 ⚠️

### Spell-stance table:

- :crossed_swords:     Balance     *spec:1*
```ts
╔═══╦═════════════╦═══════════════╗
║ 1 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ ____          ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
║ 5 ║ Moonkin     ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

- :leaves:     Restoration     *spec:2*
```ts
╔═══╦═════════════╦═══════════════╗
║ 2 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ ____          ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

Macro:
```powershell
#showtooltip

/cast [spec:1,stance:1] ____; [spec:1,stance:3] ____; [spec:1,stance:0/5] ____;

/cast [spec:2,stance:0] ____; [spec:2,stance:1] ____; [spec:2,stance:3] ____;
```

## Key Alt-Mouse 4 ⚠️

### Spell-stance table:

- :crossed_swords:     Balance     *spec:1*
```ts
╔═══╦═════════════╦═══════════════╗
║ 1 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ ____          ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
║ 5 ║ Moonkin     ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

- :leaves:     Restoration     *spec:2*
```ts
╔═══╦═════════════╦═══════════════╗
║ 2 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ ____          ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

Macro:
```powershell
#showtooltip

/cast [spec:1,stance:1] ____; [spec:1,stance:3] ____; [spec:1,stance:0/5] ____;

/cast [spec:2,stance:0] ____; [spec:2,stance:1] ____; [spec:2,stance:3] ____;
```

## Key Alt-Mouse 3 ⚠️

### Spell-stance table:

- :crossed_swords:     Balance     *spec:1*
```ts
╔═══╦═════════════╦═══════════════╗
║ 1 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ ____          ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
║ 5 ║ Moonkin     ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

- :leaves:     Restoration     *spec:2*
```ts
╔═══╦═════════════╦═══════════════╗
║ 2 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ ____          ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

Macro:
```powershell
#showtooltip

/cast [spec:1,stance:1] ____; [spec:1,stance:3] ____; [spec:1,stance:0/5] ____;

/cast [spec:2,stance:0] ____; [spec:2,stance:1] ____; [spec:2,stance:3] ____;
```

## Key Alt-Mouse 6 ⚠️

### Spell-stance table:

- :crossed_swords:     Balance     *spec:1*
```ts
╔═══╦═════════════╦═══════════════╗
║ 1 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ ____          ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
║ 5 ║ Moonkin     ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

- :leaves:     Restoration     *spec:2*
```ts
╔═══╦═════════════╦═══════════════╗
║ 2 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ ____          ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

Macro:
```powershell
#showtooltip

/cast [spec:1,stance:1] ____; [spec:1,stance:3] ____; [spec:1,stance:0/5] ____;

/cast [spec:2,stance:0] ____; [spec:2,stance:1] ____; [spec:2,stance:3] ____;
```



# Shift

## Key Shift-Q ✅

### Spell-stance table:

- :crossed_swords:     Balance     *spec:1*
```ts
╔═══╦═════════════╦═══════════════╗
║ 1 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ Faerie Fire   ║─┐
║ 1 ║ Bear        ║ ____          ║ |
║ 3 ║ Cat         ║ ____          ║ |
║ 5 ║ Moonkin     ║ Faerie Fire   ║─┘
╚═══╩═════════════╩═══════════════╝
```

- :leaves:     Restoration     *spec:2*
```ts
╔═══╦═════════════╦═══════════════╗
║ 2 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ Faerie Fire   ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

Macro:
```powershell
#showtooltip

/cast [spec:1,stance:1] ____; [spec:1,stance:3] ____; [spec:1,stance:0/5] Faerie Fire;

/cast [spec:2,stance:0] Faerie Fire; [spec:2,stance:1] ____; [spec:2,stance:3] ____;
```

## Key Shifl-E ⚠️

### Spell-stance table:

- :crossed_swords:     Balance     *spec:1*
```ts
╔═══╦═════════════╦═══════════════╗
║ 1 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ ____          ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
║ 5 ║ Moonkin     ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

- :leaves:     Restoration     *spec:2*
```ts
╔═══╦═════════════╦═══════════════╗
║ 2 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ ____          ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

Macro:
```powershell
#showtooltip

/cast [spec:1,stance:1] ____; [spec:1,stance:3] ____; [spec:1,stance:0/5] ____;

/cast [spec:2,stance:0] ____; [spec:2,stance:1] ____; [spec:2,stance:3] ____;
```

## Key Shifl-R ⚠️

### Spell-stance table:

- :crossed_swords:     Balance     *spec:1*
```ts
╔═══╦═════════════╦═══════════════╗
║ 1 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ ____          ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
║ 5 ║ Moonkin     ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

- :leaves:     Restoration     *spec:2*
```ts
╔═══╦═════════════╦═══════════════╗
║ 2 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ ____          ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

Macro:
```powershell
#showtooltip

/cast [spec:1,stance:1] ____; [spec:1,stance:3] ____; [spec:1,stance:0/5] ____;

/cast [spec:2,stance:0] ____; [spec:2,stance:1] ____; [spec:2,stance:3] ____;
```

## Key Shifl-F ⚠️

### Spell-stance table:

- :crossed_swords:     Balance     *spec:1*
```ts
╔═══╦═════════════╦═══════════════╗
║ 1 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ ____          ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
║ 5 ║ Moonkin     ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

- :leaves:     Restoration     *spec:2*
```ts
╔═══╦═════════════╦═══════════════╗
║ 2 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ ____          ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

Macro:
```powershell
#showtooltip

/cast [spec:1,stance:1] ____; [spec:1,stance:3] ____; [spec:1,stance:0/5] ____;

/cast [spec:2,stance:0] ____; [spec:2,stance:1] ____; [spec:2,stance:3] ____;
```

# Ctrl

## Key Ctrl-Q ⚠️

### Spell-stance table:

- :crossed_swords:     Balance     *spec:1*
```ts
╔═══╦═════════════╦═══════════════╗
║ 1 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ ____          ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
║ 5 ║ Moonkin     ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

- :leaves:     Restoration     *spec:2*
```ts
╔═══╦═════════════╦═══════════════╗
║ 2 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ ____          ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

Macro:
```powershell
#showtooltip

/cast [spec:1,stance:1] ____; [spec:1,stance:3] ____; [spec:1,stance:0/5] ____;

/cast [spec:2,stance:0] ____; [spec:2,stance:1] ____; [spec:2,stance:3] ____;
```

## Key Ctrl-E ⚠️

### Spell-stance table:

- :crossed_swords:     Balance     *spec:1*
```ts
╔═══╦═════════════╦═══════════════╗
║ 1 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ ____          ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
║ 5 ║ Moonkin     ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

- :leaves:     Restoration     *spec:2*
```ts
╔═══╦═════════════╦═══════════════╗
║ 2 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ ____          ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

Macro:
```powershell
#showtooltip

/cast [spec:1,stance:1] ____; [spec:1,stance:3] ____; [spec:1,stance:0/5] ____;

/cast [spec:2,stance:0] ____; [spec:2,stance:1] ____; [spec:2,stance:3] ____;
```

## Key Ctrl-R ⚠️

### Spell-stance table:

- :crossed_swords:     Balance     *spec:1*
```ts
╔═══╦═════════════╦═══════════════╗
║ 1 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ ____          ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
║ 5 ║ Moonkin     ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

- :leaves:     Restoration     *spec:2*
```ts
╔═══╦═════════════╦═══════════════╗
║ 2 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ ____          ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

Macro:
```powershell
#showtooltip

/cast [spec:1,stance:1] ____; [spec:1,stance:3] ____; [spec:1,stance:0/5] ____;

/cast [spec:2,stance:0] ____; [spec:2,stance:1] ____; [spec:2,stance:3] ____;
```

## Key Ctrl-F ⚠️

### Spell-stance table:

- :crossed_swords:     Balance     *spec:1*
```ts
╔═══╦═════════════╦═══════════════╗
║ 1 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ ____          ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
║ 5 ║ Moonkin     ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

- :leaves:     Restoration     *spec:2*
```ts
╔═══╦═════════════╦═══════════════╗
║ 2 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ ____          ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

Macro:
```powershell
#showtooltip

/cast [spec:1,stance:1] ____; [spec:1,stance:3] ____; [spec:1,stance:0/5] ____;

/cast [spec:2,stance:0] ____; [spec:2,stance:1] ____; [spec:2,stance:3] ____;
```


# DEFAULT EMPTY ⚠️

### Spell-stance table:

- :crossed_swords:     Balance     *spec:1*
```ts
╔═══╦═════════════╦═══════════════╗
║ 1 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ ____          ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
║ 5 ║ Moonkin     ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

- :leaves:     Restoration     *spec:2*
```ts
╔═══╦═════════════╦═══════════════╗
║ 2 ║ Stance Name ║ Spell         ║
╠═══╬═════════════╬═══════════════╣
║ 0 ║ Default     ║ ____          ║
║ 1 ║ Bear        ║ ____          ║
║ 3 ║ Cat         ║ ____          ║
╚═══╩═════════════╩═══════════════╝
```

Macro:
```powershell
#showtooltip

/cast [spec:1,stance:1] ____; [spec:1,stance:3] ____; [spec:1,stance:0/5] ____;

/cast [spec:2,stance:0] ____; [spec:2,stance:1] ____; [spec:2,stance:3] ____;
```
