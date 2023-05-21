## [NEXTSTEP 플레이그라운드의 미션 진행 과정](https://github.com/next-step/nextstep-docs/blob/master/playground/README.md)

---
## 학습 효과를 높이기 위해 추천하는 미션 진행 방법

---
1. 피드백 강의 전까지 미션 진행 
> 피드백 강의 전까지 혼자 힘으로 미션 진행. 미션을 진행하면서 하나의 작업이 끝날 때 마다 add, commit
> 예를 들어 다음 숫자 야구 게임의 경우 0, 1, 2단계까지 구현을 완료한 후 push

![mission baseball](https://raw.githubusercontent.com/next-step/nextstep-docs/master/playground/images/mission_baseball.png)

---
2. 피드백 앞 단계까지 미션 구현을 완료한 후 피드백 강의를 학습한다.

---
3. Git 브랜치를 master 또는 main으로 변경한 후 피드백을 반영하기 위한 새로운 브랜치를 생성한 후 처음부터 다시 미션 구현을 도전한다.

```
git branch -a // 모든 로컬 브랜치 확인
git checkout master // 기본 브랜치가 master인 경우
git checkout main // 기본 브랜치가 main인 경우

git checkout -b 브랜치이름
ex) git checkout -b apply-feedback
```

## 기능 요구사항
- [ ] 카드 별로 가능한 점수를 만든다.
- [ ] 플레이어의 이름을 쉼표를 기준으로 구분한다.
- [ ] 각 플레이어의 베팅 금액을 입력 받는다.
- [ ] 딜러가 플레이어에게 2장의 카드를 나눈다.
- [ ] 카드 숫자를 계산한다.
- [ ] 카드 합이 21일 경우 베팅 금액의 1.5배를 받는다.
- [ ] 딜러와 플레이어가 동시에 21이면 플레이어의 베팅 금액을 돌려준다.
- [ ] 플레이어에게 카드를 더 받을 것인지 묻는다.
- [ ] 카드를 추가로 나눠준다
- [ ] 딜러 카드의 합계가 16 이하면 1장을 무조건 추가로 받는다.
- [ ] 딜러가 21을 초과하면 그 때 남은 플레이어는 베팅 금액을 받는다.
- [ ] 최종 수익을 출력한다.
