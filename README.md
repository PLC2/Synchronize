# Auto Synchronize forked repositories

This repository automates the synchronization of forked repositories for the GitHub namespace `PLC2`. The algorithm
lives in the reusable action [pyTooling/SynchronizeForks](https://github.com/pyTooling/SynchronizeForks); this
repository contributes only the
[workflow](https://github.com/PLC2/Synchronize/blob/main/.github/workflows/Synchronize.yml) calling it and the
configuration files (`*.repos`) listing the forks as well as the branches and tags to synchronize.


## Synchronized repositories

Which branches and tags of each fork are synchronized is in the `*.repos` files; repeating it here would only go out
of date.

* Balister
  * `Balister-meta-sdr` ⇐ [balister/meta-sdr](https://github.com/balister/meta-sdr)
* Docker
  * `docker-compose` ⇐ [docker/compose](https://github.com/docker/compose)
* EttusResearch
  * `EttusResearch-uhd` ⇐ [EttusResearch/uhd](https://github.com/EttusResearch/uhd)
  * `EttusResearch-meta-ettus` ⇐ [EttusResearch/meta-ettus](https://github.com/EttusResearch/meta-ettus)
  * `EttusResearch-meta-stm32` ⇐ [EttusResearch/meta-stm32](https://github.com/EttusResearch/meta-stm32)
* Grafana
  * `Grafana-Loki` ⇐ [grafana/loki](https://github.com/grafana/loki)
* Hailo
  * `HailoRT` ⇐ [hailo-ai/hailort](https://github.com/hailo-ai/hailort)
  * `HailoRT-Drivers` ⇐ [hailo-ai/hailort-drivers](https://github.com/hailo-ai/hailort-drivers)
  * `Meta-Hailo` ⇐ [hailo-ai/meta-hailo](https://github.com/hailo-ai/meta-hailo)
* Infineon
  * `Infineon-ELTT2` ⇐ [Infineon/eltt2](https://github.com/Infineon/eltt2)
* Mender
  * `Mender-meta-mender` ⇐ [mendersoftware/meta-mender](https://github.com/mendersoftware/meta-mender)
* OpenBMC
  * `openbmc-sdbusplus` ⇐ [openbmc/sdbusplus](https://github.com/openbmc/sdbusplus)
* OSVVM
  * `OSVVM` ⇐ [OSVVM/OSVVM](https://github.com/OSVVM/OSVVM)
  * `OSVVM-Libraries` ⇐ [OSVVM/OsvvmLibraries](https://github.com/OSVVM/OsvvmLibraries)
  * `OSVVM-Scripts` ⇐ [OSVVM/OSVVM-Scripts](https://github.com/OSVVM/OSVVM-Scripts)
  * `OSVVM-Common` ⇐ [OSVVM/OSVVM-Common](https://github.com/OSVVM/OSVVM-Common)
  * `OSVVM-AXI4` ⇐ [OSVVM/AXI4](https://github.com/OSVVM/AXI4)
  * `OSVVM-UART` ⇐ [OSVVM/UART](https://github.com/OSVVM/UART)
  * `OSVVM-DPRAM` ⇐ [OSVVM/DpRam](https://github.com/OSVVM/DpRam)
  * `OSVVM-CoSim` ⇐ [OSVVM/CoSim](https://github.com/OSVVM/CoSim)
  * `OSVVM-CoSimPCIe` ⇐ [OSVVM/CoSimPCIe](https://github.com/OSVVM/CoSimPCIe)
  * `OSVVM-Ethernet` ⇐ [OSVVM/Ethernet](https://github.com/OSVVM/Ethernet)
  * `OSVVM-Wishbone` ⇐ [OSVVM/Wishbone](https://github.com/OSVVM/Wishbone)
  * `OSVVM-SPI` ⇐ [OSVVM/SPI_GuyEschemann](https://github.com/OSVVM/SPI_GuyEschemann)
  * `OSVVM-VideoBus` ⇐ [OSVVM/VideoBus_LouisAdriaens](https://github.com/OSVVM/VideoBus_LouisAdriaens)
  * `OSVVM-Documentation` ⇐ [OSVVM/Documentation](https://github.com/OSVVM/Documentation)
* Prometheus
  * `Prometheus-node_exporter` ⇐ [prometheus/node_exporter](https://github.com/prometheus/node_exporter)
  * `Prometheus-client_python` ⇐ [prometheus/client_python](https://github.com/prometheus/client_python)
  * `prometheus-community-node-exporter-textfile-collector-scripts` ⇐ [prometheus-community/node-exporter-textfile-collector-scripts](https://github.com/prometheus-community/node-exporter-textfile-collector-scripts)
  * `prometheus-cpp` ⇐ [jupp0r/prometheus-cpp](https://github.com/jupp0r/prometheus-cpp)
  * `prometheus-iio-exporter` ⇐ [luigifcruz/prometheus-iio-exporter](https://github.com/luigifcruz/prometheus-iio-exporter)
* VHDL
  * `PoC` ⇐ [VHDL/PoC](https://github.com/VHDL/PoC)
* Xilinx
  * `Xilinx-linux-xlnx` ⇐ [Xilinx/linux-xlnx](https://github.com/Xilinx/linux-xlnx)
  * `Xilinx-meta-amd-adaptive-socs` ⇐ [Xilinx/meta-amd-adaptive-socs](https://github.com/Xilinx/meta-amd-adaptive-socs)
  * `Xilinx-meta-amd-edf` ⇐ [Xilinx/meta-amd-edf](https://github.com/Xilinx/meta-amd-edf)
  * `Xilinx-meta-arm` ⇐ [Xilinx/meta-arm](https://github.com/Xilinx/meta-arm)
  * `Xilinx-meta-openamp` ⇐ [Xilinx/meta-openamp](https://github.com/Xilinx/meta-openamp)
  * `Xilinx-meta-openembedded` ⇐ [Xilinx/meta-openembedded](https://github.com/Xilinx/meta-openembedded)
  * `Xilinx-meta-qt5` ⇐ [Xilinx/meta-qt5](https://github.com/Xilinx/meta-qt5)
  * `Xilinx-meta-rauc` ⇐ [Xilinx/meta-rauc](https://github.com/Xilinx/meta-rauc)
  * `Xilinx-meta-ros` ⇐ [Xilinx/meta-ros](https://github.com/Xilinx/meta-ros)
  * `Xilinx-meta-security` ⇐ [Xilinx/meta-security](https://github.com/Xilinx/meta-security)
  * `Xilinx-meta-virtualization` ⇐ [Xilinx/meta-virtualization](https://github.com/Xilinx/meta-virtualization)
  * `Xilinx-meta-xilinx` ⇐ [Xilinx/meta-xilinx](https://github.com/Xilinx/meta-xilinx)
  * `Xilinx-meta-Xilinx-Tools` ⇐ [Xilinx/meta-xilinx-tools](https://github.com/Xilinx/meta-xilinx-tools)
  * `Xilinx-meta-zephyr` ⇐ [Xilinx/meta-zephyr](https://github.com/Xilinx/meta-zephyr)
  * `Xilinx-Poky` ⇐ [Xilinx/poky](https://github.com/Xilinx/poky)
* *others*
  * `civetweb` ⇐ [civetweb/civetweb](https://github.com/civetweb/civetweb)
  * `CppLinuxSerial` ⇐ [gbmhunter/CppLinuxSerial](https://github.com/gbmhunter/CppLinuxSerial)
  * `libpqxx` ⇐ [jtv/libpqxx](https://github.com/jtv/libpqxx)
  * `CESNET-libyang` ⇐ [CESNET/libyang](https://github.com/CESNET/libyang)
  * `oatpp` ⇐ [oatpp/oatpp](https://github.com/oatpp/oatpp)
  * `moreutils` ⇐ [pgdr/moreutils](https://github.com/pgdr/moreutils)
  * `Catch2` ⇐ [catchorg/Catch2](https://github.com/catchorg/Catch2)
  * `googletest` ⇐ [google/googletest](https://github.com/google/googletest)


## Configuration File Formats

`.ALL.repos` lists the upstream organisations, one per line. Each of them has a matching `<organisation>.repos` file
listing its forks as `<upstream>=<fork>:<branches>[:<tagPatterns>]`, the tag patterns being optional. A line starting
with `#` is a comment. See the
[action's README](https://github.com/pyTooling/SynchronizeForks#configuration-file-formats) for the authoritative
description.


## Documentation

See [pyTooling/SynchronizeForks](https://github.com/pyTooling/SynchronizeForks) for the action: its parameters, the
configuration file format, what it reports as an error, and how branches and tags are synchronized.
