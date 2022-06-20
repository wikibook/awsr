# sbcntr-resources

서적용 각종 자원 다운로드 리포지토리다.

## 리포지토리 구성

```bash
❯ tree . -d 1
.
├── cicd
├── cloudformations
├── cloud9
├── fargate-bastion
├── firelens
├── iam
└── scan
```


각 디렉토리와 책의 관계는 다음과 같다.

| 디렉토리        | 관련된 부분                                                    | 내용                                               |
|-----------------|------------------------------------------------------------|--------------------------------------------------|
| cicd            | 5-2 운영 설계:Code 시리즈를 사용한 CI/CD                   | CI/CD설계에서 이용할 빌드 정의와 태스크 정의 등       |
| cloudformations | 4-2 네트워크 구축, 4-4 컨테이너 레지스트리 구축, 4-5 오케스트레이터 구축, 부록 1| 실습 및 부록에서 이용하는 CloudFormation                      |
| cloud9          | 4-4 컨테이너 레지스트리 구축 | resize.sh |
| fargate-bastion | 5-7 운영 설계:Fargate를 이용한 Bastion 구축                     | Fargate Bastion에서 이용하는Bastion컨테이너 설정|
| firelens        | 5-6 운영 설계 & 보안 설계: 로그 수집 기반                       | 로그 수집 기반 FireLens 컨테이너에 설정할 로그 관련 설정|
| iam             | 4, 5장 전반                                                    | 4장과 5장에서 이용하는 각종 IAM 정책의 JSON 내용 |
| scan            | 5-8 보안 설계: Trivy/Dockle 을 이용한 보안 확인 | DevSecOps 구현을 위한 CodeBuild 빌드 정의|

