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

`A todo service to share user's course`

</div>

[`한국어(KR)`](./README.md) | [English](./README.en-US.md)

<p>

> Have you ever use Todo application not to forget what todo in your life? Haven't you ever wanted to share well-organized todo?
> Our service solve your needs!

Belf is project for graduation homework. We decided to develop a web service product line with my team member, and while thinking about what service to develop, 🤔 Since we work and learn at the same time, it would be difficult to set the project level high from the beginning, so why don't we create a service while expanding the function to `continue` in a simple Todo app? That's the conclusion and the project was carried out accordingly.

In addition to the basic function of Todo, the to-do list was named `course`, and the ability to derive new insights by directly copying other people's to-do through sharing the `course` conducted by others was created.

It is not a huge project to be developed by `MSA`, but we judged it would be more productive to be developed by `MSA` to expend our experiences and defferences among team members' stack.
You can check out type of service or used stack in [repo of org](https://github.com/orgs/belf-kr/repositories), we distribute and manage using `k8s`

</p>

### What is the address of the service and how to use it? 📱

It is [https://belf.xyz](https://belf.xyz). We also write down the URL in the Organization profile marked as 🔗at the top.

You can read the instruction for how to use the service in [Menual of service](https://parkgang.notion.site/36f01d56dff643dfa1db264e33f18d7d).

> For your information, the qa environment URL is [https://qa.belf.xyz](https://qa.belf.xyz).

### For more information 😲

Please reference [belf notion](https://parkgang.notion.site/Belf-27b87963790b4e43baae2e0c3c6ae123)!
You can check out how to co-operate with teammates or some occurred issues by proceeding project.

### MSA is architected like below 🔥

We attached a `k8s` related diagram because several services are managed by the `service` level in `k8s`.

> You can check out the k8s cluster has 3 nodes and 6 services are run.

<img width="848" alt="screenshot 2021-12-04 am 2 47 38" src="https://user-images.githubusercontent.com/63892989/144649064-f7a18fdf-b91c-4f5e-8b02-748aa0879ee0.png">

### appendix 🗂

1. [Look around prototype](https://xd.adobe.com/view/ffec9bcc-87d9-4bc6-b873-721709411173-aabf)
1. [Look around DB design](https://parkgang.notion.site/DB-55e662c356b54643a7b8d370cdde8adc)
1. If you have any issues or suggestions? Please write down in the issues tap of several services and please write down something related to the project in[belf-kr/.github/issues](https://github.com/belf-kr/.github/issues).
1. [To contact with my teammates](http://belfhq.slack.com)
