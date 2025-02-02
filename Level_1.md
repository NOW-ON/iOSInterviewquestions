# 레벨 1

| 질문 | 윤여진 | 홍석준 |
| --- | --- | --- |
| **1. Swift에서 옵셔널(Optional)이란 무엇이며, 언제 사용해야 하나요?**<br>- 옵셔널 바인딩과 강제 언래핑의 차이점은 무엇인가요?<br>- 옵셔널 체이닝의 동작 원리는 무엇이며, 어떻게 사용하나요?<br>- 암시적 언래핑 옵셔널(Implicitly Unwrapped Optional)은 어떤 경우에 사용해야 하나요? | | |
| **2. iOS 앱의 생명주기(App Life Cycle)에 대해 설명해주세요.**<br>- 앱의 각 상태(`Not Running`, `Inactive`, `Active`, `Background`, `Suspended`)에서 가능한 작업은 무엇인가요?<br>- 상태 변화에 따라 호출되는 `AppDelegate` 또는 `SceneDelegate` 메서드는 무엇인가요?<br>- 백그라운드에서 작업을 완료하기 위한 방법은 어떤 것이 있나요? | | |
| **3. Auto Layout을 사용하는 이유와 장점은 무엇인가요?**<br>- 제약 조건(Constraints)의 우선순위(Priority)는 어떻게 동작하나요?<br>- Intrinsic Content Size란 무엇이며, 어떻게 활용되나요?<br>- Ambiguous Layout과 Unsatisfiable Constraints는 무엇이며, 어떻게 해결하나요? | | |
| **4. Swift에서 클로저(Closure)란 무엇이며, 어떻게 사용하나요?**<br>- 클로저의 캡처(Capture) 기능은 무엇인가요?<br>- @escaping 클로저와 non-escaping 클로저의 차이점은 무엇인가요?<br>- 트레일링 클로저(Trailing Closure) 문법은 어떤 경우에 유용한가요? | | |
| **5. iOS에서 Delegate 패턴은 무엇이며, 어떤 상황에서 사용되나요?**<br>- Delegate 패턴과 Notification, KVO의 차이점은 무엇인가요?<br>- 프로토콜을 활용한 Delegate 패턴 구현 방법을 설명해주세요. | | |
| **6. Swift의 기본 데이터 타입과 컬렉션(Collection) 타입에는 어떤 것들이 있나요?**<br>- 값 타입(Value Type)과 참조 타입(Reference Type)의 차이점은 무엇인가요?<br>- 구조체(Struct)와 클래스(Class)의 사용 시기는 어떻게 구분하나요?<br>- 열거형(Enum)의 원시값(Raw Value)과 연관값(Associated Value)은 무엇인가요? | | |
| **7. Xcode에서 디버깅 시 자주 사용하는 기능은 무엇인가요?**<br>- 중단점(Breakpoint)의 종류와 활용 방법을 설명해주세요.<br>- LLDB 콘솔에서 유용한 명령어는 어떤 것이 있나요? | | |
| **8. iOS 앱에서 데이터를 저장하는 방법에는 어떤 것들이 있나요?**<br>- `UserDefaults`의 사용 시 주의할 점은 무엇인가요?<br>- Keychain은 어떤 데이터를 저장하기에 적합한가요?<br>- Core Data와 SQLite의 차이점은 무엇이며, 각각 언제 사용하면 좋나요? | | |
| **9. Swift에서 프로토콜(Protocol)이란 무엇이며, 어떻게 활용하나요?**<br>- 프로토콜의 요구사항은 무엇인가요?<br>- 프로토콜 확장(Protocol Extension)을 사용하는 이유는 무엇인가요?<br>- 프로토콜 지향 프로그래밍(Protocol-Oriented Programming)의 장점은 무엇인가요? | | |
| **10. Swift의 접근 제어자(Access Control Levels)에 대해 설명해주세요.**<br>- `open`과 `public`의 차이점은 무엇인가요?<br>- `internal`, `fileprivate`, `private`의 사용 시기는 어떻게 결정하나요?<br>- 접근 제어자를 사용하는 이유는 무엇인가요? | | |
| **11. iOS 앱에서 네트워크 통신을 하는 방법에는 어떤 것들이 있나요?**<br>- `URLSession`의 기본 사용 방법을 설명해주세요.<br>- 네트워크 요청 시 에러 처리는 어떻게 하나요?<br>- 서드파티 라이브러리(예: Alamofire)를 사용하는 이유는 무엇인가요? | | |
| **12. 의존성 관리 도구(CocoaPods, Carthage, Swift Package Manager)의 종류와 차이점은 무엇인가요?**<br>- 각 도구의 사용 방법과 장단점을 설명해주세요.<br>- 의존성 관리를 통해 얻을 수 있는 이점은 무엇인가요? | | |
| **13. Swift의 고차 함수(Higher-Order Functions)에 대해 설명해주세요.**<br>- `map`과 `flatMap`의 차이점은 무엇인가요?<br>- `filter`, `reduce` 함수는 어떤 경우에 사용하나요?<br>- `compactMap`은 어떤 역할을 하나요? | | |
| **14. Git에서 브랜치(Branch)를 사용하는 이유와 장점은 무엇인가요?**<br>- 브랜치를 병합(Merge)하는 방법에는 어떤 것들이 있나요?<br>- 브랜치 전략(예: Git Flow, GitHub Flow)에 대해 설명해주세요.<br>- 충돌(Conflict)이 발생했을 때 해결 방법은 무엇인가요? | | |
| **15. Swift의 에러 처리 방법에 대해 설명해주세요.**<br>- `throws`, `try`, `catch` 키워드의 사용 방법은 무엇인가요?<br>- 옵셔널을 사용한 에러 처리와 `do-catch`를 사용하는 에러 처리의 차이는 무엇인가요?<br>- 에러를 전파하는 방법은 무엇인가요? | | |
| **16. 메모리 관리에서 강한 참조(Strong Reference)와 약한 참조(Weak Reference)의 차이점은 무엇인가요?**<br>- 순환 참조(Retain Cycle)가 발생하는 경우와 해결 방법은 무엇인가요?<br>- 클로저에서 `[weak self]`와 `[unowned self]`의 차이는 무엇인가요? | | |
| **17. iOS 앱에서 Multi-threading을 구현하는 방법은 무엇인가요?**<br>- `DispatchQueue`와 `OperationQueue`의 차이점은 무엇인가요?<br>- 동시성 프로그래밍에서 Race Condition을 방지하는 방법은 무엇인가요?<br>- 메인 스레드에서 UI 업데이트를 해야 하는 이유는 무엇인가요? | | |
| **18. UIKit에서 TableView와 CollectionView의 차이점은 무엇인가요?**<br>- 셀(Cell)의 재사용(Reusability)은 어떻게 구현되나요?<br>- 동적인 셀 높이(Dynamic Cell Height)를 설정하는 방법은 무엇인가요?<br>- CollectionView의 레이아웃을 커스터마이징하는 방법은 무엇인가요? | | |
| **19. ARC(Automatic Reference Counting)의 동작 원리는 무엇인가요?**<br>- Retain Cycle이 발생하지 않도록 방지하는 방법은 무엇인가요?<br>- `deinit` 메서드는 언제 호출되며, 어떤 역할을 하나요? | | |
| **20. 상속(Inheritance)과 프로토콜(Protocol)의 차이점은 무엇인가요?**<br>- 클래스 상속을 사용할 때의 장단점은 무엇인가요?<br>- 다중 상속(Multiple Inheritance)이 불가능한 이유는 무엇인가요?<br>- 프로토콜 준수(Conformance)를 통해 다형성을 구현하는 방법은 무엇인가요? | | |
| **21. 사용자 인터페이스(UI) 테스트와 단위(Unit) 테스트의 차이점은 무엇인가요?**<br>- XCTest 프레임워크를 사용하여 테스트를 작성하는 방법은 무엇인가요?<br>- 테스트 주도 개발(TDD)의 장점은 무엇인가요?<br>- 의존성 주입(Dependency Injection)을 활용하여 테스트 가능한 코드를 작성하는 방법은 무엇인가요? | | |
| **22. Xcode에서 Instruments를 사용하여 앱의 성능을 분석하는 방법은 무엇인가요?**<br>- Time Profiler를 사용하여 성능 이슈를 찾는 방법을 설명해주세요.<br>- Allocations Instrument를 사용하여 메모리 누수를 탐지하는 방법은 무엇인가요?<br>- Leaks Instrument를 사용하여 메모리 누수를 찾는 방법은 무엇인가요? | | |
| **23. Swift의 제네릭(Generic)에 대해 설명해주세요.**<br>- 제네릭을 사용하는 이유는 무엇인가요?<br>- 제네릭 타입 파라미터와 제약 조건을 설정하는 방법은 무엇인가요?<br>- 제네릭을 사용할 때의 장점과 주의할 점은 무엇인가요? | | |
| **24. Swift의 클로저와 함수의 차이점은 무엇인가요?**<br>- 클로저가 일급 객체(First-Class Citizen)인 이유는 무엇인가요?<br>- 함수형 프로그래밍 패러다임에서 클로저가 어떻게 활용되나요? | | |
| **25. 동시성 프로그래밍에서 동기(Synchronous)와 비동기(Asynchronous)의 차이점은 무엇인가요?**<br>- iOS에서 비동기 작업을 처리하는 방법은 무엇인가요?<br>- 세마포어(Semaphore)와 뮤텍스(Mutex)의 차이점은 무엇인가요? | | |
| **26. GCD(Grand Central Dispatch)의 주요 개념과 사용 방법을 설명해주세요.**<br>- 직렬(Serial) 큐와 동시(Concurrent) 큐의 차이는 무엇인가요?<br>- 글로벌 큐(Global Queue)와 메인 큐(Main Queue)는 어떻게 다르나요?<br>- DispatchWorkItem을 사용하는 방법은 무엇인가요? | | |
