# AI Pet Video Serial Production

## Confirm one segment before you batch

- Plan each segment at about 10 seconds and plan one shot per segment.

- Generate one segment first and send the user its playable link, then wait for confirmation that the link opens and plays and that the look is right.

- Generate the remaining segments only after that confirmation.

- Before you regenerate the same video, report the new plan and the exact prompt changes and wait for the user to confirm them.

- Try a non-generative fix first when the fault is edit level, and name the generation cost before you generate again.

## Anchor every character and check the brief

- For any shot with a human, feed that human character design sheet and never generate the shot from text alone.

- Crop the four view medium shot to landscape and use that crop as the anchor image when the intended output is landscape.

- Compare the face, hair, head ornament, clothing colour and clothing pattern in the delivery against the character design sheet before you deliver it, and name any mismatch plainly before you offer a regeneration.

- Write the user brief as a short checklist before you generate, and cover pack size and count, eye colour, left and right positions, character eye colour, fur cleanliness and picture brightness.

- Compare the delivered segment against that checklist point by point before you deliver it, and name any miss plainly instead of presenting the segment as finished.

- Compare the left and right positions in the new segment with the matching shot in the earlier episode, and keep the home side and the threat side the same unless the user asks for a change.

- Check each animal against its three view reference for face, eye colour, fur colour and fur cleanliness, and lock the eye colour and the ear shape in the prompt for the next version when either one drifts.

## Check sound before you deliver

- Listen to the delivered track before you deliver it and confirm that ambient sound is present and that no human voice is present.

- Keep livestock sound occasional and distant and at low volume, and never let it run loud and continuous through the shot.

- Never deliver a silent track after you remove a voice, and fix a sound fault by editing the existing track when editing can fix it.

## Cut hard and keep the camera still

- Tell the story with hard cuts, with one shot size in each segment, and change shot size only by cutting to the next segment.

- Keep the camera fixed or use only a very slow micro move, and do not ask for a push, a pull or a one take.

- Do not use a fast continuous move to cover several shot sizes in one clip.

- Check that the camera speed and the cuts in the delivery follow the prompt, and name the mismatch before you offer a regeneration.

## Check picture quality and present the result

- Ask for fur with separate visible strands and roots when the animal is close to camera, and reject smooth whole piece fur.

- Check the delivered resolution and aspect ratio against the intended one before you deliver, name the intended size in the plan such as 1280x720 landscape, and reject a delivery that arrives in a different size.

- Do not feed a vertical reference photo when the intended output is landscape, because a vertical photo can pull the output to portrait and weaken the camera directions in the prompt.

- Give the user the playable link, the segment number and the shot it covers, and name the expiry time of a link when you know it.

- If a segment fails, explain the cause in one short sentence and offer one concrete retry.

## Available connectors

- Use `muse.connector_search` to find other connectors and `muse.skill_search` to find related skills.

- If nothing here fits, look on the web for a maintained API or MCP server and set it up with [Custom Connectors and MCPs](/opt/muse/skills/custom-connector-setup/SKILL.md), or build a custom connector.

## Alternatives for better results

- Cut one shot per segment in an editor instead of asking for several cuts inside one 10 second clip.

- Use a still reference pack for the characters and the room before you generate a new episode, and reuse a proven shot layout from an earlier episode when the new episode needs the same action.

- Reuse the last seconds of a proven earlier segment as the opening cut when the new segment continues the same moment, and generate only the shots that add new action.
