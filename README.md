
* Spring 백엔드 개발자
* 홍익대학교 컴퓨터공학과 2019.03~
* [LIVID](https://github.com/Learning-Is-Vital-In-Development) 백엔드 책 스터디 2023.01 ~
* 큐시즘 27기 2023.03~2023.05
* Pawith 2023.07~

# 기술 스택

## Language&Framework

<img src="https://img.shields.io/badge/java-6DB33F?style=flat-square&logo=java&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=Spring&logoColor=white"/></a>
<img src="https://img.shields.io/badge/SpringJpa-6DB33F?style=flat-square&logo=Spring&logoColor=white"/></a>
<img src="https://img.shields.io/badge/springsecurity-6DB33F?style=flat-square&logo=springsecurity&logoColor=white"/></a>

## DB
<img src="https://img.shields.io/badge/mysql-4479A1?style=flat-square&logo=mysql&logoColor=white"/></a>
<img src="https://img.shields.io/badge/redis-DC382D?style=flat-square&logo=redis&logoColor=white"/></a>
<img src="https://img.shields.io/badge/H2-4479A1?style=flat-square&logo=H2&logoColor=white"/></a>

## Infra

<img src="https://img.shields.io/badge/amazonec2-FF9900?style=flat-square&logo=amazonec2&logoColor=white"/></a>
<img src="https://img.shields.io/badge/amazonrds-527FFF?style=flat-square&logo=amazonrds&logoColor=white"/></a>
<img src="https://img.shields.io/badge/amazons3-569A31?style=flat-square&logo=amazons3&logoColor=white"/></a>
<img src="https://img.shields.io/badge/docker-2496ED?style=flat-square&logo=docker&logoColor=white"/></a>
<img src="https://img.shields.io/badge/github-181717?style=flat-square&logo=github&logoColor=white"/></a>
<img src="https://img.shields.io/badge/githubactions-2088FF?style=flat-square&logo=dogithubactionscker&logoColor=white"/></a>


# 프로젝트

2022.11~ : 개발자, 취준생, 대학생들의 스터디 모임 : [DevMatching](https://github.com/radar19/DevMatching)

<details>
  <summary>2023.03~ : 🐶반려동물과 함께한 시간들의 기록 : 
    <a href = "https://github.com/KUSITMS-27th-TEAM3/BackEnd">펫모리🐶</a> 
  </summary>
  <div markdown="1">

* redis와 spring의 @Cacheable을 통해 카운트 쿼리와 같이 일부 쿼리를 캐싱하였음 → 앨범 정보 100건 조회시 30%(200ms -> 150ms) 성능향상
* 애플리케이션 서비스에서 도메인 서비스를 조합하여 하나의 기능을 만드는 퍼사드 패턴을 사용하여 코드 재사용성을 높였으며 순환참조 가능성을 줄임
* 스프링 이벤트의 강력한 추상화를 통해 물리적 의존성을 논리적 의존성으로 변경하여 서비스 클래스의 의존성의 수를 줄임
* 모든 컨트롤러, 서비스에 대한 테스트를 작성하여 예상하지 못한 상황 발생을 막을 수 있었음
  </div>
</details>

* 큐시즘 우수상(3등)

<details>
  <summary >2023.07~ : 함께 이뤄가는 애완 공유 TODO 서비스 : 
    <a href = "https://github.com/TEAM-SAMSION/Backend">Pawith</a>
  </summary>
  <div markdown="1">
    
  <details>
    <summary>성능 개선</summary>
    
    * 이미지 업로드 + 팀 생성 API 개선
      * 리팩터링 전 : 이미지 업로드 API + 팀 생성 API, 동시100명 요청 평균 160ms
      * 리팩터링 후 : 이미지 업로드(비동기) + 팀 생성 API , 동시 100명 요쳥 평균 98.3ms(60% 개선)

    * Todo 완료율 API 개선
      * 리팩터링 전 : 동시 100명 요청 평균 426ms
      * 리팩터링 후 : 동시 100명 요청 평균 67ms (535% 개선)

    * Todo 조회 API 개선
      * 리팩터링 전 : 동시 100명 요청 평균 915ms
      * 리팩터링 후 : 동시 100명 요청 평균 85ms(914% 성능개선)
   
    * Todo 모임 조회 API 개선
      * 리팩터링 전 : 동시 100명 요청 평균 202ms
      * 리팩터링 후 : 동시 100명 요청 평균 88ms(129% 성능개선)
  
    * Todo 모임 이름 조회 API 개선
      * 리팩터링 전 : 동시 100명 요청 평균 225ms
      * 리팩터링 후 : 동시 100명 요청 평균 63ms(257% 성능개선)

    * 카테고리 하위 Todo 조회 API 개선(테스트 데이터 24000개 레코드)
      * 리팩터링 전 : 단건 조회 41000ms
      * 리팩터링 후 : 단건 조회 800ms(5025% 성능 개선)

  </details>
  
  </div>
</details>

* 캠퍼스타운 창업동아리 네트워크 창업캠프 입상(3등)


# 스터디

2023.01 ~ 2023.03    : [Object 스터디](https://github.com/Learning-Is-Vital-In-Development/23-1-Objects) (LIVID)

2023.01 ~ 2023.03    : [Effective-Java 스터디](https://github.com/Learning-Is-Vital-In-Development/23-4-effective_java) (LIVID)

2023.07 ~ 2023.09    : [Head First Design Patterns 스터디](https://github.com/Learning-Is-Vital-In-Development/23-13-DesignPattern) (LIVID) 

2023.07 ~ 2023.10    : [Optimizing Java 스터디](https://github.com/JSON-loading-and-unloading/Optimizing-Java) 

2023.07 ~            : [알고리즘 스터디(진행중)](https://github.com/JSON-loading-and-unloading/Algorithm)

2023.10 ~ 2023.12    : [도커 교과서](https://github.com/Learning-Is-Vital-In-Development/23-16-docker-textbook-2)

2023.11 ~            : [오브젝트 (진행중)](https://github.com/JSON-loading-and-unloading/Object-Study)


