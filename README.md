<div align="center">
  <h1>2023 OSS-Sinabro
  
  침수감지 CCTV를 통한 관제 시스템</h1>
<p align="center">
  <img src="https://user-images.githubusercontent.com/90829718/264743490-9a2c7c07-c8cd-44f4-9da0-483afa96dc60.jpg" width="150" />
</p>
</div>
<br />

## ✔ Sinabro Project
### "침수 감지 이미지 분류모델" 개발 및 이를 활용한 침수 관제 시스템을 제안하는 프로젝트

<br />

- **개발 배경**

 
>&nbsp;&nbsp;최근 장마철과 호우로 인해 지하차도의 침수 사고 발생률이 급증하였다. 특히, 14명의 사상자를 낸 “오송 지하차도 침수 사고”와 같은 사건에서는 사고 발생 최소 2시간 전에 이미 여러 위험 신호가 감지되었음에도 불구하고, 적절한 차량 통제나 대응 조치가 이루어지지 않았다.
>
>&nbsp;&nbsp;이러한 지하차도 침수 사고는 매년 장마철에 반복적으로 발생하며, 재발 방지 대책이 마련되지 않았다. 이런 문제점을 해결하고자, 침수로 인한 안전사고 예방을 목적으로 침수도로 감지 CCTV 관제 시스템을 개발하게 되었다. 이 시스템은 이미지 분류 기술을 활용해 생성해낸 “침수 감지 인공지능 모델”을 기반으로 하여, 지하차도 도로 표면의 이미지를 실시간으로 분석하여 침수 여부를 판단한다.

<br />

- **개발 목표**

  
>1. "일반도로 / 황토색 침수도로 / 비황토색 침수도로"를 구별하는 이미지 분류모델을 개발한다.
>2. CCTV는 모니터링할 도로 표면을 지정하여 서버와 실시간 통신한다.
>3. 서버는 CCTV별로 수신받은 도로 이미지를 모델을 통해 분류하며, 침수 패턴이 발생한 경우 "관제센터 Webpage"에 해당 CCTV를 업데이트한다.

<br />
<br />

## 🔎 프로젝트 개략도
<p align="center">
  <img src="https://github.com/OSS-Sinabro/Sinabro_Readme/assets/90829718/310736cc-f33e-4a56-b004-f38d3dc962b3" width="600" />
</p>

<br />

## 📌 주요 기능

| **Function** | **Repository** |
|:------------:|:--------------:|
| DeepLearning | 🔗[**Sinabro_DeepLearning**](https://github.com/OSS-Sinabro/Sinabro_DeepLearning) |
| Server       | 🔗[**Sinabro_Server**](https://github.com/OSS-Sinabro/Sinabro_Server) |
| Raspberry Pi | 🔗[**Sinabro_Raspberrypi**](https://github.com/OSS-Sinabro/Sinabro_Raspberrypi) |


<br />


## 🎥시연 영상

> 🔗[**시연 영상**](https://youtu.be/-8Rl-fm9SdU?si=JQ4lKL_gWCzm6yM6)

<img src="https://github.com/OSS-Sinabro/Sinabro_Readme/assets/90829718/c7bb1473-7708-4b18-9645-afa46e4c56e4" width="600" />

<br />
<br />
<br />

## ☑  기대효과
>- **즉각적 대응 가능성** <br />
초기 침수 상황에 즉각적인 대응이 가능하여 재산 피해 및 인명 피해를 예방
>- **안전한 이동 경로 제공** <br />
해당 경로의 운전자에게 안전한 이동 경로를 제공하여 2차 피해를 예방
>- **침수 상황 집중 모니터링** <br />
여러 CCTV를 모니터링하는 관제센터에서 본 시스템을 통해 침수 상황이 발생한 구역만을 집중적으로 파악

## ☑  활용분야
>- **교통 관리 및 재난 대응** <br />
강수량이 많은 상황에서 교통 관리 부서와 재난 대응 센터의 적절한 대응이 가능
>- **스마트 도시 구축** <br />
스마트 도시 구축 과정에서 도시의 안전과 효율성을 향상시키는 요소로 활용
>- **보험 산업과의 협력** <br />
보험 산업과 협력하여 실시간 침수 데이터를 활용하여 보험 사고 대응에 활용

<br />

## 🤝 Team Sinabro
<table>
  <tbody>
    <tr>
      <td align="center"><a href="https://github.com/dj991108"><img src="https://avatars.githubusercontent.com/u/90829718?s=400&u=90d56923e2706f34c55a65af5a57da741856d97f&v=4"width="100px;" alt=""/><br /><sub><b> 팀장 : 김동준 </b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/kyungmin1221"><img src="https://avatars.githubusercontent.com/u/105621255?v=4" width="100px;" alt=""/><br /><sub><b> 팀원  : 박경민 </b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/plopPark"><img src="https://avatars.githubusercontent.com/u/114977536?v=4" width="100px;" alt=""/><br /><sub><b> 팀원 : 박상준 </b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/cyujin"><img src="https://avatars.githubusercontent.com/u/113533845?v=4" width="100px;" alt=""/><br /><sub><b> 팀원 : 최유진 </b></sub></a><br /></td>
      </tr>
  </tbody>
</table>

<br />
