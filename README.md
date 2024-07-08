# idus-shimmer-Upgrade

자세한 기술과 영상설명은 아래의 노션을 클릭해주세요:  
[Notion 페이지](https://intriguing-cowl-e9d.notion.site/idus-3ccead989c854699993e8895c27eefd9)

## 목표
**목표:** 현업에서 활약하고 있는 개발 선배님들의 실력 따라잡기

## 문제 발생
사용자가 메인화면에 진입 후, 로딩화면과 로딩완료된 메인화면의 미세한 경계를 허물어보는 시도를 해보고 싶었습니다.</br> 사용자가 인지하지 못하는 그 짧은 순간도 캐치해 완벽에 가까운 개발자가 되기 위해 개선을 시도했습니다.

## 문제 해결

### 접근

1. **다양한 접근 방법 시도**

이번 문제를 해결하기 위해 다양한 시도를 해보았습니다.

가장 먼저 생각한 방법은 Shimmer 효과와 Skeleton 효과를 사용하지 않고 SplashScreen에서 메인 화면의 정보를 받아오는 것이었습니다. 하지만 네트워크 지연, 불확실성, 앱의 응답성 등의 문제로 많은 기업들이 이 방법을 채택하지 않는다는 것을 알게 되었습니다.
(사용하지 않는 이유에 대한 자세한 내용은 [Notion 페이지](https://intriguing-cowl-e9d.notion.site/idus-3ccead989c854699993e8895c27eefd9)에서 확인할 수 있습니다.)

다음으로 생각한 방법은 애니메이션을 활용하는 것이었습니다. Shimmer와 Skeleton 효과를 메인 화면과 자연스럽게 연결하면 사용자가 조금 더 편안해지지 않을까 하는 생각으로 접근해보았습니다.

#### 1.1 로딩 효과와 각 렌더링 화면의 자연스러운 전환 효과
먼저 Skeleton UI를 설계한 후, Shimmer 효과를 적용했습니다. 다음으로 이 효과를 각 화면의 Stack 위젯으로 감싸 겹치게 표현한 뒤, Opacity 위젯을 통해 자연스럽게 화면을 전환하였습니다.
</br></br>
## 리뷰
이번 프로젝트에서는 메인 화면의 로딩과 완료된 화면 간의 미세한 경계를 허물어 사용자 경험을 개선하고자 하는 목표를 설정하였습니다. 이를 위해 다양한 접근 방법을 시도한 결과, 몇 가지 중요한 점들을 배울 수 있었습니다.

위와 같은 해결 과정은 사용자 경험을 최우선으로 고려한 다양한 시도와 접근 방식을 통해 이루어졌습니다. 네트워크와 UI/UX의 복합적인 문제를 해결하기 위해 애니메이션과 로딩 효과를 적절히 활용함으로써, 사용자가 자연스럽고 편안한 화면 전환을 경험할 수 있게 되었습니다.

마지막으로, 이번 프로젝트를 통해 단순히 기능 구현을 넘어 사용자 중심의 개발 접근 방식을 더욱 강화할 수 있는 기회가 되었습니다. 앞으로도 이러한 경험을 바탕으로 더욱 완벽한 사용자 경험을 제공하기 위해 지속적으로 노력하고 성장하고자 합니다.

