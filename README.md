# Let us: GO! 2019 Summer 방문기

```
렛어스고 2019 여름 세미나에 참석한 후기를 담았습니다.
```



2019년 8월 3일은 정말 더웠습니다. 폭염 경보가 내려진 날씨였습니다. 렛어스고 행사장은 홍대입구에 있었습니다. 9호선 급행을 타고 왔지만, 당산에서 환승할 때 온몸이 녹아내리는 느낌이었습니다. 화마와 싸워서 어렵게 간 렛어스고 세미나는 유익했습니다.



## [리빙 포인트] Let us: GO! 세미나는 Go 언어에 대해서 다루지 않는다.

아이폰 점유율이 최근에서야 높아지기도 했고, 개발하려면 맥 장비가 필요한 진입장벽 때문인지 몰라도, iOS 앱 개발자는 주니어, 시니어 모두 다른 개발자 직군에 비해 상대적으로 적다고 느끼고 있습니다. 

그런 이유인지 몰라도, iOS 세미나는 안드로이드 세미나에 비해 그렇게 자주 열리지 않습니다. 부정기적으로 열리는 Let's Swift 와 let us: Go! 두 개 정도만 있습니다.

https://letusgo.app/

let us: Go! 는 일년에 네번 열리는 정기 세미나입니다. iOS Developers Korea 오픈 톡방에서 일년에 네 분기씩 공지 알림이 갑니다. 티케팅은 선착순인데, 시간이 조금만 늦어도 바로 마감됩니다. 사내에서 일하는 선임 iPhone 개발자께도 티케팅을 권유했지만, 저만 티케팅이 성공했습니다. 

제가 렛어스고 행사를 알게된 건 작년 여름이었습니다. 작년 여름은 육군훈련소의 군사훈련과 겹쳐서 참석하지 못했습니다. 그리고 작년 렛어스고 윈터 세미나에 참석했습니다. 올해 봄은 시기를 놓쳐서 신청하지 못했습니다. 두 번째로 가게 된 세미나입니다.

## 쏘카와 마이리얼트립과 헤이딜러가 완전 수라장

작년에 비해서 참석 인원이 엄청 늘어났고, 스폰서들은 아예 부스까지 차렸습니다. 산업기능요원을 하는 입장으로서, 부스를 차린 회사들이 모두 병역특례인정업체라는 점이 눈에 띄었습니다. 각 부스의 리드 개발자  혹은 HR 담당자는 폐회식, 휴식시간 사이사이에 회사 홍보와 지원 홍보를 하고 갔습니다. 모든 스폰서들은 회사 규모에 비해서, iPhone 개발자가 현재 매우 적다는 느낌을 받았습니다.

헤이딜러는 네임드 오픈소스 컨트리뷰터, **장상권** 안드로이드 개발자께서 홍보를 하셨습니다. 안드로이드 팀은 3명이여서 코드 리뷰와 Jira, 컨플루언스, A/B 테스트 등을 도입하고 있다고 했습니다. 반면 아이폰 재직 개발자는 1인이기 때문에, 3년차급이나 5년차 이상급의 아이폰 개발자를 채용하고 있다고 합니다.

마이리얼트립은 HR 담당자가 홍보를 했습니다. HR 답게 회사의 복지와 성장세 등에 대해서 설명을 해 주셨기 때문에, 개발적인 문화를 확실히 알기는 어려웠습니다. 다만 모집 공고 하단에 **(산업기능요원 현역 전직, 보충역 가능)** 이라는 문구가 크게 써있는 건 기억에 남았습니다.쏘카는 아이폰 단독개발자가 홍보를 하셨습니다. 쏘카의 레거시 코드는 외주를 준 레거시 하이브리드 앱이었기 때문에, 그것을 rxSwift를 이용한 풀 네이티브 앱으로 1년동안 갈아 엎은 일화를 소개해 주셔서 기억에 남았습니다.

## 어이-. 이것이 애플의 『iOS 13』 란 것이다--

