# eaglerxQuickSetup
EaglercraftX setup with TeaVM 0.8.1

Quick setup command for linux:
git clone https://github.com/eaglerarchive/eaglercraftx-1.8.git; cd ./eaglercraftx-1.8/mcp918; wget http://www.modcoderpack.com/files/mcp918.zip; wget https://launcher.mojang.com/v1/objects/0983f08be6a4e624f5d85689d1aca869ed99c738/client.jar; wget https://raw.githubusercontent.com/ThisIsALegitUsername/AssetsIndex/main/1.8.json; sudo apt-get update; sudo apt-get install ffmpeg; cd ../; chmod +x ./build_init.sh; chmod +x ./build_make_workspace.sh; ./build_init.sh; ./build_make_workspace.sh

Move ./org/teavm/jso into generated directory ./org/teavm

Change build.gradle file to be the one in this repo
