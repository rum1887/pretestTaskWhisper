# Pretest Task Whisper
### System information 

```bash
Hardware: Apple M1 Arm64, 8GB RAM
Operating System: macOS Sonoma 14.3
Kernel Version: Darwin 23.3.0
```
### Framework execution

1. Built and ran whisper tiny.en model by following this [guide](https://github.com/ggerganov/whisper.cpp).</br></br>
   <img width="1440" alt="Screenshot 2024-02-08 at 6 57 42 PM" src="https://github.com/rum1887/pretestTaskWhisper/assets/57267583/db9670bd-e519-4292-a38a-da2d8f89e287">
   <img width="1440" alt="Screenshot 2024-02-08 at 6 57 50 PM" src="https://github.com/rum1887/pretestTaskWhisper/assets/57267583/ffb061b7-29e1-4b1d-9b8c-087596e4440e">

 2. Built WasmEdge with llama.cpp plugin by following this [guide](https://wasmedge.org/docs/contribute/source/plugin/wasi_nn/#build-wasmedge-with-wasi-nn-llamacpp-backend).</br></br>
    ![wasmedge](https://github.com/rum1887/pretestTaskMLX/assets/57267583/38f0f2f9-8977-41f1-8099-94e84edc2016)
   
4. Execution(1) llama.cpp  </br></br>
   Modified this [example](https://github.com/second-state/WasmEdge-WASINN-examples/tree/master/wasmedge-ggml) to run "llama2 7b chat model in GGUF format" in WasmEdge</br></br><img width="1440" alt="llama" src="https://github.com/rum1887/pretestTaskMLX/assets/57267583/5cf10e24-8260-4458-bb1b-a51d6b606086">
   
5. Execution(2) API Server</br></br>
   Ran Mistral-7B-Instruct-v0.1 and created an OpenAI compatible API server for the model following this [guide](https://github.com/second-state/LlamaEdge/tree/main/api-server).
   
   <img width="1440" alt="Screenshot 2024-02-17 at 6 03 54 PM" src="https://github.com/rum1887/pretestTaskMLX/assets/57267583/ce1a5ff1-3ca3-49a4-a5b3-5255b9474227">


