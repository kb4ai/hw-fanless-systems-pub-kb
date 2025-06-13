# Thermal Design Guide for Fanless Systems

## CPU Selection by TDP

| TDP Class | Recommended CPUs | Use Case |
|-----------|------------------|----------|
| 15W | Intel U-series, AMD U | Ultra-silent office |
| 35W | Intel T-series, AMD GE | Balanced performance |
| 65W | Ryzen 7000 eco mode | Development work |
| 85W+ | i7/i9 undervolted | Professional workloads |

## Passive Cooling Principles

### Convection Optimization
- **Vertical fins**: Better natural airflow
- **Chimney effect**: Bottom intake, top exhaust
- **Spacing**: Adequate fin separation
- **Orientation**: Vertical mounting preferred

### Heat Transfer
- **Conduction**: CPU → Base → Heatpipes → Fins
- **Radiation**: Blackened surfaces help
- **Convection**: Natural air movement
- **Surface area**: More fins = better cooling

## Thermal Interface Materials

### Recommended TIMs
1. **Thermal Grizzly Kryonaut**: Best non-conductive
2. **Liquid Metal**: For extreme performance
3. **Graphite pads**: Reusable, consistent
4. **Phase change**: Good for long-term

### Application Tips
- Thin, even layer
- Full die coverage
- No air bubbles
- Replace annually

## Environmental Factors

### Room Conditions
- **Ambient temp**: Every °C matters
- **Airflow**: Even minimal helps
- **Humidity**: Affects convection
- **Altitude**: Thinner air = less cooling

### Placement
- Away from walls
- Not in enclosed spaces
- Elevated from floor
- Clear top ventilation

## Monitoring & Safety

### Temperature Targets
- **Idle**: <50°C
- **Load**: <80°C
- **Throttle**: >90°C
- **Shutdown**: >105°C

### Monitoring Tools
- HWiNFO64 (Windows)
- lm-sensors (Linux)
- Intel XTU
- AMD Ryzen Master