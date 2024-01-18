
So, my current plan is to do this w.r.t some very legitimate sites I'm reading from.

Basically:

Loop this every so often / when our screen is scrolled down a bit (and new content is found)
{
Grab the current screen and read its content
If there's new shit, send it to an LLM.
This LLM breaks down this text into scenes as required / "Convert to be suitable for prompts for a stable diffusion model to produce manga panels"
Get resulting response, throw it into an image gen stable diffuser thing. Boom.
}

A wiki should be made aswell for keywords (like main characters) which could then be replaced in the screen-grabbed text to be a trait list of this person. E.g our main character John becomes "John jumps up" <=> "A tall muscular man, with long hair and an affinity to shadows jumps up"


These are the core features.

Extra features would be to somehow do LORA or whatever (research into it) for this wiki section, so we get consistently the same characters in different environments.




TODOs are in a project on this repo, trying out Kanban boards!