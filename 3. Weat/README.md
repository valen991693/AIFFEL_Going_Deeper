# AIFFEL Campus Online 5th Code Peer Review
- 코더 : 김범준
- 리뷰어 : 황인준


# PRT(PeerReviewTemplate) 
각 항목을 스스로 확인하고 토의하여 작성한 코드에 적용합니다.

- [O] 코드가 정상적으로 동작하고 주어진 문제를 해결했나요?
  > 네, 여러 영화 장르의 예술-일반 영화에 대한 weat score를 확인했습니다
- [O] 주석을 보고 작성자의 코드가 이해되었나요?
  > 기존 코드와 다른 형태소 분석기를 사용하면서 그에대한 주석을 남겨서 이해를 도왔다 
```python
from konlpy.tag import Mecab
tokenizer = Mecab() #속도가 느려 형태소 분석기는 교체하였다 
```
- [O] 코드가 에러를 유발할 가능성이 없나요?
  > 에러가 발생하지 않았습니다.
- [O] 코드 작성자가 코드를 제대로 이해하고 작성했나요?
  > 작성자가 여러 시행착오를 거치며 적절한 방식을 찾으려고 노력한것으로 보아 이해하고 작성한것임을 알 수 있다.
- [O] 코드가 간결한가요?
  > 네 코드가 간결하게 작성되었습니다.

# 예시
1. 코드의 작동 방식을 주석으로 기록합니다.
2. 코드의 작동 방식에 대한 개선 방법을 주석으로 기록합니다.
3. 참고한 링크 및 ChatGPT 프롬프트 명령어가 있다면 주석으로 남겨주세요.
```python

```

# 참고 링크 및 코드 개선
> 작성자는 기존의 코드에서 크게 두가지를 다르게 시도해 보았다. 첫번째는 형태소 분석기를 okt에서 mecab를 사용해보았다는 것이고, 두번째는 타겟에서의 공통 단어를 포함하고 진행해봤다는점이다.
> WEAT score가 두가지 요인으로 인해서 1보다 크거나 -1보다 작은 경우가 없었던 것이 아닐까 생각하는데, 일반영화 예술영화의 공통단어가 장르영화들의 축 상에서 기하학적인 의미로 수직 성분이 많았던게 아닐까 추정해볼 수 있지 않을까 싶다.
> 혹은 mecab 방식이 WEAT score 계산에 불리한게 아닐까 생각된다
```python

```
