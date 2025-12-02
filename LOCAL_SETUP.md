# 🔙 Local Development Directory Structure

This shows how the project is organized on my local machine:

1. Ollama
   `C:/Users/username/AppData/Local/Programs/Ollama`

2. Linux/Ubuntu (WSL2)
   `/home/username/run_nemo.sh`
   `/home/username/miniconda3`
   `/home/username/ollama_bridge.py`

3. Custom model files
   `C:/Users/username/OneDrive/Desktop/modelfile`
   - ask_ollama.bat
   - Modelfile
   - my.txt
   - ollama.json
   - python-clientsscriptsttstalk

4. NeMo TTS scripts & models
   `D:/Users/username/Documents/Visual Studio Code Projects/tts_en_multispeaker_fastpitchhifigan`
   - audio.wav
   - tts_en_fastpitch_multispeaker.nemo
   - tts_en_hifitts_hifigan_ft_fastpitch.nemo
   - tts_inference.py
   - tts_runner.py

5. Unreal Engine 5 Project
   - Content/
   - Scripts/

## ⚙️ External Dependencies

Some components are not included in the main repo due to size or licensing restrictions.  
You can download and extract them into the `ExternalDependencies` folder.

1. **NeMo TTS Models**  
   - File: `tts_models.7z`  
   - Path after extraction: `ExternalDependencies/tts_en_multispeaker_fastpitchhifigan/`  

2. **Custom Ollama Character Models**  
   - File: `custom_models.7z`  
   - Path after extraction: `ExternalDependencies/Modelfile/`  
