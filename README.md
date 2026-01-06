# How to install gemini-cli latestest version in Termux without Errors?
## Here is how to:
```
yes | pkg update && clear && \
yes | pkg i nodejs && clear && \
yes | GYP_DEFINES="android_ndk_path=$PREFIX" npm install -g @google/gemini-cli --ignore-scripts && clear && \
gemini --version && clear && \
gemini
```
