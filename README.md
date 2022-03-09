# docker_occt_wasm_sample
Docker image belongs to web assembly sample of OpenCascade v 7.5.0.
# 
To run the web web assembly sample of OpenCascade do the following:

* On the command line execute: `docker pull okanpin/opencascade_wasm_sample`.
* On the command line execute: `docker run -d -p <port>:7000 okanpin/opencascade_wasm_sample`.
* Open a web browser and enter the URL: `http://localhost:<port>` and the browser displays `Directory listing for /`.
* Select `webgl/` and the browser displays `Directory listing for /webgl/`.
* Select `occt-webgl-sample.html` and the browser displays the web assembly sample of OpenCascade.