WWDC 2019 직후의 정기 세미나인 만큼, iOS 13 베타와 Xcode 11 베타, 맥 카탈리나의 새로운 기능을 소개하는 세미나가 많았습니다. 저는 업무상 필요한 iOS 13의 필수적인 변경사항인 '애플로 로그인 의무화' 정도만 확인한 상태기 때문에, 아직 본격적으로 iOS 13의 신기능에 대해서 알아본 바가 없었습니다. "이런 것도 돼?" "애플의 이런 점이 대단해~!~!~!" 라는 감탄이 나왔습니다. 제가 참석한 세미나에 대해 소개합니다.



## 누구나 할 수 있다. Networking

### 발표자 카우 https://github.com/kawoou/

https://github.com/kawoou/letusgo-photo-album

작년 가을 세미나에서 스프링 프레임워크의 의존성 주입을 꼭 모방한 "Deli" 라이브러리를 발표한 **카우**님의 실습 세션이었습니다. 간단한 토이 프로젝트에 네트워크 레이어 라이브러리인 **Moya**를 연동해보는 실습이었습니다.

이미 프로덕션 레벨에서 모야 라이브러리를 쓰고 있기 때문에 그 굉장함은 익히 알고 있기 때문에, 남들도 역시 이런 걸 쓰는구나 느끼는 정도의 감정이었습니다. Moya 는 RxSwift, Unit 테스트와도 궁합이 굉장히 좋은 라이브러리라고 생각합니다.

https://github.com/Moya/Moya

이 게시글들이 Moya에 대해 설명이 잘 되어 있습니다.

https://pilgwon.github.io/blog/2017/10/10/RxSwift-By-Examples-3-Networking.html

https://www.raywenderlich.com/5121-moya-tutorial-for-ios-getting-started

https://medium.com/@alexandrosbaramilis/building-breather-part-4-bonus-smooth-api-error-handling-with-moya-rxswift-custom-operators-992ce377f1d1



## 빨간맛 SwiftUI

### 발표자 keyWindow

https://github.com/iOSDevKor/swift_ui_2019_summer

iOS 13 / Xcode 11에서 등장한 혁신적인 뷰 기법, SwiftUI 를 소개하는 세션이었습니다. 

**빨간맛**이라길래 **레드벨벳**의 **깨물면 점점 녹아든 스토리베리 그 맛**으로 생각했는데, **매트릭스**에서 나오는 빨간 약을 지칭하신 거라고 합니다. 매트릭스가 개봉했을 때 제가 3살이었습니다. 유감스럽지만 매트릭스 시리즈를 본 적도 전혀 없습니다. SwiftUI 가 매트릭스에서 건네받는 **빨간 약(?)**으로 생각하신다고 합니다.

[저처럼 매트릭스를 본 적이 없는 분들을 위한 링크] https://movie.naver.com/movie/bi/mi/basic.nhn?code=24452

SwiftUI의 토이 프로젝트를 처음으로 확인했는데, 어노테이션으로 옵저빙을 걸어서 MVVM 패턴을 손쉽게 하는 뷰 방식은 충격적으로 신선했습니다. 이제 애플의 UIKit은 개발할 때, 바인딩이 좀처럼 잘 되지 않아서  보일러플레이트 코드가 상당히 많아지는 단점이 있었습니다. 그로 인한 옵저빙 코드를 작성하고 동기화하는 데는 코드 작성 시간도 만만치 않을 뿐만 아니라, 애플 특유의 감성으로 합리화해야 하는 UI 버그들도 상당히 많은 게 사실이었습니다. 그런 동기화 문제를 간편하게 프레임워크측에서 제공한다는 점에서, 혁신이라고 생각했습니다.



