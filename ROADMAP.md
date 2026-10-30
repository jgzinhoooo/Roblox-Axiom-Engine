# Axiom Engine — Development Roadmap

> **Planning document, not a release promise.** Axiom Engine is maintained in free time alongside work, school, and personal responsibilities. Updates may be irregular.

## Current priority: Blender → Roblox Studio

Enable AI agents to model complex 3D assets in Blender, transfer them into Roblox Studio through a supported workflow, identify their intended location, and place them correctly.

### Planned stages
1. **Blender modeling:** generate a test house using a Python script.
2. **Export compatibility:** establish units, pivot/origin, axis conventions, geometry and material handling.
3. **Studio import research:** test supported import workflows and identify any manual steps.
4. **Import bridge:** coordinate file transfer/import with meaningful errors and retries.
5. **Scene awareness:** find the intended terrain region or reference object.
6. **Smart placement:** adjust scale, rotation, elevation, and pivot; detect intersections.
7. **Validation:** confirm the model appears correctly and provide safe retry/rollback.
8. **Efficiency:** measure AI request/credit usage against Part-by-Part construction.

### First milestone
Given a request to build a simple house at a specified location, the agent generates it in Blender and places it accurately in Roblox Studio with as little manual intervention as the supported tools allow.

**Status:** Research and planning. Automated import and placement are not yet confirmed.

## Other long-term goals
- AI-assisted Luau scripting and debugging.
- Efficient context sharing and targeted operations.
- Coordination between AI agents.
- Reliable native Roblox Studio construction.

Progress and priorities may change as technical feasibility is tested.
