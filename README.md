# LLM Auto Optimization

## Description
**각 서브모듈에 프로젝트 전체의 기능이 아래처럼 나누어져 있습니다.**

### Main repository
* nsgaquant : NSGA-2를 이용한 mixed-precision quantization configuration search framework 구현체.
* GPTQModel : 기존 GPTQModel 프로젝트를 변형하여 최적화된 inference speed benchmark와 latency를 objective로 한 NSGA search를 위한 linear performance estimator이 구현되어 있음.

사용법은 main repository 각각의 README를 참고하세요.

### Sub repository
* GPTQ_kernels : 3bit autogptq과 2.1bit, 3.1bit owq 커널을 포함한 커널 레포지토리
* hqq
* ao