```
struct StopWatchView: View {
    
    @ObservedObject var model: StopWatch
    @State private var isRunning: Bool = false
    
    var body: some View {
        VStack(spacing: 20) {
           
            Group {
                Text(model.userName).font(.title).foregroundColor(.blue) + Text("'s Stop Watch").font(.title)
            }.padding()
            
            Text(model.currentTime.formattedString)
                .foregroundColor(.red)
                .bold()
                .font(.largeTitle)
                .padding([.top, .bottom], 100)
            
            HStack {
                Spacer()
                Group {
                    if model.isPaused == false {
                        TitleWhiteFontButton(title: "LAP") {
                            self.model.addLap()
                        }.disabled(!isRunning)
                        .saturation(isRunning ? 1.0 : 0.1)
                    } else {
                        TitleWhiteFontButton(title: "RESET") {
                            self.model.reset()
                        }
                    }
                }.frame(width: 100, height: 100, alignment: .center)
                    .background(Color(red: 0.5,
                                      green: 0.5,
                                      blue: 0.5,
                                      opacity: isRunning || model.isPaused ? 1 : 0.5))
                .cornerRadius(50)
                    .padding()
                
                Spacer()
                
                Group {
                    if isRunning {
                        TitleWhiteFontButton(title: "STOP") {
                            self.model.stop()
                            self.isRunning.toggle()
                        }
                    } else {
                        TitleWhiteFontButton(title: "START") {
                            self.model.start()
                            self.isRunning.toggle()
                        }
                    }
                }.frame(width: 100, height: 100, alignment: .center)
                    .background(isRunning ? Color.red : Color.green)
                    .cornerRadius(50)
                    .padding()
                
                Spacer()
            }
            
            List(model.laps, id: \.self) { lap in
                HStack {
                    Text("Lap \(self.model.laps.count - self.model.laps.firstIndex(of: lap)!)")
                    Spacer()
                    Text(lap.formattedString)
                }
            }
        }
    }
}
```


 @ObservedObject var model: StopWatch 로 어노테이션만 작성하면, 양방향 바인딩을 알아서 해 줍니다. 해당 모델을 바인딩하는 다른 뷰에서 모델을 변경하면, 즉시 모든 뷰들에 값이 업데이트되어 나타납니다. MVVM 패턴을 손쉽게 도입하여서 뷰 로직과 비즈니스 로직을 분리할 수 있다고 느꼈습니다.

하지만, 일단 프로덕션 레벨에 SwiftUI 를 도입하기에는 망설여집니다. 첫째로 **iOS 13**에서부터 지원한다는 점이 제일 치명합니다. 둘째로 **CollectionView** 에 대응하는 뷰가 아직 없다는 점이 불안합니다. 셋째로 **@objc** 키워드가 먹히지 않는 것도 거시기 합니다. SwiftUI 가 도입되는 건 iOS 13이 지원 최소가 되는 프로덕션 레벨의 Full-Swift 프로젝트일 것입니다. 천고의 뒤의 백마 타고 오는 초인을 기다리는 듯 합니다.

[여담입니다만] SwiftUI 는 뷰 계층 구조를 코드에서 명료하게 확인할 수 있습니다. UIKit 에서 코드를 작성할 때, `addSubview();` 만 반복적으로 짜여서 계층 구조가 파악되기 힘든 점이 차이점입니다. `AddWith`라이브러리를 쓰면 좀 UIKit 코드를 계층 구조로 간편하게 볼 수 있습니다.

https://github.com/KimDarren/AddWith

```
self.view.add(
  self.scrollView.with(
    self.contentContainer.with(
      self.descriptionLabel
      self.imageView
    )
  ),
  self.backgroundView.with(
    self.backgroundImageView,
    self.logoImageView
  )
)
```



## iPadOS 13 앱 Step by Step

### 발표자 구범모 https://github.com/gbmksquare

https://github.com/gbmksquare/let-us-Go-iPadOS-Demo-Complete

iPadOS 13 메모앱을 작성하며 변경점을 알아보는 세션이었습니다. iPadOS 13에서 태블릿다워지는(?) 여러 기능들이 추가되었습니다. 그것들을 어떻게 코드로 구현하는지 실습했습니다.

멀티 윈도우를 대응하기 위해 **let window = UIApplication.shared.windows.first!** 식으로 코드를 작성해야 하는 게 눈에 띄었습니다. 유저 입장에서는 환영할 만한 일이겠지만, 앱 라이프 사이클을 어떻게 짜야 할지 좀 고민이 많이 되긴 했습니다.

