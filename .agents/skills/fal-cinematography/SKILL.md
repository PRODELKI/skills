---
name: fal-cinematography
description: Plan and critique deliberate camera, blocking, lens, lighting and continuity for visual storytelling, including AI-animated family films. Use before image-to-video prompting and during shot review.
---

# fal / Cinematography — PRODELKI adaptation

This is an original, independently written operational adaptation of cinematography practice for production planning. It is not a copy of, or officially endorsed by, the fal.ai plugin skill.

## First, lock the scene

Confirm (1) the dramatic purpose of the shot, (2) what must happen visibly, (3) which characters and objects are present, (4) the duration and aspect ratio, (5) approved reference images, and (6) where the shot starts and ends. A pretty image with no narrative job does not pass.

## One shot = one visual event

Describe in this order:

1. **Action and stakes:** the observable change on screen, not a vague emotion.
2. **Blocking:** where each character begins, where they move, and what they touch.
3. **Framing:** wide/medium/close-up and eye line.
4. **Camera:** fixed, dolly-in, tracking, pan or tilt; choose one coherent motion.
5. **Lens and depth:** wide/normal/telephoto feel, focal plane, background behaviour.
6. **Lighting:** identify actual sources and their spatial relation to the characters.
7. **Continuity:** repeated face, wardrobe, body proportions, environment, lighting direction, props.
8. **Final state:** a precise composition or gesture that connects to the following shot.
9. **Failure constraints:** no extra fingers, duplicate people, drifting identity, floating props, camera jumps, unwanted text.

## Family-photo animation workflow

- Obtain consent before uploading recognisable photos, especially of children.
- Select one approved portrait or character sheet per person; separate sheets for distinct ages.
- Record face/hair/build and identifying visual anchors, consistent costume, and relative heights.
- Generate and approve **still keyframes** of all scenes before animating them.
- Animate from approved keyframes using image-to-video. Do not expect a prompt alone to preserve identity.
- Use one speaking character per shot when lip sync or facial fidelity is critical.
- Avoid heavy camera movement during dialogue or intimate close-ups.
- Review frames at 0%, 25%, 50%, 75%, 100% for identity drift, body and hand errors, motion discontinuity, accidental characters and scene mismatches.
- Regenerate only the failing shot and record why it failed. Do not overwrite approved shots.

## Shot manifest

| Field | Record |
| --- | --- |
| Shot | number + story beat |
| Length | planned seconds |
| Subject | who is visible |
| Identity anchors | approved photo/character reference IDs |
| Action | physical event in one sentence |
| Camera | framing + movement |
| Lighting | actual source + direction |
| First frame | approved image |
| Last frame | target end state |
| Audio | spoken text / offscreen narration / sound |
| Restrictions | what must not change |
| Review | accepted / retry + failure reason |

## Prompt template

> [Approved reference image and identity anchors.] [Shot number, narrative purpose.] [Subject and starting placement.] [Action over the clip.] [Framing and measured camera movement.] [Lighting and environment.] [End-state composition.] Keep all faces, wardrobe, relative sizes, props and room geometry consistent with the approved reference. No new people, facial morphing, extra limbs, abrupt camera cuts, or unintended captions.

## Quality gate

Reject a shot if it changes a family member's identity, breaks the scene geography, fails to show the intended action, adds unstable anatomy, or cannot cut naturally to the next shot. If the action is impossible within the clip duration, split it into two shots.

## Source and scope

Methodology: practical cinematography, shot continuity, and image-to-video prompting. The original fal.ai plugin also contains a separate Cinematography skill; this file is an independently authored PRODELKI adaptation for family films and does not grant model access or guarantee output quality.
