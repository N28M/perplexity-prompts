# perplexity-prompts

This repo stores the prompts for my custom perplexity spaces

## Using this repo

* Create a space in perplexity.
* Paste the prompt (e.g. resume-adjuster) in the instructions.
* Add the necessary files (e.g. resume, skills etc).
* Provide the input in the chat window for the agent to process it (e.g for resume-adjuster the JD goes into the chat box).

## Spaces

* *Resume Adjuster*
  * This space looks at the Job Description and uses the context from the resume and supplemental skills file to adjust the resume for the job. 
  * The agent generates an updated resume based on the provide context.
  * The agent also provides a skills match % before and after the adjustment.
  * Inputs
    * Resume
    * Skills.md
    * JD in the chat box
    * **Verify the generated resume as the agent sometimes still invents skills that you might have no idea about**
