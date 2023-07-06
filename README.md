# cartographer_installer

用于一键安装cartographer

# 一键执行安装

    git clone https://github.com/Astrophil-github/cartographer_installer.git

    # 适用于ubuntu20及以上版本
    ./auto-carto-build_20.sh
    # 适用于ubuntu18及以上版本
    ./auto-carto-build_18.sh

# 后续编译

需要再下载一个cartographer的工作空间

    cd
    git clone https://github.com/xiangli0608/cartographer_detailed_comments_ws
    cd cartographer_detailed_comments_ws
    ./catkin_make.sh