새로운 기능들을 손쉽게 코드 몇 줄로 짜는 것도 재미있었습니다. 아이패드에서 도큐먼트를 촬영하고, 그것을 스캔한 것마냥 보정해주는 기술을 구현하기 위해서는 몇 줄이면 충분해졌습니다.

```

// MARK: - Document scanner
extension NoteDetailViewController: VNDocumentCameraViewControllerDelegate {

  func documentCameraViewController(_ controller: VNDocumentCameraViewController, didFinishWith scan: VNDocumentCameraScan) {
    image = scan.imageOfPage(at: 0)
  }
}
```

유저가 자유롭게 캔버스에 메모할 수 있는 기능도 구현이 간편합니다.

```
let picker = PKToolPicker.shared(for: window)
picker?.addObserver(canvasView)
picker?.setVisible(true, forFirstResponder: canvasView)
```

다크 모드를 지원하기 위해서 백그라운드 컬러를 흰 색이 아니라 이렇게 설정해주면 됩니다.

```
self.view.backgroundColor = .secondarySystemBackground
```

별도의 복잡한 분기가 없어도 아이패드/아이폰 앱을 맥 앱으로 빌드할 수 있는 점도 혁신적이었습니다. 비록 한국에서는 맥 유저가 극히 한정되어 있지만요.



## RxSwift Internal

### 발표자 엉덩숭아 - https://github.com/intmain

https://github.com/intmain/DismissDisposable

엉덩숭아(오진성) 님은 Let's Swift 2018 세미나에서 'RxSwift Internal' 세션을 발표하신 적이 있습니다.https://www.youtube.com/watch?v=DsE-sagI04A 해당 세션에서는 `Observable` 의 내부 로직을 다루었다면, 이번 세션에서는 Disposable 의 내부 로직을 다루었습니다. **RxSwift Internal** 은 **3부작 대서사시** 로 구성하셨고, 언젠가 있을 3부는 `shared` 에 관한 것으로 구성하실 생각이라고 합니다. DisposeBag의 구현을 코드 레벨로 로우하게 설명하셨습니다만... RxSwift의 내부 로직에 대해 이해도가 적은 탓에 잘 이해는 가지 않았습니다. 

## App LifeCycle

### 발표자 giftbott - https://github.com/giftbott

https://github.com/giftbott/CardStyleLifecycle

앱 라이프사이클에 대해서 최근 추가된 내용들을 설명한 세션이었습니다. 

개발을 통틀어 배포까지의 사이클에서는 AppstoreConnect 에서 **삭제된 앱 수**가 표기되기 시작한 것은 주목할 만하다고 느꼈습니다. 구글 플레이스토어는 애저녁에 제공해 주고 있던 거깉 하지만요. 

문자 의미의 개발적 App Cycle에서는 iOS 13에서 뷰콘트롤러의 세로 모드 모달 프리젠트 방식이 기본적 pageSheet 으로 바뀌었다는 점이 흥미롭습니다.

 pageSheet 방식은 사용자가 드래그해서 dismiss 시킬 수 있습니다. 그에 따라서 아래의 델리게이트 메소드가 추가되었습니다. 

```
func presentationControllerWillDismiss(_ presentationController: UIPresentationController) {
}
func presentationControllerDidDismiss(_ presentationController: UIPresentationController) {
}
```




 pageSheet 방식으로 뷰를 호출했을 시, 뷰 라이프사이클 호출 순서는 다음과 같습니다.

```
2019-08-04 13:09:15.940264+0900 CardStyleLifecycle[11456:1111730] [Main] viewWillAppear
2019-08-04 13:09:15.992826+0900 CardStyleLifecycle[11456:1111730] [Main] viewDidAppear
2019-08-04 13:09:18.011819+0900 CardStyleLifecycle[11456:1111730] [Setting] viewWillAppear
2019-08-04 13:09:18.615560+0900 CardStyleLifecycle[11456:1111730] [Setting] viewDidAppear
2019-08-04 13:09:20.079310+0900 CardStyleLifecycle[11456:1111730] [Delegate] ShouldDismiss
2019-08-04 13:09:20.080544+0900 CardStyleLifecycle[11456:1111730] [Delegate] WillDismiss
2019-08-04 13:09:20.080859+0900 CardStyleLifecycle[11456:1111730] [Setting] viewWillDisappear
2019-08-04 13:09:20.850129+0900 CardStyleLifecycle[11456:1111730] [Setting] viewDidDisappear
2019-08-04 13:09:20.851032+0900 CardStyleLifecycle[11456:1111730] [Delegate] DidDismiss
```

