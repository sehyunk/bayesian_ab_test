# bayesian_ab_test
베이지안 AB테스트 검증 모듈

- A군과 B군의 샘플수(n)와 전환수(c)를 받습니다.
  - `(A군샘플, A군전환, B군샘플, B군전환)`
- 실험결과를 반환합니다.
  - `{chance}의 확률로 {uplift}개선`
- 앰플리튜드의 chance to outperform을 python에서도 동일하게 구현하기위해 만듬
  - [[Amplitude] How Amplitude calculates chance to outperform](https://help.amplitude.com/hc/en-us/articles/360053484751-FAQ-How-Amplitude-calculates-chance-to-outperform-and-statistical-significance-in-A-B-tests)
