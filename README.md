# packer-scripts

to use the scripts, make sure to fill in the service pricipal details in private.json; and run like this:

./packer.exe build -force -var-file private.json -var 'image=gpuimage' centos77-nvidia-mellanox.json

