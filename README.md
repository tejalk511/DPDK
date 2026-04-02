# DPDK
What you should do in Codespaces
Step 1: Setup
sudo apt update
sudo apt install -y build-essential meson ninja-build libnuma-dev
Step 2: Clone DPDK
git clone https://github.com/DPDK/dpdk.git
cd dpdk
----------------------
Optional 
sudo apt update
sudo apt install -y meson ninja-build python3-pyelftools libnuma-dev
pip3 install pyelftools (Install elftools using pip (important))
----------------------------
Step 3: Build
meson setup build
cd build
ninja
