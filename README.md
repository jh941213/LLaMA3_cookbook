# LLaMA3_Cookbook 🦙

LLaMA3 (Large Language Model by META AI)는 AI 기술의 최전선에서 활약하는 대규모 언어 모델입니다.🌟 이 저장소📁는 LLaMA3를 활용하여 다양한 프로젝트🚀를 시작하는 데 필요한 정보를 제공하고자 합니다.

## 공식 웹사이트 및 정보
- [공식홈페이지](https://llama.meta.com/)
- [Request acess](https://llama.meta.com/llama-downloads/)
- [Meta Llama Model card](https://llama.meta.com/docs/model-cards-and-prompt-formats/meta-llama-3)
- [Kaggle meta](https://www.kaggle.com/organizations/metaresearch/models)

## ⚡️ Cloud API 
### API 호출 가능
| 이름 | 설명 | 링크 |
|------------|------|------|
| Grok | 고성능 AI Chip을 통해 LLaMA3를 인퍼런스 및 API 호출을 통해 이용할 수 있다 | [Grok](https://console.groq.com/playground) | 
| AWS | bedrock 에서 LLaMA를 지원합니다 현재 llama2만 사용가능 |[AWS](https://aws.amazon.com/ko/bedrock/) |
| Azure | Microsoft Azure 8B/70B 둘다 지원 Azrue Marketplace 검색 | [Azure](https://azuremarketplace.microsoft.com/en-us/marketplace/apps/metagenai.meta-llama-3-8b-chat-offer?tab=overview)|
| together.ai | llama2, codellama, llama3 8b/70b inst 사용가능 |[together.ai](https://www.together.ai/) |


## 🤖 인퍼런스 (Inference)


### 인퍼런스 플랫폼
| 플랫폼 이름 | 설명 | 링크 |
|------------|------|------|
| HuggingFace | Llama 8B | [link](https://meta-llama/Meta-Llama-3-8B) |
| HuggingFace | Llama 70B | [link](https://huggingface.co/meta-llama/Meta-Llama-3-70B) |
| HuggingFace | Llama 8B Instruct| [link](https://huggingface.co/meta-llama/Meta-Llama-3-8B-Instruct) |
| HuggingFace | Llama 70B Instruct| [link](https://huggingface.co/meta-llama/Meta-Llama-3-70B-Instruct) |
| HuggingFace | Llama Guard-2-8B(정책모델) | [link](https://huggingface.co/meta-llama/Meta-Llama-Guard-2-8B) |
| Ollama | 다양하게 경량화 되어있는 llama3 모델 추론 가능 | [link](https://ollama.com/library/llama3) |

## 💬 Chat InterFace (Related Information)
| 이름 | 링크 |
|------------|------|
| HuggingChat | [link](https://huggingface.co/chat/) |
| Groq | [link](https://groq.com/) |
| togeter.ai |[link](https://www.together.ai/) |


## LLaMA Framework(RAG)

| 이름 | 링크 | 
|------------|------|
|Langchain | [link](https://www.langchain.com/) |
|llamaindex | [link](https://www.llamaindex.ai/) |


## 🛠️ 파인튜닝 (Fine-tuning)
| 이름 | 링크 | 
|------------|------|
|torchrune| [link](https://github.com/pytorch/torchtune)|






## 관련정보
| 정보 | 링크 | 
|------------|------|
| 프롬프트 엔지니어링 가이드 | [link](https://www.promptingguide.ai/tools)|
| 맥북관련 llama 튜닝 및 인퍼런스 | [link](https://itnext.io/step-by-step-guide-to-running-latest-llm-model-meta-llama-3-on-apple-silicon-macs-m1-m2-or-m3-b9424ada6840) | 




## MAC vs 4090

| 항목          | M3 Max                              | M1 Pro                    | RTX 4090                                    |
|---------------|-------------------------------------|---------------------------|---------------------------------------------|
| CPU 코어      | 16코어                              | 10코어                    | 16코어 AMD                                  |
| 메모리        | 128GB                               | 16GB                      | 32GB                                        |
| GPU 메모리    | 없음                                | 없음                      | 24GB                                        |
| **모델 7B** | - 모든 컴퓨터에서 잘 작동            | - 모든 컴퓨터에서 잘 작동   | - 모든 컴퓨터에서 잘 작동                    |
|               | - 성능 M3 Max와 유사                  |                           | - 성능 M3 Max와 유사                          |
| **모델 13B**| - 성능 좋음                        | - 세 번째로 성능 좋음       | - 가장 성능 좋음                             |
| **모델 70B**| - 빠르게 실행, 128GB 메모리 활용    | - 16GB 부족, 크래시 및 재부팅 | - GPU에서 실행 불가, CPU에서 매우 느리게 실행 |
| 전력 소모      | 65W                                |                           | 250-300W                                    |
| 가격 대비 성능 | 우수 ($4600)                       |                           | 비교적 낮음 ($6000 for A6000 GPU)            |


## 🙌 기여하기
이 저장소에 기여하고 싶으신가요? [Issues](https://github.com/your-github/LLaMA3_Recipes/issues)에 자유롭게 의견을 남기거나 Pull Request를 보내주세요. 모든 종류의 기여를 환영합니다!

## 📩 문의하기
더 많은 정보가 필요하거나 협력을 희망하시는 분은 [여기](https://github.com/your-github/LLaMA3_Recipes)를 클릭하여 저에게 메시지를 보내주세요. 함께 지식을 나누고 싶습니다!
