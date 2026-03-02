![Nexa Screenshot](./assets/Banner.png)

# Nexa - Your On-the-Go ComfyUI Companion

A sleek, responsive android app that connects directly to your local ComfyUI server. Generate images from your phone, build dynamic UIs from JSON workflows, upload images to LoadImage nodes.

## What does it do?
Nexa completely changes how you interact with ComfyUI. Instead of dealing with the giant node spaghetti desktop interface when you just want to generate some images on the couch, Nexa turns your workflows into clean mobile forms. 

Just give it an workflow JSON file from ComfyUI, and it auto-detects your Prompts, Samplers, Loras, Checkpoints, and Images. It even lets you add custom magic variables (like `%trigger_word%`) so you can swap them instantly via sliders and text boxes!

## Features 
- **Auto-Detect Nodes**: Automatically maps Prompts, Models, Loras, and Image resolutions.
- **Node Reordering**: Easily change the order your text prompts and images show up in the app.
- **Image-to-Image Support**: Upload photos right from your phone's gallery directly to `LoadImage` nodes.
- **Custom Overrides**: Add your own custom variables like `%my_seed%` and hook them up to sliders or text inputs.
- **Native History Tab**: Browse past generations, view their settings (prompt, sampler info), and save/delete them.

## Screenshots

<p align="center">
  <img src="./Screenshots/2.jpg" width="18%" />
  <img src="./Screenshots/4.jpg" width="18%" />
  <img src="./Screenshots/5.jpg" width="18%" />
  <img src="./Screenshots/6.jpg" width="18%" />
  <img src="./Screenshots/7.jpg" width="18%" />
</p>


## How to use it 

1. **Setup your server**:
   Open a terminal and run your ComfyUI with the listen flag:
   `python main.py --listen`
   
2. **Open the App**:
   Go to the Settings tab in Nexa and type in your local IP plus the port (e.g. `192.168.1.100:8188`).
   
3. **Get your Workflow**:
   In your desktop ComfyUI settings, check the "Enable Dev mode Options" box. This adds a "Save (API format)" button. Build your workflow and click it!
   
4. **Import to Nexa**:
   Hit "+ Create New Workflow" in the app, paste the JSON you just downloaded, and press "Analyze for Auto-Detect". Watch it pull all your nodes automatically, then save it and start generating!

---
*This app is open source and free forever. If you want to help me keep updating it, please consider donating:*
- [Ko-fi (Buy me a coffee)](https://ko-fi.com/kasumaoniisan)
- **Crypto (LTC)**: `LSjf1DczHxs3GEbkoMmi1UWH2GikmXDtis`
