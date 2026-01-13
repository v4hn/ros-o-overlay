# A ROS-O deb repository for testing-bookworm-one

## Github Preview Notice

If you are viewing this page on github.com, please note that the README.md preview on the repository page is incomplete.
Please view [the `README.md` file directly](https://github.com/v4hn/ros-o-overlay/blob/testing-bookworm-one/README.md) to see the full content.

## Install Instructions

```bash
echo "deb [trusted=yes] https://raw.githubusercontent.com/v4hn/ros-o-overlay/testing-bookworm-one/repository/ ./" | sudo tee /etc/apt/sources.list.d/v4hn_ros-o-overlay-testing-bookworm-one.list
sudo apt update
sudo apt install python3-rosdep2
echo "yaml https://raw.githubusercontent.com/v4hn/ros-o-overlay/testing-bookworm-one/repository/local.yaml debian" | sudo tee /etc/ros/rosdep/sources.list.d/1-v4hn_ros-o-overlay-testing-bookworm-one.list
rosdep update

# install required packages, e.g.,
sudo apt install ros-one-desktop-full ros-one-plotjuggler ros-one-navigation [...]
```

## Build

|     |     |
| --- | --- |
| Target Distribution | testing-bookworm |
| Architecture | amd64 |
| Available Packages | 8 |
| Build Date | Tue Jan 13 13:19:15 UTC 2026 |

## Build Status

|   | Logs | Package | Version | Files | Upstream |
| - | ---- | ------- | ------- | ----- | -------- |
| <a id="[eigenpy](https://raw.githubusercontent.com/v4hn/ros-o-overlay/testing-bookworm-one/repository/ros-one-eigenpy_3.12.0-110-gf53e616-2026.01.13.12.27_amd64.deb)" href="#[eigenpy](https://raw.githubusercontent.com/v4hn/ros-o-overlay/testing-bookworm-one/repository/ros-one-eigenpy_3.12.0-110-gf53e616-2026.01.13.12.27_amd64.deb)">:green_circle:</a> | [:green_book:](https://raw.githubusercontent.com/v4hn/ros-o-overlay/testing-bookworm-one/repository/eigenpy_3.12.0-110-gf53e616-2026.01.13.12.27-bloom_generate.log) [:green_book:](https://raw.githubusercontent.com/v4hn/ros-o-overlay/testing-bookworm-one/repository/ros-one-eigenpy_3.12.0-110-gf53e616-2026.01.13.12.27_amd64-2026-01-13T12:27:15Z.build) | [eigenpy](https://raw.githubusercontent.com/v4hn/ros-o-overlay/testing-bookworm-one/repository/ros-one-eigenpy_3.12.0-110-gf53e616-2026.01.13.12.27_amd64.deb) | 3.12.0-110-gf53e616-2026.01.13.12.27 | [:books:](https://raw.githubusercontent.com/v4hn/ros-o-overlay/testing-bookworm-one/repository/ros-one-eigenpy_3.12.0-110-gf53e616-2026.01.13.12.27_amd64.files) | [:link:](https://github.com/stack-of-tasks/eigenpy/tree/devel) |
| <a id="[hpp-fcl](https://raw.githubusercontent.com/v4hn/ros-o-overlay/testing-bookworm-one/repository/ros-one-hpp-fcl_2.4.5-2026.01.13.12.48_amd64.deb)" href="#[hpp-fcl](https://raw.githubusercontent.com/v4hn/ros-o-overlay/testing-bookworm-one/repository/ros-one-hpp-fcl_2.4.5-2026.01.13.12.48_amd64.deb)">:green_circle:</a> | [:green_book:](https://raw.githubusercontent.com/v4hn/ros-o-overlay/testing-bookworm-one/repository/hpp-fcl_2.4.5-2026.01.13.12.48-bloom_generate.log) [:green_book:](https://raw.githubusercontent.com/v4hn/ros-o-overlay/testing-bookworm-one/repository/ros-one-hpp-fcl_2.4.5-2026.01.13.12.48_amd64-2026-01-13T12:48:19Z.build) | [hpp-fcl](https://raw.githubusercontent.com/v4hn/ros-o-overlay/testing-bookworm-one/repository/ros-one-hpp-fcl_2.4.5-2026.01.13.12.48_amd64.deb) | 2.4.5-2026.01.13.12.48 | [:books:](https://raw.githubusercontent.com/v4hn/ros-o-overlay/testing-bookworm-one/repository/ros-one-hpp-fcl_2.4.5-2026.01.13.12.48_amd64.files) | [:link:](https://github.com/humanoid-path-planner/hpp-fcl/tree/HEAD) |
| <a id="[jrl_cmakemodules](https://raw.githubusercontent.com/v4hn/ros-o-overlay/testing-bookworm-one/repository/ros-one-jrl-cmakemodules_1.1.2-20-g51304f9-2026.01.13.12.26_amd64.deb)" href="#[jrl_cmakemodules](https://raw.githubusercontent.com/v4hn/ros-o-overlay/testing-bookworm-one/repository/ros-one-jrl-cmakemodules_1.1.2-20-g51304f9-2026.01.13.12.26_amd64.deb)">:green_circle:</a> | [:green_book:](https://raw.githubusercontent.com/v4hn/ros-o-overlay/testing-bookworm-one/repository/jrl_cmakemodules_1.1.2-20-g51304f9-2026.01.13.12.26-bloom_generate.log) [:green_book:](https://raw.githubusercontent.com/v4hn/ros-o-overlay/testing-bookworm-one/repository/ros-one-jrl-cmakemodules_1.1.2-20-g51304f9-2026.01.13.12.26_amd64-2026-01-13T12:26:35Z.build) | [jrl_cmakemodules](https://raw.githubusercontent.com/v4hn/ros-o-overlay/testing-bookworm-one/repository/ros-one-jrl-cmakemodules_1.1.2-20-g51304f9-2026.01.13.12.26_amd64.deb) | 1.1.2-20-g51304f9-2026.01.13.12.26 | [:books:](https://raw.githubusercontent.com/v4hn/ros-o-overlay/testing-bookworm-one/repository/ros-one-jrl-cmakemodules_1.1.2-20-g51304f9-2026.01.13.12.26_amd64.files) | [:link:](https://github.com/jrl-umi3218/jrl-cmakemodules/tree/master) |
| <a id="[pinocchio](https://raw.githubusercontent.com/v4hn/ros-o-overlay/testing-bookworm-one/repository/ros-one-pinocchio_0-2026.01.13.12.55_amd64.deb)" href="#[pinocchio](https://raw.githubusercontent.com/v4hn/ros-o-overlay/testing-bookworm-one/repository/ros-one-pinocchio_0-2026.01.13.12.55_amd64.deb)">:green_circle:</a> | [:green_book:](https://raw.githubusercontent.com/v4hn/ros-o-overlay/testing-bookworm-one/repository/pinocchio_0-2026.01.13.12.55-bloom_generate.log) [:green_book:](https://raw.githubusercontent.com/v4hn/ros-o-overlay/testing-bookworm-one/repository/ros-one-pinocchio_0-2026.01.13.12.55_amd64-2026-01-13T12:55:37Z.build) | [pinocchio](https://raw.githubusercontent.com/v4hn/ros-o-overlay/testing-bookworm-one/repository/ros-one-pinocchio_0-2026.01.13.12.55_amd64.deb) | 0-2026.01.13.12.55 | [:books:](https://raw.githubusercontent.com/v4hn/ros-o-overlay/testing-bookworm-one/repository/ros-one-pinocchio_0-2026.01.13.12.55_amd64.files) | [:link:](https://github.com/v4hn/pinocchio/tree/pr-cleanup-package.xml) |
| <a id="[urdfdom](https://raw.githubusercontent.com/v4hn/ros-o-overlay/testing-bookworm-one/repository/ros-one-urdfdom_5.0.4-2-g4caee7c-2026.01.13.12.54_amd64.deb)" href="#[urdfdom](https://raw.githubusercontent.com/v4hn/ros-o-overlay/testing-bookworm-one/repository/ros-one-urdfdom_5.0.4-2-g4caee7c-2026.01.13.12.54_amd64.deb)">:green_circle:</a> | [:green_book:](https://raw.githubusercontent.com/v4hn/ros-o-overlay/testing-bookworm-one/repository/urdfdom_5.0.4-2-g4caee7c-2026.01.13.12.54-bloom_generate.log) [:green_book:](https://raw.githubusercontent.com/v4hn/ros-o-overlay/testing-bookworm-one/repository/ros-one-urdfdom_5.0.4-2-g4caee7c-2026.01.13.12.54_amd64-2026-01-13T12:54:29Z.build) | [urdfdom](https://raw.githubusercontent.com/v4hn/ros-o-overlay/testing-bookworm-one/repository/ros-one-urdfdom_5.0.4-2-g4caee7c-2026.01.13.12.54_amd64.deb) | 5.0.4-2-g4caee7c-2026.01.13.12.54 | [:books:](https://raw.githubusercontent.com/v4hn/ros-o-overlay/testing-bookworm-one/repository/ros-one-urdfdom_5.0.4-2-g4caee7c-2026.01.13.12.54_amd64.files) | [:link:](https://github.com/ros/urdfdom/tree/rolling) |
| <a id="[urdfdom_headers](https://raw.githubusercontent.com/v4hn/ros-o-overlay/testing-bookworm-one/repository/ros-one-urdfdom-headers_2.0.2-2026.01.13.12.53_amd64.deb)" href="#[urdfdom_headers](https://raw.githubusercontent.com/v4hn/ros-o-overlay/testing-bookworm-one/repository/ros-one-urdfdom-headers_2.0.2-2026.01.13.12.53_amd64.deb)">:green_circle:</a> | [:green_book:](https://raw.githubusercontent.com/v4hn/ros-o-overlay/testing-bookworm-one/repository/urdfdom_headers_2.0.2-2026.01.13.12.53-bloom_generate.log) [:green_book:](https://raw.githubusercontent.com/v4hn/ros-o-overlay/testing-bookworm-one/repository/ros-one-urdfdom-headers_2.0.2-2026.01.13.12.53_amd64-2026-01-13T12:53:58Z.build) | [urdfdom_headers](https://raw.githubusercontent.com/v4hn/ros-o-overlay/testing-bookworm-one/repository/ros-one-urdfdom-headers_2.0.2-2026.01.13.12.53_amd64.deb) | 2.0.2-2026.01.13.12.53 | [:books:](https://raw.githubusercontent.com/v4hn/ros-o-overlay/testing-bookworm-one/repository/ros-one-urdfdom-headers_2.0.2-2026.01.13.12.53_amd64.files) | [:link:](https://github.com/ros/urdfdom_headers/tree/rolling) |

## Top Offenders (broken packages)

|   | Logs | Package | Version | Files | Upstream |
| - | ---- | ------- | ------- | ----- | -------- |
