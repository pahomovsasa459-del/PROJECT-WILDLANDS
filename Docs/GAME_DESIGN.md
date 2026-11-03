# PROJECT: WILDLANDS — Game Design Document

## Vision
An original first-person 3D survival-adventure for Android, set on the fictional tropical island of Verdana. The goal is to balance immersive environments, responsive touch controls, and stable performance on mobile devices.

## Core pillars
- Exploration: dense jungle paths, mountain routes, abandoned buildings, small settlements, and hidden places.
- Story: after a plane crash, the protagonist searches for missing people and uncovers the activities of an organization known as Sector.
- Discovery: environmental clues, documents, landmarks, and optional locations gradually reveal the island's history.
- Mobile-first design: scalable graphics, readable interface, adjustable sensitivity, and performance testing on real devices.

## Setting
Verdana is a fictional island with several distinct regions:
- Coastal jungle and the crash site.
- Inland forest with streams and clearings.
- Mountain foothills and elevated viewpoints.
- Abandoned industrial and research locations.
- Small settlements connected by rough roads and footpaths.

## Story premise
The protagonist survives an aircraft crash on Verdana. Communication is unreliable and several people are missing. While exploring the island and following clues, the protagonist discovers that Sector has been operating in remote parts of the island. The story is told through encounters, locations, and environmental evidence.

## First playable prototype
The first milestone is deliberately small:
1. Create a Unity project using URP.
2. Build one compact jungle test area.
3. Add first-person movement and a mobile touch-control layout.
4. Add a simple interaction prompt and one inspectable story clue.
5. Add a basic pause/settings menu.
6. Test frame rate, memory use, loading, and touch response on the target Android device.

## Visual and technical direction
- Engine: Unity with Universal Render Pipeline (URP).
- Camera: first person.
- Art direction: grounded, atmospheric tropical realism; original assets and locations.
- Performance: use level-of-detail, occlusion, texture compression, baked lighting where appropriate, and adjustable quality settings.
- Scope: build and test a small vertical slice before expanding the island. The eventual install size depends on assets, audio, and build settings; the ~1 GB target is an aspiration, not a guarantee.

## Out of scope for the first prototype
- A full open world.
- Multiplayer.
- Complex vehicle systems.
- Final-quality cinematic sequences.
- A complete campaign.

## Milestones
- M1: project setup and Android build.
- M2: small test environment and player movement.
- M3: touch controls, interaction, and pause menu.
- M4: first story objective and performance pass.
- M5: expand the world only after the prototype is stable.

## Originality
PROJECT: WILDLANDS may take broad inspiration from open-world exploration games, but its characters, story, locations, interface, art, and implementation should be original.
