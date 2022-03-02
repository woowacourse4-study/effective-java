## [Effective Java 3/E 스터디]

### 일정
22.02.22. ~ 레벨 1 종료 시 까지

### 목록
- [x] 1. [생성자 대신 정적 팩터리 메서드를 고려하라](https://github.com/woowacourse-study/2022-effective-java/blob/main/01%EC%9E%A5/%EC%95%84%EC%9D%B4%ED%85%9C_01/%EC%83%9D%EC%84%B1%EC%9E%90_%EB%8C%80%EC%8B%A0_%EC%A0%95%EC%A0%81_%ED%8C%A9%ED%84%B0%EB%A6%AC_%EB%A9%94%EC%84%9C%EB%93%9C%EB%A5%BC_%EA%B3%A0%EB%A0%A4%ED%95%98%EB%9D%BC.md) (토르)
- [ ] 2. 생성자에 매개변수가 많다면 빌더를 고려하라
- [ ] 3. private 생성자나 열거 타입으로 싱글턴임을 보증하라
- [x] 4. [인스턴스화를 막으려거든 private 생성자를 사용하라](https://github.com/woowacourse-study/2022-effective-java/blob/main/02%EC%9E%A5/%EC%95%84%EC%9D%B4%ED%85%9C_04/%EC%9D%B8%EC%8A%A4%ED%84%B4%EC%8A%A4%ED%99%94%EB%A5%BC%20%EB%A7%89%EA%B8%B0%20%EC%9C%84%ED%95%B4%20private%20%EC%83%9D%EC%84%B1%EC%9E%90%20%EC%82%AC%EC%9A%A9%ED%95%98%EA%B8%B0.md)	(연로그)
- [x] 5. [자원을 직접 명시하지 말고 의존 객체 주입을 사용하라](https://github.com/woowacourse-study/2022-effective-java/blob/main/02%EC%9E%A5/%EC%95%84%EC%9D%B4%ED%85%9C_05/%EC%9E%90%EC%9B%90%EC%9D%84%20%EC%A7%81%EC%A0%91%20%EB%AA%85%EC%8B%9C%ED%95%98%EC%A7%80%20%EB%A7%90%EA%B3%A0%20%EC%9D%98%EC%A1%B4%20%EA%B0%9D%EC%B2%B4%20%EC%A3%BC%EC%9E%85%EC%9D%84%20%EC%82%AC%EC%9A%A9%ED%95%98%EB%9D%BC.md)	(매트)
- [ ] 6. 불필요한 객체 생성을 피하라	
- [ ] 7. 다 쓴 객체 참조를 해제하라	
- [ ] 8. finalizer와 cleaner 사용을 피하라	
- [ ] 9. try-finally보다는 try-with-resources를 사용하라	
- [ ] 10. equals는 일반 규약을 지켜 재정의하라	
- [ ] 11. equals를 재정의하려거든 hashCode도 재정의하라	
- [ ] 12. toString을 항상 재정의하라	
- [ ] 13. clone 재정의는 주의해서 진행하라	
- [x] 14. [Comparable을 구현할지 고려하라](https://github.com/woowacourse-study/2022-effective-java/blob/main/03%EC%9E%A5/%EC%95%84%EC%9D%B4%ED%85%9C_14/Comparable%EC%9D%84_%EA%B5%AC%ED%98%84%ED%95%A0%EC%A7%80_%EA%B3%A0%EB%A0%A4%ED%95%98%EB%9D%BC.pdf) (오찌)
- [ ] 15. 클래스와 멤버의 접근 권한을 최소화하라	
- [ ] 16. public 클래스에서는 public 필드가 아닌 접근자 메서드를 사용하라	
- [ ] 17. 변경 가능성을 최소화하라	
- [x] 18. [상속보다는 컴포지션을 사용하라](https://github.com/woowacourse-study/2022-effective-java/blob/main/04%EC%9E%A5/%EC%95%84%EC%9D%B4%ED%85%9C18/%EC%95%84%EC%9D%B4%ED%85%9C18-%EC%83%81%EC%86%8D%EB%B3%B4%EB%8B%A4%EB%8A%94_%EC%BB%B4%ED%8F%AC%EC%A7%80%EC%85%98%EC%9D%84_%EC%82%AC%EC%9A%A9%ED%95%98%EB%9D%BC.md)	(루키)
- [ ] 19. 상속을 고려해 설계하고 문서화하라. 그러지 않았다면 상속을 금지하라.	
- [x] 20. [추상 클래스보다는 인터페이스를 우선하라](https://github.com/woowacourse-study/2022-effective-java/blob/main/04%EC%9E%A5/%EC%95%84%EC%9D%B4%ED%85%9C20/%EC%95%84%EC%9D%B4%ED%85%9C20-%EC%B6%94%EC%83%81-%ED%81%B4%EB%9E%98%EC%8A%A4%EB%B3%B4%EB%8B%A4%EB%8A%94-%EC%9D%B8%ED%84%B0%ED%8E%98%EC%9D%B4%EC%8A%A4%EB%A5%BC-%EC%9A%B0%EC%84%A0%ED%95%98%EB%9D%BC.md)	(에덴)
- [ ] 21. 인터페이스는 구현하는 쪽을 생각해 설계하라	
- [ ] 22. 인터페이스는 타입을 정의하는 용도로만 사용하라	
- [ ] 23. 태그 달린 클래스보다는 클래스 계층구조를 활용하라	
- [ ] 24. 멤버 클래스는 되도록 static으로 만들라	
- [ ] 25. 톱레벨 클래스는 한 파일에 하나만 담으라	
- [ ] 26. 로 타입은 사용하지 말라	
- [ ] 27. 비검사 경고를 제거하라	
- [ ] 28. 배열보다는 리스트를 사용하라	
- [ ] 29. 이왕이면 제네릭 타입으로 만들라	
- [ ] 30. 이왕이면 제네릭 메서드로 만들라	
- [ ] 31. 한정적 와일드카드를 사용해 API 유연성을 높이라 
- [ ] 32. 제네릭과 가변인수를 함께 쓸 때는 신중하라	
- [ ] 33. 타입 안전 이종 컨테이너를 고려하라	
- [x] 34. [int 상수 대신 열거 타입을 사용하라](https://github.com/woowacourse-study/2022-effective-java/blob/main/06%EC%9E%A5/%EC%95%84%EC%9D%B4%ED%85%9C34/%EC%9D%B4%ED%8E%99%ED%8B%B0%EB%B8%8C_%EC%9E%90%EB%B0%94_%EC%95%8C%ED%8C%8C_34.pdf) (알파)
- [ ] 35. ordinal 메서드 대신 인스턴스 필드를 사용하라	
- [ ] 36. 비트 필드 대신 EnumSet을 사용하라	
- [x] 37. [ordinal 인덱싱 대신 EnumMap을 사용하라](https://github.com/woowacourse-study/2022-effective-java/blob/main/06%EC%9E%A5/%EC%95%84%EC%9D%B4%ED%85%9C_37/ordinal_%EC%9D%B8%EB%8D%B1%EC%8B%B1_%EB%8C%80%EC%8B%A0_EnumMap%EC%9D%84_%EC%82%AC%EC%9A%A9%ED%95%98%EB%9D%BC.md)	(티키)
- [ ] 38. 확장할 수 있는 열거 타입이 필요하면 인터페이스를 사용하라
- [ ] 39. 명명 패턴보다 애너테이션을 사용하라	
- [ ] 40. @Override 애너테이션을 일관되게 사용하라	
- [ ] 41. 정의하려는 것이 타입이라면 마커 인터페이스를 사용하라
- [ ] 42. 익명 클래스보다는 람다를 사용하라	
- [ ] 43. 람다보다는 메서드 참조를 사용하라	
- [ ] 44. 표준 함수형 인터페이스를 사용하라
- [x] 45. [스트림은 주의해서 사용하라](https://github.com/woowacourse-study/2022-effective-java/blob/main/07%EC%9E%A5/%EC%95%84%EC%9D%B4%ED%85%9C_45/%EC%8A%A4%ED%8A%B8%EB%A6%BC%EC%9D%80_%EC%A3%BC%EC%9D%98%ED%95%B4%EC%84%9C_%EC%82%AC%EC%9A%A9%ED%95%98%EB%9D%BC.md)	(야호)
- [x] 46. [스트림에서는 부작용 없는 함수를 사용하라](https://github.com/woowacourse-study/2022-effective-java/blob/main/07%EC%9E%A5/%EC%95%84%EC%9D%B4%ED%85%9C_46/%EC%8A%A4%ED%8A%B8%EB%A6%BC%EC%97%90%EC%84%9C%EB%8A%94_%EB%B6%80%EC%9E%91%EC%9A%A9%EC%97%86%EB%8A%94_%ED%95%A8%EC%88%98%EB%A5%BC_%EC%82%AC%EC%9A%A9%ED%95%98%EB%9D%BC.md) (후니)
- [ ] 47. 반환 타입으로는 스트림보다 컬렉션이 낫다	
- [ ] 48. 스트림 병렬화는 주의해서 적용하라	
- [ ] 49. 매개변수가 유효한지 검사하라	
- [ ] 50. 적시에 방어적 복사본을 만들라	
- [ ] 51. 메서드 시그니처를 신중히 설계하라
- [ ] 52. 다중정의는 신중히 사용하라	
- [ ] 53. 가변인수는 신중히 사용하라	
- [x] 54. [null이 아닌, 빈 컬렉션이나 배열을 반환하라](https://github.com/woowacourse-study/2022-effective-java/blob/main/08%EC%9E%A5/%EC%95%84%EC%9D%B4%ED%85%9C_54/null%EC%9D%B4_%EC%95%84%EB%8B%8C_%EB%B9%88_%EC%BB%AC%EB%A0%89%EC%85%98%EC%9D%B4%EB%82%98_%EB%B0%B0%EC%97%B4%EC%9D%84_%EB%B0%98%ED%99%98%ED%95%98%EB%9D%BC.md) (호호)
- [x] 55. 옵셔널 반환은 신중히 하라	
- [ ] 56. 공개된 API 요소에는 항상 문서화 주석을 작성하라
- [ ] 57. 지역변수의 범위를 최소화하라	
- [x] 58. [전통적인 for 문보다는 for-each 문을 사용하라](https://github.com/woowacourse-study/2022-effective-java/blob/main/08%EC%9E%A5/%EC%95%84%EC%9D%B4%ED%85%9C_58/%EC%A0%84%ED%86%B5%EC%A0%81%EC%9D%B8_for_%EB%AC%B8%EB%B3%B4%EB%8B%A4%EB%8A%94_for-each_%EB%AC%B8%EC%9D%84_%EC%82%AC%EC%9A%A9%ED%95%98%EB%9D%BC.md)	(썬)
- [ ] 59. 라이브러리를 익히고 사용하라	
- [ ] 60. 정확한 답이 필요하다면 float와 double은 피하라
- [ ] 61. 박싱된 기본 타입보다는 기본 타입을 사용하라	
- [ ] 62. 다른 타입이 적절하다면 문자열 사용을 피하라	
- [ ] 63. 문자열 연결은 느리니 주의하라	
- [ ] 64. 객체는 인터페이스를 사용해 참조하라	
- [ ] 65. 리플렉션보다는 인터페이스를 사용하라
- [ ] 66. 네이티브 메서드는 신중히 사용하라	
- [ ] 67. 최적화는 신중히 하라	
- [ ] 68. 일반적으로 통용되는 명명 규칙을 따르라
- [ ] 69. 예외는 진짜 예외 상황에만 사용하라	
- [ ] 70. 복구할 수 있는 상황에는 검사 예외를, 프로그래밍 오류에는 런타임 예외를 사용하라	
- [ ] 71. 필요 없는 검사 예외 사용은 피하라	
- [ ] 72. 표준 예외를 사용하라	
- [ ] 73. 추상화 수준에 맞는 예외를 던지라	
- [ ] 74. 메서드가 던지는 모든 예외를 문서화하라	
- [ ] 75. 예외의 상세 메시지에 실패 관련 정보를 담으라	
- [ ] 76. 가능한 한 실패 원자적으로 만들라	
- [ ] 77. 예외를 무시하지 말라
- [ ] 78. 공유 중인 가변 데이터는 동기화해 사용하라	
- [ ] 79. 과도한 동기화는 피하라	
- [ ] 80. 스레드보다는 실행자, 태스크, 스트림을 애용하라	
- [ ] 81. wait와 notify보다는 동시성 유틸리티를 애용하라	
- [ ] 82. 스레드 안전성 수준을 문서화하라	
- [ ] 83. 지연 초기화는 신중히 사용하라	
- [ ] 84. 프로그램의 동작을 스레드 스케줄러에 기대지 말라
- [ ] 85. 자바 직렬화의 대안을 찾으라	
- [ ] 86. Serializable을 구현할지는 신중히 결정하라	
- [ ] 87. 커스텀 직렬화 형태를 고려해보라	
- [ ] 88. readObject 메서드는 방어적으로 작성하라	
- [ ] 89. 인스턴스 수를 통제해야 한다면 readResolve보다는 열거 타입을 사용하라	
- [ ] 90. 직렬화된 인스턴스 대신 직렬화 프록시 사용을 검토하라

### 학습 목적
- 이펙티브 자바는 레벨 1 필독서 중 하나로, 효율적인 자바 코드를 짜기 위한 솔루션들을 배울 수 있는 책입니다. 하지만 책의 모든 아이템을 정독하면서 테스트 해보고, 책의 예제 외에 적용할 수 있는 코드를 작성해 보는 것을 레벨 1 동안 혼자서 마치기란 쉽지 않습니다. 따라서 여러 사람이 함께 스터디하여 학습 효율을 높이고 레벨 1 동안 완독하는 것을 목표로 합니다.
- 개인적으로 효과적인 학습 방식 중 하나가 본인이 배운 내용을 남에게 설명하거나 가르쳐주는 것이라고 생각합니다. 자신이 맡은 아이템에 대해 발표함으로써 해당 아이템에 대해 효과적으로 학습할 수 있습니다.
- 또한 맡은 아이템이 아니더라도 책을 읽으면서 이해가 가지 않는 부분에 대해 의문점을 가져보고, 다른 크루들과의 토론으로 의문을 풀어나가는 과정을 통해 효율적인 학습을 추구하고자 합니다.

### 진행 방식
- 매주 월, 금 17시에 스터디를 진행합니다.
- 매 스터디마다 1인당 이펙티브 자바의 1개 아이템에 대한 10분 이내의 발표를 진행합니다.
  - 발표자료의 형식은 자유입니다.
- 매 스터디 전날 23:59까지 발표자료를 Pull Requests로 올립니다.
- 발표는 2조로 나누어 진행합니다. 스터디원을 절반으로 나누어 월요일에는 1조가, 금요일에는 2조가 진행합니다. -> 1주일에 아이템 1개씩 발표합니다.
- 조원들이 모두 발표를 마치면 질문을 받고 답변합니다.
- 질문 사항에 대해 발표자가 잘 모르겠다면, Q&A 기간내에 추후 답변도 가능합니다.
- 스터디가 끝나면 다른 조 발표일까지 Q&A를 진행합니다.
  - ex) 월요일에 아이템 1에 대해 발표를 한 오찌는 금요일까지 아이템 1에 대한 스터디원들의 질문에 답변합니다.
- Q&A는 GitHub에 Issues 기능을 사용합니다.
- 본인이 발표하지 않는 아이템도 반드시 읽고 이해가 되지 않는 부분에 대해 질문을 남겨주시면 됩니다.

### 스터디 규칙
- 지각 시 2천원, 결석 시 4천원에 벌금을 총무(에덴)에게 제출합니다.
- 본인의 페어의 발표에는 반드시 최소 1개의 이슈사항을 남깁니다.
- 아이템 선정은 매 스터디가 끝난 뒤 당일 자정까지 선착순으로 슬랙에 남겨서 정합니다.
- 월요일 발표자
  - 후니 매트 루키 티키 썬 야호

- 금요일 발표자
  - 토르 호호 오찌 연로그 알파 에덴

- 전체 발표 진행자는 해당일 발표가 아닌 사람 중에서 가나다순으로 정합니다.
- 업로드하는 발표자료의 디렉토리는 챕터 - 아이템 번호 의 구조로 합니다.
  - ex) 02장 - 아이템_01 - 생성자 대신 정적 팩터리 메서드를 고려하라.md
- 이슈 작성 시 제목은 [itemXX] ~~~ 의 구조로 합니다.
