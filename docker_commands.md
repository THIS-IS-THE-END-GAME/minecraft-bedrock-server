docker run -d -it -e EULA=TRUE -p 19132:19132/udp --name bedrock_minecraft -v ~/minecraft-bedrock-server/_data:/minecraft itzg/minecraft-bedrock-server

git lfs track "_data/worlds/Bedrock level/level.dat"
git lfs track "_data/worlds/Bedrock level/level.dat_old"
git lfs track "_data/worlds/Bedrock level/levelname.txt"