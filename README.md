# LLM Research Notes

한국어 LLM fine-tuning, 데이터 전처리와 텍스트 평가 실험을 모은 연구 저장소입니다.
[woonsango/LLM_research](https://github.com/woonsango/LLM_research)의 fork이며, 이곳의 설명은 현재 저장된 코드 기준입니다.

| 폴더 | 내용 |
| :--- | :--- |
| [Dataset](Dataset/) | 영어·한국어 데이터와 전처리 노트북 |
| [Model/phi_2_korean_fine_tuning](Model/phi_2_korean_fine_tuning/) | Phi-2 / KoAlpaca fine-tuning 학습·로드 실험 |
| [Evaluation/TIRscore](Evaluation/TIRscore/) | TIRscore 평가 함수와 예제 |

모델 실험의 진행 상태와 한계는 [실험 README](Model/phi_2_korean_fine_tuning/README.md)에 남겨두었습니다.
학습 코드에는 PyTorch, Transformers, Datasets, PEFT, TRL 의존성이 있으며, 모든 실험을 재현하는 검증된 버전 조합은 제공하지 않습니다.

추적되던 로컬 `venv/`는 제거했습니다. 필요한 가상환경은 실행할 컴퓨터에서 새로 만들고, 각 실험에 맞는 의존성을 설치하세요.
기존 가상환경과 과거 실험 파일은 Git 이력에서 확인할 수 있습니다.
