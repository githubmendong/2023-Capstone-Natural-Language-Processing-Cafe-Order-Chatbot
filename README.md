# 2023-Capstone-Natural-Language-Processing-Cafe-Order-Chatbot

# 2023-05-29 중간 보고
프로젝트의 목적:
이 프로젝트의 주된 목표는 자연어 처리 분야의 두 주요 모델인 BERT와 GPT-4를 이해하고 활용하는 것입니다.
이 모델들은 현재 가장 고도의 인공지능 언어 처리 기능을 제공하며, 이를 통해 자연어 처리 분야의 이해도를 높이고자 합니다.

입력 데이터:
훈련 단계에서는 질문(Question)과 답변(Answer), 그리고 의도(Intent)가 라벨링된 데이터를 입력으로 사용합니다.
이러한 데이터는 모델이 학습하는 데 필요한 핵심 정보를 제공하며, 모델이 어떤 입력에 대해 어떤 출력을 생성해야 하는지를 이해하게 돕습니다.

모델 사용:
학습이 완료된 모델은 사용자로부터 질문(Question)을 입력으로 받아 생성된 답변(Answer)를 출력합니다.
이 과정에서 모델은 학습 단계에서 얻은 정보를 활용하여 입력된 질문에 가장 적절한 답변을 생성하게 됩니다.

GPT 사용:
사실 GPT 사용은 단순 호기심에 있습니다.
따라서, Dialog Data -> Input(Q) -> Tokenizing + Masking -> GPT4 generator -> Training 순 모델이 학습합니다.
챗봇은 Data -> (Q) -> BIC -> Input(Q) -> GPT-4 gnerator -> A 순으로 진행합니다.

따라서