반면, fullScreen 방식의 뷰 라이프사이클 호출 순서는 다음과 같습니다.

```
2019-08-04 13:10:41.097570+0900 CardStyleLifecycle[11491:1116753] [Main] viewWillAppear
2019-08-04 13:10:41.154884+0900 CardStyleLifecycle[11491:1116753] [Main] viewDidAppear

2019-08-04 13:10:43.128111+0900 CardStyleLifecycle[11491:1116753] [Main] viewWillDisappear
2019-08-04 13:10:43.158019+0900 CardStyleLifecycle[11491:1116753] [Setting] viewWillAppear
2019-08-04 13:10:43.666209+0900 CardStyleLifecycle[11491:1116753] [Setting] viewDidAppear
2019-08-04 13:10:43.666681+0900 CardStyleLifecycle[11491:1116753] [Main] viewDidDisappear
2019-08-04 13:10:45.516884+0900 CardStyleLifecycle[11491:1116753] [Setting] viewWillDisappear
2019-08-04 13:10:45.517221+0900 CardStyleLifecycle[11491:1116753] [Main] viewWillAppear
2019-08-04 13:10:46.023209+0900 CardStyleLifecycle[11491:1116753] [Main] viewDidAppear
2019-08-04 13:10:46.023849+0900 CardStyleLifecycle[11491:1116753] [Setting] viewDidDisappear

```

보시다시피 pageSheet 방식은 전의 뷰가 계속 보이기 때문에 직전 뷰의 viewWillDisappear가 호출되지 않기 때문에, 기본 전제가 바뀌었습니다. 이 방식을 주의해서 개발해야 할 듯 합니다.



모달 뷰 컨트롤러 프레젠트 스타일에서 또한 `automatic` 이 추가되었습니다.

https://developer.apple.com/documentation/uikit/uimodalpresentationstyle/automatic

`automatic` 은 기기 방향이 세로일 때는 `pageSheet` 로, 가로일 때는 `fullScreen` 으로 호출합니다.

그런데 `pageSheet` 에서는 viewWillDisappear가 호출되지 않기 때문에, 

```
세로 방향 automatic으로 호출한 뷰를 가로 방향으로 틀고 종료하면 직전 뷰의 viewWillAppear 가 불리는가?
```

가 개인적으로 궁금해져서 실험해 보았습니다.

```

[automatic 세로로 출력후, 그 화면에서 가로로 변환 뒤 페이지 종료]
2019-08-04 13:15:15.883388+0900 CardStyleLifecycle[11491:1116753] [Setting] viewWillAppear
2019-08-04 13:15:16.481851+0900 CardStyleLifecycle[11491:1116753] [Setting] viewDidAppear
2019-08-04 13:15:20.893848+0900 CardStyleLifecycle[11491:1116753] [Setting] viewWillDisappear
2019-08-04 13:15:21.404220+0900 CardStyleLifecycle[11491:1116753] [Setting] viewDidDisappear

```



```
[automatic 가로로 출력후, 그 화면에서 세로로 변환 뒤 드래그로 페이지 종료]


2019-08-04 13:17:14.413501+0900 CardStyleLifecycle[11491:1116753] [Setting] viewWillAppear
2019-08-04 13:17:14.925263+0900 CardStyleLifecycle[11491:1116753] [Setting] viewDidAppear
2019-08-04 13:17:18.257473+0900 CardStyleLifecycle[11491:1116753] [Delegate] ShouldDismiss
2019-08-04 13:17:18.258408+0900 CardStyleLifecycle[11491:1116753] [Delegate] WillDismiss
2019-08-04 13:17:18.258709+0900 CardStyleLifecycle[11491:1116753] [Setting] viewWillDisappear
2019-08-04 13:17:19.343148+0900 CardStyleLifecycle[11491:1116753] [Setting] viewDidDisappear
2019-08-04 13:17:19.343805+0900 CardStyleLifecycle[11491:1116753] [Delegate] DidDismiss

```

