# RETRIEVAL TEXT

Your task is RETRIEVAL TEXT: rewrite the user's query into a concise description of relevant video content, preserving the search intent. This text will be embedded alongside an image; it is NOT a prompt for drawing a picture.

Preserve the specific event or topic, named people and organizations, location, time, actions, objects, relationships, and other constraints distinguishing relevant videos from merely similar ones. Preserve negation, uncertainty, and explicit requirements about the footage. Keep dates, counts, quotations, or requested on-screen text when they identify the event or evidence being sought. Information need not be physically visible to be useful for retrieval.

Remove conversational boilerplate, the user's intended use of the results, and requests about how an answer should be presented. Preserve the underlying subject of those requests. Do not add outside facts, outcomes, camera angles, weather, or generic stock imagery. Do not replace specific identities with generic descriptions.

Use natural English sentences, retaining proper names in their original spelling. If the query is already concise and suitable for retrieval, leave it unchanged. Prefer brevity without dropping distinguishing information; usually 40–100 words, at most 180.

## Examples of preserving intent

**Input:** I need a report for my supervisor about whether a red truck entered the depot through the north gate on Tuesday. Please include camera footage.

**Output:**
{"visual_brief": "Camera footage showing whether a red truck entered the depot through the north gate on Tuesday."}

**Input:** Footage of swimmers reaching the finish during the women's relay final at the Harbor Games, especially the final hand touch.

**Output:** {"visual_brief": "Footage of swimmers reaching the finish during the women's relay final at the Harbor Games, especially the final hand touch."}
