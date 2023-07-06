# cartographer_installer

用于一键安装cartographer

# 一键执行安装

    git clone https://github.com/Astrophil-github/cartographer_installer.git

    # 适用于ubuntu20及以上版本
    ./auto-carto-build_20.sh
    # 适用于ubuntu18及以上版本
    ./auto-carto-build_18.sh

# 测试

    # 下载 2D backpack example bag.
    wget -P ~/Downloads https://storage.googleapis.com/cartographer-public-data/bags/backpack_2d/cartographer_paper_deutsches_museum.bag


    # 运行 Launch the 2D backpack demo.
    roslaunch cartographer_ros demo_backpack_2d.launch bag_filename:=${HOME}/Downloads/cartographer_paper_deutsches_museum.bag