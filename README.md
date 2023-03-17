### Hi there👋 I'm mobile app developer using IOS.

<!--
**Seokwon5/Seokwon5** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->    
📱 Platforms & Languages   
<img src="https://img.shields.io/badge/IOS-000000?style=flat-square&logo=IOS&logoColor=white"/>   
<img src="https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=Swift&logoColor=white"/>   
   
🔧 Tools    
<img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=white"/> 

# Resume


안녕하세요 🙇🏻 

IOS 개발자 이석원 입니다.

__프로그래밍 언어 Swift__ 와 swiftUI__ 에 관심이 많고 꾸준히 공부하고 있습니다.

* Email : tjrdnjs5@gmail.com

## Education

* 동국대학교 경주캠퍼스 컴퓨터공학과 4학년 졸업 
  * 2016.03 ~ 2022.02

* 서울경신고등학교 졸업
  * 2011.03 ~ 2014.02
  
## Skills

* Programming Language
  * Swift
  * SwiftUI

## Projects

### [렘비]

* __친구들의 MBTI를 저장해두고 관리하는 어플리케이션__

* [AppStore 다운로드]

* SwiftUI를 공부하면서 진행한 개인 프로젝트

* 기간

    * 2023.01 ~ ing (리팩토링하며 계속 서비스 중)
    
* 역할

    * __ CoreData 적용__
        
        앱 내에 사람들의 이름과 성격을 저장하기 위해 알아보던 중 소량의 데이터를 저장하는 앱 특성을 고려하여 데이터 베이스가 아닌 Core Data라는 프레임 워크를 사용하여 
        
        데이터를 저장하고 삭제하고 수정하는 기능을 구축하였습니다. 
       
        NSManagedObject라는 관리객체에 데이터를 담아 FetchRequst로 데이터를 불러들이고 list에 담아 이용자들이 편하게 볼 수 있도록 ui를 구축하였습니다.

    * __같은 MBTI를 가진 사람들을 모아보기__

        MBTI를 저장한 뒤, 같은 성격을 가진 사람들을 모아보는 기능을 만들어 이용자들이 성격별로 지인들을 한눈에 볼 수 있도록 모든 MBTI성격모델을 만들고 CoreData안의 mbti객체와
        
        같은 성격일 경우에만 뿌려주는 FetchResult 데이터 구조를 만들던 중, predicate에 조건문을 달았을 경우 MBTI모델을 읽기 전 FetchRequest가 먼저 실행 되는 오류를 
        
        해결하기 위해 구글링을 하여 init메소드를 따로 설정하는 방법으로 먼저 predicate 조건을 읽고 그 뒤에 fetchRequest가 실행되도록 하였습니다.


    * __가장 많은 성격을 순위로 보기__

        현재 이용자들이 자신의 친구들은 어떤 MBTI를 가장 많이 가지고 있는지 한눈에 볼 수 있도록 성격 순위를 매기기 위해 count를 이용하여 성격마다 개수를 파악한 뒤 List에 뿌려주는 기능을
        
        CoreData에 있는 mbti객체안에서 어떻게 String값으로 뽑아낼지, AppStorage를 써서 저장 단계에서 따로 저장을 할지에 대해 앞으로 리펙토링 단계에서 넣을 계획으로 있습니다. 



<br></br>





마지막 수정일 : 2023/03/18

