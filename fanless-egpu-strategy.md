# Fanless + External GPU Strategy

## The Perfect Combination

1. **Silent daily driver**: Fanless system for 95% of tasks
2. **On-demand power**: eGPU via TB/OCuLink when needed
3. **Acoustic isolation**: GPU noise in separate enclosure
4. **Thermal separation**: Heat sources physically separated

## Implementation Approaches

### Thunderbolt Native
- Motherboard: ASRock Z790 PG-ITX/TB4
- CPU: Intel i5-13400T (35W TDP)
- Chassis: HDPLEX H3
- eGPU: Via TB4 when needed

### OCuLink Integration
- Board: AsRock X570D4I-2T (OCuLink header)
- CPU: AMD 5700G (65W cTDP)
- Direct OCuLink to external GPU
- 64 Gbps bandwidth, zero fan noise

### Hybrid Approach
- Fanless low-profile GPU (RTX A2000)
- External high-end GPU for demanding tasks
- Best of both worlds

## Best Practices

### Thermal Management
1. **Keep fanless system minimal**: Don't push TDP limits
2. **Offload heavy compute**: Use eGPU for demanding tasks
3. **Storage over network**: NAS for bulk storage
4. **Modular approach**: Easy to upgrade external components

### Cable Management
- **OCuLink**: Shortest cable possible (heat)
- **Thunderbolt**: Active cables for distance
- **Power**: Separate circuits for eGPU
- **Organization**: Clean routing maintains airflow