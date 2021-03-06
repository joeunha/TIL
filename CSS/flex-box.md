# [Flexible Box module](https://developer.mozilla.org/ko/docs/Web/CSS/CSS_Flexible_Box_Layout/Flexbox%EC%9D%98_%EA%B8%B0%EB%B3%B8_%EA%B0%9C%EB%85%90)
- flexbox 인터페이스 내의 아이템 간 공간 배분과 강렬한 정렬 기능을 제공하기 위한 1차원 레이아웃 모델로 설계되었다.

#### 적용
- flex로 정렬하고 싶은 요소들을 감싸고 있는 부모 엘리먼트에 `display: flex;`라고 속성을 주면 직속 자식(direct children)이 flex 항목이 된다.
- 기본적으로 `flex-basis:auto; flex-direction:row; flex-wrap:nowrap; (flex-flow: row nowrap;)` 속성으로 적용된다. 이렇게 되면 각 항목(자식)은 내부 요소의 크기로 폭이 설정되고, 주축을 따라 정렬된다.
- `flex-wrap: wrap;` 으로 바꿔주면 항목이 넘치는 경우 줄바꿈을 한다.

#### 축 (Axis)
- Flex 는 두개의 축을 갖는다. 하나는 주축(Main Axis)이라고 부르는 축인데, 정렬 방향과 일치하는 축이다. 다른 하나는 교차축(Cross Axis / Block Axis)으로 주축과 수직 관계에 있는 축이다.

#### 정렬, 끝 맞추기, 여유 공간 분배
- `alingn-items`는 교차축을 따라 정렬하는 방식을 지정한다.
- `alingn-content`는 두줄 이상의 요소를 갖는 flex 컨테이너가 교차축을 따라 아이템을 정렬하는 방식을 지정한다.
- `justify-contents`는 주축을 따라 정렬하는 방식을 지정한다.