## 安装依赖
sudo apt install libvdpau-dev libavcodec-dev libavcodec-dev libavfilter-dev -y

## 编译
make -j4

## 使用示例
./mpv_vdpau_demo test.h264 test.yuv 1280 720 0 aaa.rgb32 32 32

