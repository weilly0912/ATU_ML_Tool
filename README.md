# ATU Machine Learning Tool ( atuml )
To install the ATU Machine Learning Tool's AI development tool [(atuml)](https://github.com/weilly0912/ATU_ML_Tool/blob/main/atuml) on NXP i.MX Series , simply place this tool in the /usr/bin directory to use it!

# How to using atuml tool

* **(1) help**

  * $ atuml –-help


* **(2) display systems information**

  * $ atuml –-info 1

* **(3) running model**

  * using NPU

    * $ atuml –-run <tflite> –-acc "npu"

  * using GPU

    * $ atuml –-run <tflite> –-acc "gpu"

  * using CPU

    * $ atuml –-run <tflite> –-acc "cpu"

* **(4) Benchmark**

  * $ atuml -b <tflite>

  * $ atuml –-benchmark_loop_generate_file mlmodel/ –csv_status 'w+'

* **DEMO**

  * $ atuml --demo help

  * $ atuml –-demo ObjectDetect_YOLOv5s

  * $ atuml –-demo ObjectDetect_Gstreamer
 
  ![圖1](https://github.com/weilly0912/ATU_ML_Tool/blob/main/result_1.jpg)

