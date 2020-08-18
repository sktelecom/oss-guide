---
template: overrides/main.html
---

# CLA (Contributor License Agreement)

일반적인 오픈소스 라이선스는 기여자로부터의 라이선싱도 명시하고 있기 때문에 추가적인 Contributor Agreement가 필요하지 않습니다. SK텔레콤이 공개하는 오픈소스 프로젝트는 일반적으로 CLA를 요구하지 않습니다. 다만, 필요에 따라 코드의 법적 문제를 방지하기 위해 기여자에게 CLA나 DCO(Developer Certificate of Origin)를 요구하는 것도 고려할 수 있으며, 이 경우 OSPO에 문의하세요. : <U>_Support (오픈소스 관련)_</U>

CLA와 DCO에 대한 대략적인 사항은 아래 설명을 참고하세요. 

## CLA

어떤 프로젝트는 오픈소스 라이선스만으로는 명시적인 기여 조건이 불확실하다고 생각하기 때문에 모든 기여자에게 명시적인 CLA를 받기를 원합니다. 이정도의 요구사항을 충족할 수 있는 간결한 CLA(Contributor License Agreement)로 OpenJS의 [Individual CLA](https://openjsf.org/wp-content/uploads/sites/84/2019/11/OpenJS-Foundation-Individual-CLA-2019-11-15.pdf)를 참고할 수 있습니다.

## DCO

또 어떤 프로젝트는 개발자에게 그들이 만든 각 Commit에 대한 권한이 있음을 진술하기를 원합니다. [DCO](https://developercertificate.org/) (Developer Certification Origin)는 이런 요구사항을 충족하며, 많은 프로젝트에서 사용하고 있습니다. 

```text 
Developer Certificate of Origin
Version 1.1

Copyright (C) 2004, 2006 The Linux Foundation and its contributors.
1 Letterman Drive
Suite D4700
San Francisco, CA, 94129

Everyone is permitted to copy and distribute verbatim copies of this
license document, but changing it is not allowed.


Developer's Certificate of Origin 1.1

By making a contribution to this project, I certify that:

(a) The contribution was created in whole or in part by me and I
    have the right to submit it under the open source license
    indicated in the file; or

(b) The contribution is based upon previous work that, to the best
    of my knowledge, is covered under an appropriate open source
    license and I have the right under that license to submit that
    work with modifications, whether created in whole or in part
    by me, under the same open source license (unless I am
    permitted to submit under a different license), as indicated
    in the file; or

(c) The contribution was provided directly to me by some other
    person who certified (a), (b) or (c) and I have not modified
    it.

(d) I understand and agree that this project and the contribution
    are public and that a record of the contribution (including all
    personal information I submit with it, including my sign-off) is
    maintained indefinitely and may be redistributed consistent with
    this project or the open source license(s) involved.
```

* 한 예로, Node.js 커뮤니트는 CLA를 사용하다가 [DCO](https://github.com/nodejs/node/blob/master/CONTRIBUTING.md)로 [변경](https://nodejs.org/en/blog/uncategorized/notes-from-the-road/#easier-contribution)하였습니다. 
* GitHub Repository에서 DCO를 자동화하는 간단한 방법은 Bot을 이용하는겁니다.  : [Probot](https://github.com/probot/dco)

### Apache Individual CLA

MIT와 같은 오픈소스 라이선스는 명시적 특허 허여 조항을 포함하지 않습니다. 이런 오픈소스 프로젝트에서 만약 기여자로부터 명시적인 특허 허여를 받고 싶다면 [Apache Individual CLA](https://www.apache.org/licenses/icla.pdf) (Contributor License Agreement)를 사용할 수 있습니다. 이 CLA는 Apache License 2.0과 동일한 특허 허여 조항을 포함합니다. 

### Google CLA

Google의 CLA 전략을 참고하는 것도 도움이 됩니다. : [https://opensource.google/docs/releasing/contributions/](https://opensource.google/docs/releasing/contributions/)

이외에 다음 사항들도 고려할 수 있습니다. 

* 향후 라이선스 변경 필요성을 고려하여 기여자들에게 미리 이에 대한 동의를 받기 위한 내용을 CLA에 포함시킬 수 있습니다. 
* CLA 작성 시, [CLA assistant](https://github.com/cla-assistant/cla-assistant)를 이용하면 기여자의 혼란을 줄일 수 있습니다. 