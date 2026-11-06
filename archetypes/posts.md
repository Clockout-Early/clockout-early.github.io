---
# 제목 = 사람들이 검색할 말 + 결과(숫자). 조회수는 대부분 제목에서 나온다.
title: "{{ replace .File.ContentBaseName "-" " " | title }}"
date: {{ .Date }}
draft: true            # 검수 체크리스트 통과 + 직접 확인한 뒤에만 false
translationKey: "{{ .File.ContentBaseName }}"   # 한·영 글을 잇는 키. 두 언어에서 같은 파일 이름을 쓴다
tags: []
description: ""        # 검색 결과·SNS 미리보기에 뜨는 한두 문장
savedTime: ""          # 줄인 시간. 예) "하루 15분 → 1분" (실제 경험치로)
---

<!-- 도입: 3~4줄. 독자가 "어, 나도 이거 귀찮은데" 하게 만든다. -->

## 이런 일, 귀찮지 않으세요?

## 결과부터: ○분 → ○분

## 어떻게 했나

### 준비물

### 1단계

### 2단계

## 따라 해 보기

## 해 보니 막혔던 점

## 마무리

<!-- 발행 전: 작업 폴더의 checklists/review.md 확인 -->
