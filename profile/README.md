<p align="center">
  <table align="center">
    <tbody>
      <tr>
        <td>
          <img src="https://user-images.githubusercontent.com/63892989/144641795-319226e1-b98a-4876-be67-e1d14c11d8a3.png" alt="screenshot" width="500" />
        </td>
        <td>
          <img src="https://user-images.githubusercontent.com/63892989/144641821-b6e00be9-350f-433d-9d36-951241ddaf71.png" alt="screenshot" width="500" />
        </td>
      </tr>
    </tbody>
  </table>
  <h1 align="center">
    ✨ Belf ✨
  </h1>
</p>
<div align="center">

`사용자의 코스를 공유하는 Todo 서비스`

</div>
<p>

> 일상생활에서 할 일을 까먹지 않기 위해서 Todo 앱을 사용해 보신 적이 있으신가요? 규칙적으로 잘 정리된 Todo를 공유해 보고 싶지 않은가요?  
> 저희의 서비스가 그 고민을 해결해 드립니다!

belf는 졸업 과제를 위해 진행된 프로젝트입니다. 팀원과 함께 웹 서비스 제품군을 개발하기로 정했으며 어떤 서비스를 개발할 까 고민하던 도중 🤔 우리는 일과 학습을 병행하기 때문에 처음부터 프로젝트 레벨을 높게 잡으면 힘들 텐데 간단한 Todo 앱에 `지속적` 으로 기능을 확장하면서 서비스를 만들어 보면 어떨까? 라는 결론을 도출하였고 그에 맞게 진행된 프로젝트입니다.

Todo의 기본적인 기능과 더불어 할일의 목록을 `코스` 라고 명명하여 다른 사람이 진행하는 `코스` 를 공유를 통해 다른 사람의 할일을 직접 따라해보면서 새로운 insight를 도출할 수 있는 기능이 탄생하였습니다.

이외 `MSA` 를 적용할 만큼 규모가 큰 프로젝트는 아니지만 한번 적용해보고 싶기도 하고 팀원들의 stack이 모두 달라서 `MSA` 형태로 개발하는 것이 더 생산적이라는 판단하에 `MSA` 형태로 개발되었습니다.
서비스 종류 및 사용된 stack은 [org의 repo](https://github.com/orgs/belf-kr/repositories) 를 통해 살펴보실 수 있으며 `k8s` 으로 서비스를 배포 및 관리하였습니다.

</p>

### 서비스 접속 주소 및 사용법은? 📱

[https://belf.xyz](https://belf.xyz) 입니다. 맨 위에 🔗으로 지정 된 Organization Profile의 URL에도 적어놓았어요.

서비스 사용법은 [서비스 사용 매뉴얼](https://parkgang.notion.site/36f01d56dff643dfa1db264e33f18d7d) 에 작성되어있어요.

> 참고로 qa 환경은 [https://qa.belf.xyz](https://qa.belf.xyz) 랍니다.

### 이외 더 자세한 내용은 😲

[belf notion](https://parkgang.notion.site/Belf-27b87963790b4e43baae2e0c3c6ae123) 을 참고해주세요!
어떻게 팀원과 협업했는지 프로젝트를 진행하면서 발생한 이슈와 같은 내용이 작성되어 있습니다.

### MSA는 아래와 같이 구성되어 있어요 🔥

각각의 서비스는 `k8s` 의 `service` level으로 관리되기 때문에 `k8s` 관련 다이어그램을 첨부하였습니다.

> k8s cluster는 3개 Node를 가지고 있으며 6개의 서비스가 돌아가는 것을 확인할 수 있어요!

<img width="848" alt="스크린샷 2021-12-04 오전 2 47 38" src="https://user-images.githubusercontent.com/63892989/144649064-f7a18fdf-b91c-4f5e-8b02-748aa0879ee0.png">

### 부록 🗂

1. [프로토타이핑 구경하기](https://xd.adobe.com/view/ffec9bcc-87d9-4bc6-b873-721709411173-aabf)
1. [DB 설계 구경하기](https://parkgang.notion.site/DB-55e662c356b54643a7b8d370cdde8adc)
1. 이슈 및 건의사항이 있다면? 각 서비스의 issues 탭을 통해서 남겨주시고 프로젝트와 관련된 내용은 [belf-kr/.github/issues](https://github.com/belf-kr/.github/issues) 에 남겨주세요.
1. [저희 팀원와 소통하고 싶다면?](http://belfhq.slack.com)
