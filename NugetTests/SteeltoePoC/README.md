# PoC: Steeltoe를 활용한 Eureka 서비스 디스커버리 연결
## 📌 목적

* .NET 애플리케이션에서 **Steeltoe 라이브러리**를 활용하여 **Eureka 서버**와 연동 가능성을 검증한다.
* 마이크로서비스 환경에서 서비스 등록 및 검색이 정상적으로 이루어지는지 확인한다.

---

## ⚙️ 환경 구성

* **프로그래밍 언어**: .NET 8
* **라이브러리**: Steeltoe Discovery (Eureka Client)
* **서비스 디스커버리 서버**: Spring Cloud Netflix Eureka
* **빌드/실행 환경**: Docker, Docker Compose

---

## 🔑 주요 기능

1. **서비스 등록 (Service Registration)**

   * .NET 애플리케이션이 기동될 때 Eureka 서버에 본인의 인스턴스를 등록한다.

2. **서비스 검색 (Service Discovery)**

   * 다른 서비스의 정보를 Eureka 서버에서 조회 가능하다.
   * 로드 밸런싱 및 동적 서비스 호출에 활용 가능하다.

---