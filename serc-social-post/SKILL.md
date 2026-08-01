---
name: serc-social-post
description: Prompt template for creating SERC social media posts for Linda Nichols. Use this skill whenever Linda asks to create, draft, or write a social media post for Instagram, TikTok, or Facebook for Southeastern Reptile Conservation or @purringturtle or @southeastreptile. Ask the template questions before drafting. Always apply the linda-voice skill rules to the output.
---

# SERC Social Media Post Template

## How to use this skill

1. Ask Linda the questions below (all required except where noted)
2. Apply the linda-voice skill rules to produce the post
3. Default assumptions (do not ask about these):
   - Call to action: link in bio
   - Tone: educational with humor where it fits naturally
4. Output the post using the message_compose_v1 tool so Linda can copy it easily
5. If platform is Instagram or TikTok: max 5 lowercase hashtags
6. If platform is Facebook: no hashtags

---

## Template Questions

Ask these in a single message before drafting. Keep the prompts short and conversational.

**1. Who or what is this about?**
Name, species, and nickname if the finders gave one.

**2. What happened / what is this post about?**
The injury, situation, milestone, fundraiser, release, or topic.

**3. Where are they now in their story?**
Intake, in care, improving, pre-release, released, or other update.

**4. Any specific details to include?**
People or volunteers to thank, handles to tag, products or partners to mention, fundraising ask, or anything else that needs to be in the post.

**5. Which platform?**
Instagram, TikTok, or Facebook.

---

## Output Rules by Platform

Apply linda-voice skill rules. Quick reference:

| Platform | Length | Hashtags | CTA |
|---|---|---|---|
| Instagram | 3 to 5 short paragraphs | Max 5, lowercase | Link in bio |
| TikTok | 1 to 2 short paragraphs | Max 5, lowercase | Link in bio |
| Facebook | Longer form fine | None | Embed link if relevant |

---

## Quality Check Before Delivering

Before outputting the post, confirm:
- No em dashes or hyphens used as dashes
- Standard capitalization (not all lowercase)
- Hashtags are lowercase and within the limit for the platform
- No specific release sites or precise location names
- Opener earns the scroll
- Ending is grounded, warm, or lands a small dry punchline
- Link in bio assumed unless details said otherwise
