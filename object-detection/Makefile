all:
	g++ -fPIE -O3 -o tutorial1 --std=c++11 main.cpp -I. \
            -I/opt/intel/computer_vision_sdk/opencv/include/ \
            -I/opt/intel/computer_vision_sdk/deployment_tools/inference_engine/include/ \
            -I/opt/intel/computer_vision_sdk/deployment_tools/inference_engine/include/cpp \
            -L/opt/intel/computer_vision_sdk/deployment_tools/inference_engine/lib/ubuntu_16.04/intel64 -linference_engine -ldl -lpthread -lcpu_extension \
            -L/opt/intel/computer_vision_sdk/opencv/lib -lopencv_core -lopencv_imgcodecs -lopencv_imgproc -lopencv_highgui -lopencv_videoio -lopencv_video -I$(INTEL_CVSDK_DIR)/deployment_tools/inference_engine/include -I$(INTEL_CVSDK_DIR)/deployment_tools/inference_engine/samples/ -I./ -I$(INTEL_CVSDK_DIR)/deployment_tools/inference_engine/samples/common/format_reader/ -I$(INTEL_CVSDK_DIR)/opencv/include -I/usr/local/include -I$(HOME)/inference_engine_samples/thirdparty/gflags/include -I$(INTEL_CVSDK_DIR)/deployment_tools/inference_engine/include -I$(INTEL_CVSDK_DIR)/deployment_tools/inference_engine/include/cpp -I$(INTEL_CVSDK_DIR)/deployment_tools/inference_engine/samples/extension -L$(INTEL_CVSDK_DIR)/deployment_tools/inference_engine/bin/intel64/Release/lib -L$(INTEL_CVSDK_DIR)/deployment_tools/inference_engine/lib/ubuntu_16.04/intel64 -L/opt/intel/computer_vision_sdk/deployment_tools/inference_engine/samples/build/intel64/Release/lib -L$(INTEL_CVSDK_DIR)/opencv/lib -ldl -linference_engine -lopencv_highgui -lopencv_core -lopencv_imgproc -lopencv_videoio -lopencv_imgcodecs -lopencv_imgcodecs -lcpu_extension -L$(HOME)/inference_engine_samples/intel64/Release/lib -lgflags_nothreads 


