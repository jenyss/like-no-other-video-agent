# "Like No Other" Video Agent 

The "Like No Other" Video Agent is a tribute to human creativity and imagination. It’s inspired by three iconic ads that have stayed with me - evoking joy, awe, happiness, love, and compassion. Emotions… like no other.

We often speak of technology as if it will ultimately prevail. But at the end of the day, it is the result of our own boundless human potential and **no matter how magnificent the technology becomes, it will always lack one of life’s most profound forces: emotion**. 

**The "Like No Other" agent is designed to recreate your favourite commercial.** I gave it tools and let it be the Creative Director, Producer and Post Production Producer of the videos.

**This experiment quickly demonstrates why some jobs must be carried out only by trained professionals - and why you probably shouldn’t attempt them at home. Video production is still one of those things… unless you’re aiming for mediocre results (or have very low expectations!).**

The agent uses some of the best image, video and audio models available today and the Google ADK "think" function to plan its creative process and then execute it. But it all starts with an OpenAI Agent (with a search tool) powered by GPT-4o (my favourite), wrapped as a ADK tool, to research and structure information about your favourite ad:

* The Ad in a Nutshell
* The Scenes
* Why It Resonated
* The Music

Once that’s done, the agent decides which models to use, and in what sequence to bring the ad to life. It can go straight to text-to-video, or choose to first generate an image and then animate it. It gets to pick between different models… but guess which image and video tools a Google ADK Agent powered by Gemini would naturally prefer 😉 

So, to shake things up, feel free to comment out the Veo3 tool. You can also adjust the instructions to guide the agent when to give a preference to a specific model-tool. 

Video length is capped at 30 seconds (but you can generate longer ones, if you're willing to pay the price for a good laugh), just change the duration in the agent's instructions or let it decide itself (not advisable).

If you have any questions or would like to collaborate, feel free to reach out to me on [LinkedIn](https://www.linkedin.com/in/jenya-stoeva-60477249/). You're more than welcome!

## Agent Architecture

![like-no-other-video-agent](https://github.com/user-attachments/assets/49417ace-2f3f-49ea-924e-bae5f670933e)


## How-To

**Option 1:** Run in Colab
<br> _coming soon..._

**Option 2:** Run Locally
- Clone this repo and open the uploaded notebook in JupyterLab
- Create a .env file with your API keys:
  - ```OPENAI_API_KEY```
  - ```FAL_KEY```
  - ```GOOGLE_API_KEY```
- In the last notebook cell, enter your prompt. Then either run the notebook cells one by one, or choose “Run All Cells” from the Run menu. Make sure to check the provided example ```user_prompts```.
 
  
