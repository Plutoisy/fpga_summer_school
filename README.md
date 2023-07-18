项目参考 ： [dhm2013724/yolov2_xilinx_fpga](https://github.com/dhm2013724/yolov2_xilinx_fpga)<br/>
           [qing-2/PYNQ-YOLOv2]https://github.com/qing-2/PYNQ-YOLOv2

> 本项目主要复现在FPGA上运行yolov2的整个流程，hls-vivado-fpga<br/>
> 本项目运行环境为Vivado HLS 2018.3与Vivado 2018.3

### 1.在Vivado HLS 2018.3完成c仿真(时间较长)，c综合，RTL导出，产生ip核
### 2. 在Vivado 2018.3中完成ip核连线与电路仿真综合，生成bit流文件和hwh文件
### 3. 将bit和hwh上传pynq远程实验室的板子上，运行ipynb查看结果 


