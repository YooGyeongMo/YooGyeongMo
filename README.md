<h1 align="center">안녕?,Hi I'm Demian 👋</h1>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=200&section=header&text=GyeongMo%20Yoo%20🌊&fontSize=40&animation=twinkling" />
</p>

```swift
import UIKit
import SwiftUI

struct GyeongMoYoo: Developer {
    let name = "Yoo Gyeong Mo"
    let username = "YooGyeongMo"
    let mainFocus = ["Swift", "UIKit", "SwiftUI"]
    let currentDeepDive = ["UIKit Animation", "iOS Pomodoro App", "Core Animation"]

    let awards = [
        "🏆 Collab - Android App 기획/디자인/개발 - 지학인재원장상, ICT 코딩 부문 우수상",
        "🥇 PyModi Smart of IoT - 인공지능혁신공유대학 금상",
        "🎖️ STARTMATCH - 대경권 해커톤 지학인재원장상",
        "📱 MediEye - 공공 API 기반 약물 정보 앱",
        "🧠 MyChatBot - ChatGPT 기반 데스크탑 챗봇",
        "🗺️ Safty Paris - React + Firebase 전체 웹 구축"
    ]
    
    let techStack = TechStack(
        strongLanguages: ["Kotlin", "Python (알고리즘)", "JavaScript"],
        knowledgeable: ["C++", "C#", "Java"],
        android: ["Compose", "Navigation", "Coroutines", "Room", "Retrofit2", "RxJava"],
        frontend: ["HTML", "CSS", "React", "Node.js"],
        apis: ["Kakao SDK", "Google Auth", "Naver Login", "Google Maps", "Geocode API", "Public Pill API"],
        design: ["Figma", "Mobbin", "Photoshop", "Blender"],
        collaboration: ["Git", "GitHub", "Jira"]
    )

    func introduce() {
        print("안녕하세요, 유저를 위한 앱을 고민하는 개발자 Yoo Gyeong Mo입니다.")
        print("Swift, UIKit, SwiftUI를 집중적으로 공부하고 있으며, 감각을 되찾는 몰입 타이머 앱을 개발 중입니다.")
    }
}
