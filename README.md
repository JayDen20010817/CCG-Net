# 🤣👉CCG-Net👈
<p align="center">
<img src="introduction.png" width="400 height="400">
</p>

## 🔥Overview
<p align="center">
  <img src="framework.png" width="900 height="900"
</p>

## 📣Quick start:
- Place the text, audio, and video feature files in the format as described above in the following manner in the 'Data' folder:
WITS Dataset_link：https://github.com/LCS2-IIITD/MAF <br />
  - Data
    - Text
      - train_text.json
      - val_text.json
      - test_text.json
    - Audio
      - train_audio.p
      - val_audio.p
      - test_audio.p
    - Video
      - train_video.p
      - val_video.p
      - test_video.p<br />

  MUStARD Dataset_link:<br />
  -**Text data** - It is available at https://github.com/soujanyaporia/MUStARD in data/sarcasm_data.json location. We also provide train, valid and text dlog ids with them. <br />
  -**Audio data** - We first obtain raw video from https://github.com/soujanyaporia/MUStARD and convert those videos to audio format corresponding to the last utterance   of every dialog. The we proceed to obtain audio features in the same manner 	as described in https://github.com/thuiar/MIntRec/tree/main/tools/audio_preprocess.py <br />
  -**Video data** - We get raws videos from https://github.com/soujanyaporia/MUStARD and obtain the video features corresponding to last utterance from https://github.com/soujanyaporia/MUStARD under Run the code section point 3 Download the pre-		extracted visual features. <br />

- Subsequent install the dependencies mentioned in the requirement.txt. <br />
- Finally run model_driver.py file 
    

    