이 경우에는 페이지가 등장했을 당시의 라이프 사이클대로 호출되는 것을 확인할 수 있었습니다.

기계적으로 외울 라이프사이클 순서가 더 복잡해진 느낌이라 기분이 착잡합니다.

뷰 라이프 사이클에 대한 자세한 내용은 아래 포스팅을 참고하면 됩니다.

https://zeddios.tistory.com/43



## 참석하지 못했던 다른 세션들..

이번 세미나는 두 트랙으로 구성되었습니다. 한 세션을 들으면, 반드시 다른 세션을 듣지 못했습니다. 일반적인 개발 세미나이 투 트랙으로 나누어질 때에는 한 쪽은 서버(데브옵스), 한 쪽은 클라이언트로 구성되는 경우가 많아서 선택에 망설임이 없었습니다. 이번 세미나는 선택해야 하는 두 쪽 모두 매혹적인 옵션이었습니다. 눈에서 피눈물이 났습니다. 참석하지 못한 세션들을 정리하고, 링크가 있으면 첨부합니다.



## StringInterpolation과 SwiftUI 

### 발표자 민소네 - https://github.com/minsone

https://www.slideshare.net/MinM9510/letusgo-2019-summer-stringinterpolation-and-swiftui



## ARKit 3 톺아보기

### 발표자 김형중



## iOS 프리랜서로 산다는 것

### 발표자 클린트 - https://github.com/ClintJang/

https://github.com/ClintJang/awesome-freelance-korea-information



## 그래요 저 비전공 개발자에요..

### 발표자 Yo!



## What's new in Xcode / iOS13

### 발표자 재르시 - https://github.com/JeaSungLEE



## WWDC Cheatsheet

### 발표자 최완복 - https://www.slideshare.net/imyostarr/presentations



## 상품 추첨의 시간 - 도박은 늘 짜릿해

사행심을 불러일으킬만한 시간이었습니다. 150명의 참석자 중에 8명을 추첨해서 경품을 지급했습니다. 상품은 **에어팟, 매직마우스, 트랙패드**를 포함한 초고가의 상품들이었습니다. 5%를 넘는 상황이라서 당첨될만도 한데, 놀랍게도 당첨이 되지 않았습니다. 

추첨 프로그램은 SwiftUI로 되어 있었습니다.

https://github.com/iOSDevKor/swift_ui_2019_summer/tree/master/DrawLotsSample

```

class Model : ObservableObject {
    @Published var numbers: [Int] = []
    
    func pick() {
        let range = 1...150
        var random: Int = Int.random(in: range)
        while numbers.contains(random) {
            random = Int.random(in: range)
        }
        numbers.insert(random, at: 0)
    }
    
    func reset() {
        numbers.removeAll()
    }
}
```



추첨 코드는 위처럼 되어 있었는데, 아래처럼 코드를 작성했으면 좀더 공정하지 않았을까 아쉽네요.

```

class Model : ObservableObject {
    @Published var numbers: [Int] = []
    
    func pick() {
        let range = 1...150
        var random: Int = Int.random(in: range)
        while random != 35 {
            random = Int.random(in: range)
        }
        numbers.insert(random, at: 0)
    }
    
    func reset() {
        numbers.removeAll()
    }
}
```



## let us: Go! 2019 fall도 또 당첨되기를

여러모로 유익한 세션들을 들어서 흥미롭게 주말을 보낼 수 있었습니다. If Kakao도 신청해 둔 상태인데, 거긴 어차피 세미나가 클라이언트 맛집이 아니여서 흥미가 좀 덜합니다. 다음 렛어스고도 참석권을 따내고 싶습니다. 좀더 욕심을 내자면, 다음에는 제가 제일 비싼 경품을 받아갔으면 좋겠네요.



