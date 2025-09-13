### Edge AI H/W, S/W Codesign

1. HW는 Simulation 형태로 정해서 한다
* TOPs
* Memory BW
* Memory Size
* DRAM은 어떻게 해야하나?
* constraint를 reverse engineering 한다. 

2. Benchmark는 아래 reference 가 있긴 한데, 어떻게 활용할지 생각해본다.
* Qualcomm AI Hub
* https://aihub.qualcomm.com/mobile/models?domain=Generative+AI&useCase=Text+Generation

3. 모델은 가능하면 최신 모델을 하면 배우는게 많을 것 같다.
* Open AI OSS (LLM) 
* Qwen3 (LLM)
* Gemma (LLM)
* Lamma (LLM)
* YOLOv10-Detection (CNN Object Detection 계약), VR Glass 환경에서 object detection(상품정보?, 객체 인식)
* Stable-Diffusion-v2.1 (Diffusion)
* etc. 

4. Quantization은 QAT로 한다?
* 같이 하는 사람들이 배울수 있으니

5. GPU에서 Nsight 이용해서 profiling & optimization
* https://developer.nvidia.com/nsight-systems

6. 같이 강의듣고 토론하기
efficientML 송한 교수→ https://youtu.be/rCFvPEQTxKI?si=JZG0v7NwK0PC-mU6

+김형섭, 김재원, 김승우
- Lecture 3-4 : Pruning
- Lecture 5-6 : Quantization
- Lecture 9 : Knowledge Distillation
- idea 제안 → final project 따라해보기??
- 각자 공부 후 논의하기
- in discord
