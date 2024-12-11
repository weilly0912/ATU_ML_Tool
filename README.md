# i.MX Runtime Tool (imxrt) 
To install the i.MX Runtime's AI development tool [(imxrt)](https://github.com/weilly0912/ATU_ML_Tool/blob/main/imxrt) on NXP i.MX Series , simply place this tool in the /usr/bin directory to use it!

# How to using imxrt tool

* **(1) help**

  * $ imxrt –-help


* **(2) display systems information**

  * $ imxrt –-info 1

* **(3) running model**

  * using NPU

    * $ imxrt –-run "tflite" –-acc "npu"

  * using GPU

    * $ imxrt –-run "tflite" –-acc "gpu"

  * using CPU

    * $ imxrt –-run "tflite" –-acc "cpu"

* **(4) Benchmark**

  * $ imxrt -b "tflite" 

  * $ imxrt –-benchmark_loop_generate_file mlmodel/ –csv_status 'w+'

* **DEMO**

  * $ imxrt --demo help

  * $ imxrt –-demo ObjectDetect_YOLOv5s

  * $ imxrt –-demo ObjectDetect_Gstreamer
 
  ![圖1](https://github.com/weilly0912/ATU_ML_Tool/blob/main/result_1.jpg)


* 必須安裝 :
  * pip3 install requests
