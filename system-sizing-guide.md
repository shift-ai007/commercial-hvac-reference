# Commercial HVAC Sizing Guide — South Florida

Proper sizing is the single most important decision in commercial HVAC. Undersized systems run constantly, overpay on energy, and fail early. Oversized systems short-cycle, leaving humidity uncontrolled — a critical problem in South Florida.

## Rule of Thumb vs. Manual J/N

### Residential Rule of Thumb (DO NOT use for commercial)
The "1 ton per 400 sq ft" rule is for residential only. Commercial spaces have wildly different heat loads based on occupancy, lighting, equipment, and envelope.

### Manual N (Commercial Load Calculation)
Always use ACCA Manual N or equivalent engineering software for commercial sizing. Key inputs:

| Factor | Why It Matters in South Florida |
|--------|-------------------------------|
| Outdoor design temp | Use 93°F dry-bulb / 79°F wet-bulb (ASHRAE 0.4% conditions for Miami) |
| Roof type and color | Dark flat roofs = massive solar gain. Cool roofing reduces load by 20-25% |
| Glass area and type | East/west-facing glass is brutal. Low-E glazing cuts solar gain by 40-60% |
| Occupancy density | Restaurants: 15 sq ft/person. Offices: 150 sq ft/person. Huge difference |
| Lighting load | LED retrofit from fluorescent can reduce cooling load by 10-15% |
| Equipment heat | Server rooms, commercial kitchens, laundry — all major internal loads |
| Ventilation requirement | Florida code requires more outside air than most states (high humidity = high latent load) |

## Sizing by Building Type

These are rough ranges for South Florida. Always verify with a load calculation.

| Building Type | Tons per 1,000 sq ft | Notes |
|--------------|---------------------|-------|
| Standard office | 3.0-4.0 | Low internal loads, moderate glass |
| Medical office | 3.5-5.0 | Higher ventilation, sterilization equipment |
| Retail (open floor) | 3.5-4.5 | High glass, door traffic, variable occupancy |
| Restaurant | 5.0-8.0 | Kitchen exhaust, high occupancy, cooking equipment |
| Warehouse | 1.5-2.5 | High ceiling, minimal occupancy, often spot cooling only |
| Server room | 8.0-15.0+ | 24/7 cooling, precision required, redundancy mandatory |
| Church/Assembly | 3.5-5.0 | Variable occupancy, peak on weekends only |
| Grocery store | 4.0-6.0 | Refrigeration cases add heat, high door traffic |

## Latent vs. Sensible Load

In South Florida, latent load (humidity removal) is often 30-40% of total load. National averages assume 20-25%. This matters because:

1. **Oversized systems short-cycle**: They cool the air (sensible) before removing enough moisture (latent), leaving the space clammy at 72°F
2. **Dehumidification requires runtime**: The evaporator coil needs sustained contact with air to condense moisture. Short cycles don't achieve this
3. **Dedicated dehumidification may be needed**: For spaces with high latent loads (pools, commercial kitchens, large lobbies with frequent door openings), consider a separate dehumidification unit

### Sensible Heat Ratio (SHR)

Target SHR for South Florida:
- Office/retail: 0.65-0.75 (30-35% latent)
- Restaurant: 0.55-0.65 (35-45% latent)
- Lobby with frequent door opening: 0.50-0.60 (40-50% latent)
- Warehouse (minimal ventilation): 0.75-0.85 (15-25% latent)

## Redundancy Planning

Commercial systems should have redundancy. Florida heat means a failed system is an emergency.

| Building Type | Minimum Redundancy | Recommended |
|--------------|-------------------|-------------|
| Office | N+0 (single system OK if under 10 tons) | N+1 for critical spaces |
| Medical | N+1 mandatory | N+1 with auto-switchover |
| Data center | 2N (full redundancy) | 2N+1 with diversity |
| Restaurant | N+0 (accept downtime risk) | Portable spot cooler on standby |
| Retail | N+0 (single system) | Split into 2 zones for partial redundancy |

## Common Sizing Mistakes in South Florida

1. **Using national design temperatures**: Miami's outdoor design is 93°F, not 95°F — but humidity is the real issue. Use wet-bulb temps.
2. **Ignoring infiltration**: Frequent door openings (retail, restaurants) bring in 80°F/80% RH outside air that adds massive latent load
3. **Oversizing "just to be safe"**: A 20% oversized system will short-cycle, leaving humidity at 65%+ even though the thermostat reads 72°F
4. **Forgetting kitchen exhaust makeup air**: If a restaurant hood exhausts 3,000 CFM, that air must be replaced — and cooled/dehumidified
5. **Not accounting for future tenant changes**: Office build-outs often convert open space to high-density meeting rooms. Size for the worst case or install VRF for flexibility
