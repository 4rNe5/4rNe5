# (ProjectName)App.swift 파일이 하는 일

---

```swift
//만들면 대충 이렇게 나온다
import SwiftUI

@main
struct (ProjectName)App: App {
    var body: some Scene {
        WindowGroup {
            ContentView()
        }
    }
}
```

## `(ProjectName)App.swift` 파일은

SwiftUI 앱에서 앱의 진입점(`entry point`)을 정의하는 파일이다. 이 파일에서는 `@main` 어노테이션을 사용하여 앱의 진입점을 지정하고, 앱의 기본 설정을 구성할 수 있다. 

`@main` 어노테이션을 사용하여 앱의 진입점을 지정할 때, 해당 어노테이션이 있는 클래스에서 `App` 프로토콜을 구현해야 한다. `App` 프로토콜은 SwiftUI 앱에서 필요한 최소한의 요구사항을 정의하고 있으며, `body` 프로퍼티를 통해 앱의 화면을 구성한다.

`@main` 어노테이션이 있는 클래스에서는 `App` 프로토콜을 구현하면서, 앱의 기본 설정을 구성할 수 있다. 예를 들어, `App` 프로토콜에서는 앱의 윈도우(window)와 루트 뷰(root view)를 설정할 수 있고, 또한, 앱의 /라이프사이클 이벤트(lifecycle event)를 처리할 수 있다.

따라서, `(ProjectName)App.swift` 파일은 SwiftUI 앱에서 앱의 진입점을 지정, 앱의 기본 설정을 구성하는 중요한 파일이다. 이 파일에서 앱의 기본 설정을 구성하면, 앱의 전반적인 동작을 제어할 수 있다.