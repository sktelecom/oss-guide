---
template: overrides/main.html
---

# 오픈소스 라이선스

## 오픈소스란?

오픈소스란 라이선스 방식을 통해 배포된 소스 코드를 자유롭게(freely) 복사, 수정, 사용, 재배포할 수 있는 소프트웨어를 뜻합니다. 오픈소스는 누구라도 버그를 수정하거나 코드를 개조하여 기능을 추가할 수 있으며, 소프트웨어 개발에 참여할 수 있습니다. 이렇게 오픈소스는 개발자에게 프로그램 배포 권리, 소스 코드 접근 권리, 소스 코드 수정 권리를 제공합니다.

## 법적 책임

오픈소스는 잘 활용하면 개발 비용과 기간을 단축할 수 있어 널리 사용되고 있지만 적지 않은 사용자들이 오픈소스 법적 책임과 이에 따른 위험에 대해서는 잘 알지 못합니다. 

* 상용 소프트웨어와 마찬가지로 오픈소스를 사용하기 위해서는 해당 오픈소스의 라이선스를 반드시 준수해야 합니다. 이를 위반할 경우 사용 권리가 박탈되고, 이를 제품화 한 경우 제품을 판매할 수 없습니다. 
* 또한 오픈소스 커뮤니티로부터 클레임을 당하여 라이선스 위반 기업으로 기업 이미지에 큰 손실을 끼칠 수 있습니다.
* 최악의 경우, 법적 소송에 연루될 수 있으므로 오픈소스에 대해 미리 알고 대처하는 것이 중요합니다.

오픈소스의 법적 책임은 오픈소스 라이선스의 종류에 따라 다르므로 오픈소스를 사용할 때에는 각 라이선스의 법적 책임을 반드시 알고 사용해야 합니다.

## 지식재산권

오픈소스에 관한 법적리스크를 이해하기 위해서는 소프트웨어에 관한 지식재산권과 라이선스의 기본적인 개념을 이해할 필요가 있습니다. 오픈소스 라이선스는 소프트웨어 라이선스의 일종이기 때문입니다.   
소프트웨어를 보호하는 법적 장치, 즉 소프트웨어에 관한 지식재산권으로는 저작권, 특허권, 상표권, 영업비밀이 있습니다.

### 저작권 (Copyright) 

* 저작권(Copyright)은 창작물에 대하여 창작자(저작자)가 취득하는 권리로서 창작의 결과물을 보호하며, 창작과 동시에 권리가 발생합니다. 
* 따라서 어떤 프로그래머가 소프트웨어를 개발하면 저작권이 자동적으로 발생하며, 그 권리는 프로그래머 또는 그가 속한 회사에 부여됩니다.  저작권이 있는 저작물은 저작권자의 허락 없이는 누구도 해당 저작물을 복제, 배포, 수정할 수 없습니다.

### 특허권 (Patent) <a id="id-&#xC624;&#xD508;&#xC18C;&#xC2A4;&#xB77C;&#xC774;&#xC120;&#xC2A4;-&#xD2B9;&#xD5C8;&#xAD8C;(Patent)"></a>

* 특허권(Patent)은 발명에 관하여 발명자(특허권자)가 갖는 독점 배타권입니다.
* 저작권과는 달리 일정한 방식으로 출원을 해야 하며, 심사를 통과한 후 등록되어야만 권리가 발생합니다.  특허기술을 사용하기 위해서는 반드시 특허권자의 허락을 얻어야만 합니다. 
* 특허받은 방식을 구현하는 소프트웨어라면 프로그래밍 언어에 상관없이 특허권의 범위에 속합니다. 

<figure>
  <img src="/assets/copyright.png"  />
  <figcaption>오픈소스라이선스가이드 3.0 / 한국저작권위원회</figcaption>
</figure>

## 소프트웨어 라이선스 <a id="id-&#xC624;&#xD508;&#xC18C;&#xC2A4;&#xB77C;&#xC774;&#xC120;&#xC2A4;-&#xC18C;&#xD504;&#xD2B8;&#xC6E8;&#xC5B4;&#xB77C;&#xC774;&#xC120;&#xC2A4;"></a>

소프트웨어에 대한 독점배타권을 가진 권리자는 다른 사람들이 해당 소프트웨어를 사용하거나 배포하는것을 허락할 수 있습니다. 간단히 말해 라이선스는 자신의 저작물을 다른 사람이 사용, 복사, 수정, 배포 등을 할 수 있도록 허가하는 것을 말합니다.

일반적인 상용 소프트웨어는 그 대가로 로열티를 요구합니다.

## 오픈소스 라이선스 <a id="id-&#xC624;&#xD508;&#xC18C;&#xC2A4;&#xB77C;&#xC774;&#xC120;&#xC2A4;-&#xC624;&#xD508;&#xC18C;&#xC2A4;&#xB77C;&#xC774;&#xC120;&#xC2A4;"></a>

일반 상용소프트웨어와 마찬가지로 오픈소스에도 저작권 등 지식재산권이 있습니다.  그래서 권리자의 허락 없이 함부로 사용하면 소송을 당할 수 있습니다.  
그런데 오픈소스의 권리자들은 많은 사람들이 자유롭게 사용할 수 있도록 광범위한 라이선스를 부여하고 있습니다.  예를 들어 사용자들에게 사용에 대한 권리 뿐만 아니라 마음대로 복제 및 배포를 할 수 있도록 하고, 소스코드까지 제공하여 마음대로 수정할 수 있도록 허락합니다. 이를 위해서는 이러한 권한을 명시적으로 나타내는 오픈소스 라이선스가 필요합니다. 따라서, 오픈소스 라이선스가 적용되지 않은 소프트웨어는 오픈소스가 아니며, 저작권자를 제외한 누구도 그 소프트웨어를 사용, 복제, 수정 및 배포할 수 없습니다.

!!! warning
    여기서 주의해야 할 점은, GitHub에 공개된 프로젝트라고 해서 오픈소스인 것은 아닙니다. GitHub의 Public 프로젝트는 [GitHub’s Terms of Service](https://help.github.com/en/github/site-policy/github-terms-of-service#3-ownership-of-content-right-to-post-and-license-grants)가 적용되어서 다른 사람들이 나의 프로젝트를 보거나 Fork 할 수는 있지만 다른 권한은 부여하지 않습니다. 오픈소스 프로젝트라면 많은 사람들이 자유롭게 사용, 수정, 배포하고 또다시 기여할 수 있도록 오픈소스 라이선스가 적용돼야 합니다.

### 라이선스가 없는 코드라면?

만약 코드에 라이선스가 명시되어 있지 않다면, 그 코드를 사용할 수 있는 권리는 여전히 저작권자에게만 있다는 것입니다. 따라서, 우리는 그 코드를 사용할 권리가 없습니다. 그 코드를 회사의 제품 혹은 서비스에 포함시킬 수 없습니다. 꼭 필요한 코드라면 코드의 저작자에게 연락하여 다음과 같이 요청하세요.

```
"We’d love to use this code in a project of ours and wanted to make sure that you 
are OK with it. Would you be willing to add an OSI-approved license like the MIT or 
the Apache License to the project so that we know this is really open source?"
```

대부분의 저작자들은 이에 대해 긍정적으로 대응할 것입니다.

오픈소스 라이선스는 상용 소프트웨어처럼 그에 따르는 로열티는 요구하지 않으며, 대신 소스 코드 제공 등 몇 가지 지켜야할 의무사항을 요구합니다.

## 주요 의무 사항

오픈소스의 의무사항을 이해하고 준수하는 것은 중요합니다. 오픈소스 라이선스의 일반적으로 의무사항은 고지와 소스 코드 공개입니다.

!!! note
    단, 대부분의 오픈소스 라이선스는 오픈소스를 배포(distribute) 할 때 의무사항을 부과합니다. 즉, 사외로 배포하는 소프트웨어 혹은 모델 내에 포함된 오픈소스에 대해서만 의무 사항 준수가 필요합니다. 예를 들어 오픈소스를 사내에서 테스트 용도로 사용한다면, 의무사항은 부과되지 않습니다.

### 저작권 표시 및 라이선스 고지

대부분의 오픈소스 라이선스는 개발자 또는 기여자에 관한 사항과 저작권에 관한 사항을 제품에 표시하거나 포함하도록 요구하며, 이용자들이 오픈소스에 관한 권리를 잘 이해할 수 있도록 배포자로 하여금 해당 라이선스의 사본을 함께 첨부할 것을 요구하고 있습니다.

```text
ex) 
Apache License 2.0
 
4. a. You must give any other recipients of the Work or Derivative Works a copy of
this License;
 
4. c. You must retain, in the Source form of any Derivative Works that You distribute,
all copyright, patent, trademark, and attribution notices from the Source form of the
Work, excluding those notices that do not pertain to any part of the Derivative Works;
```

### 소스코드 공개

대표적으로 GPL 계열의 라이선스는 바이너리 형태로의 소프트웨어 배포를 허용하는 대신, 바이너리에 해당하는 소스코드를 함께 공개할 것을 요구합니다. 

```text
ex) 
GPL 2.0
 
3. You may copy and distribute the Program (or a work based on it, under Section 2) in
object code or executable form under the terms of Sections 1 and 2 above provided that
you also do one of the following:
 a) Accompany it with the complete corresponding machine-readable source code,
```

### 재배포시 동일 라이선스 적용

라이선스에 따라 큰 차이를 보이는 부분은 'Copyleft' 에 관한 사항입니다.  GPL을 대표로 하는 Copyleft 라이선스들은 이용자들이 소프트웨어를 수정한 후 배포하고자 할 때 수정된 소프트웨어도 동일한 License로 배포할 것을 요구합니다.

```text
ex) 
GPL 2.0
 
2. You may modify your copy or copies of the Program or any portion of it, thus forming
a work based on the Program, and copy and distribute such modifications or work under
the terms of Section 1 above, provided that you also meet all of these conditions:
 b) You must cause any work that you distribute or publish, that in whole or in part
contains or is derived from the Program or any part thereof, to be licensed as a whole
at no charge to all third parties under the terms of this License.
```

## 오픈소스 라이선스 유형

오픈소스 라이선스를 분류하는 방법에는 여러 관점이 있을 수 있지만, 여기에서는 Copyleft, Weak Copyleft, Permissive로 나눠서 설명합니다. 

### Copyleft 라이선스

Copyleft 라이선스 유형은 오픈소스 라이선스 중에 요구하는 의무사항이 가장 많은 라이선스 유형이기 때문에 이 유형의 라이선스로 배포되는 오픈소스는 사용 시 주의가 필요합니다.

!!! danger
    * 대표적인 의무 사항은 이 라이선스로 배포되는 오픈소스를 제품에 포함하여 배포하려면 해당 오픈소스의 소스 코드의 공개가 필요합니다. 또한 이 오픈소스와 결합하는 소스 코드까지도 동일한 오픈소스 라이선스를 적용하여 공개해야 합니다. ‌
    * 따라서, _**Copyleft 라이선스 유형의 라이선스가 적용된 오픈소스는 SK텔레콤이 배포하는 제품에 포함 시 주의해야 합니다. 이러한 오픈소스는 설계 단계에서부터 Build 시 자사 소프트웨어와 통합되지 않도록 하고, Runtime에도 독립된 프로세스로 동작되도록 해야 합니다.**_  


Copyleft 라이선스 유형으로 분류할 수 있는 오픈소스 라이선스는 다음과 같습니다.

* BCL
* [Creative Commons “Attribution-ShareAlike” (CC BY-SA) and “Attribution-NoDerivs” (CC BY-ND) licenses](http://creativecommons.org/licenses/)
* [GNU Classpath’s GPL + exception](http://www.gnu.org/software/classpath/license.html)
* [GNU GPL v1, v2, v3](http://opensource.org/licenses/gpl-license.php)
* [GNU LGPL v2.1, v3](http://opensource.org/licenses/lgpl-license.php) (단, LGPL이 적용된 컴포넌트를 [dynamically-linked](https://opensource.google/docs/thirdparty/licenses/#LinkingRequirements) 형태로 사용할 경우, 자사 코드를 공개하지 않는 방식으로 사용할 수 있습니다.).
* Netscape Public License [NPL 1.0](http://www.mozilla.org/MPL/NPL/1.0/) and [NPL 1.1](http://www.mozilla.org/MPL/NPL/1.1/)
* [OSL](http://opensource.org/licenses/osl-2.1.php)
* [QPL](http://opensource.org/licenses/qtpl.php)
* [Sleepycat License](http://opensource.org/licenses/sleepycat.php)‌

이와 같이 소스 코드 공개 의무를 요구하는 Copyleft 라이선스 하의 오픈소스를 포함하는 소프트웨어를 배포할 경우, 사용자에게 소스 코드를 직접 제공하거나, 사용자가 요청시 소스 코드를 제공하겠다는 서면 약정서를 제공해야 합니다. 이에 대한 세부 절차 및 방법은 다음 가이드를 참고하세요. : _오픈소스 컴플라이언스_

### Weak Copyleft 라이선스

Weak copyleft 라이선스 유형은 Copyleft 라이선스 유형과 동일한 의무사항 준수를 요구하지만 한 가지 중요한 예외를 갖고 있습니다. Weak Copyleft 라이선스 유형의 라이브러리를 사용하여 소프트웨어를 배포할 경우, 해당 라이브러리의 소스 코드만 공개하면 됩니다 (단, 해당 라이브러리의 수정사항은 공개 범위에 포함됩니다.). 즉, GPL 등의 Copyleft 라이선스 유형과는 달리 Weak Copyleft 라이선스 유형의 라이브러리를 사용하는 다른 소프트웨어는 동일한 라이선스로 소스 코드를 공개해야 할 의무가 없습니다.

Weak Copyleft 라이선스 유형으로 분류할 수 있는 오픈소스 라이선스는 다음과 같습니다.

* Common Development and Distribution License [CDDL 1.0](http://opensource.org/licenses/cddl1.php), _CDDL 1.1_
* _CeCILL-C License_
* [CPL 1.0](http://opensource.org/licenses/cpl1.0.php)
* [EPL 1.0](http://opensource.org/licenses/eclipse-1.0.php) and [EPL 2.0](https://opensource.org/licenses/EPL-2.0) (Eclipse Public License)
* [IPL 1.0](http://opensource.org/licenses/ibmpl.php) (IBM Public License)
* Mozilla Public License [MPL 1.0](http://opensource.org/licenses/mozilla1.0.php), [MPL 1.1](http://opensource.org/licenses/mozilla1.1.php), and [MPL 2.0](http://opensource.org/licenses/MPL-2.0)
* [Apple Public Source License (APSL) 2.0](http://opensource.org/licenses/apsl-2.0.php)
* _Ruby_

LGPL의 경우, Dynamic Link하여 사용할 경우, Weak Copyleft 라이선스 유형으로 간주하여 사용할 수 있습니다.

### Permissive 라이선스

Permissive 라이선스 유형은 제한이 거의 없어서 상대적으로 준수하기가 쉬운 라이선스이며, 일반적으로 저작권 표시, 라이선스 고지 등의 고지 의무 준수를 요구하기 때문에 소프트웨어를 외부 배포 시에는 라이선스가 요구하는 고지를 해야 합니다.

Permissive 라이선스로 분류할 수 있는 오픈소스 라이선스는 다음과 같습니다.

* Academic Free License: [AFL 2.1](http://web.archive.org/web/20060428203736/http://opensource.org/licenses/afl-2.1.php) and [AFL 3.0](http://opensource.org/licenses/AFL-3.0)
* [Apache License 2.0](http://apache.org/licenses/LICENSE-2.0)
* [Artistic License 1.0](http://opensource.org/licenses/artistic-license-1.0) and [Artistic License 2.0](http://opensource.org/licenses/artistic-license-2.0)
* [ASL 1.1](http://apache.org/licenses/LICENSE-1.1) (Apache Software License 1.1)
* [Autodesk DWF Toolkit](http://usa.autodesk.com/adsk/servlet/item?siteID=123112&id=5522878)
* [Boost Software License](http://www.boost.org/users/license.html)
* [BSD (occasionally referred to as the “University of California” license)](https://opensource.org/licenses/bsd-license.php)
* [BSD 3-clause (sometimes called BSD-new)](https://opensource.org/licenses/BSD-3-Clause)
* [BSD + Patent](https://opensource.org/licenses/BSDplusPatent)
* [BSD - AES variant](https://web.archive.org/web/20190806093009/https://fedoraproject.org/wiki/Licensing:BSD#AES_Variant)
* [Creative Commons “Attribution” (CC BY) license](http://creativecommons.org/licenses/)
* _JSON License_ (MIT license with the added note: “The Software shall be used for Good, not Evil.”)
* [Eclipse Distribution License (BSD variant)](https://www.eclipse.org/org/documents/edl-v10.php)
* [FreeType Project License](http://freetype.sourceforge.net/FTL.TXT)
* [ISC License](http://opensource.org/licenses/ISC)
* [libjpeg-turbo](http://bazaar.launchpad.net/~tom-gall/libjpeg-turbo/trunk/view/1/README)
* [LibTIFF](http://www.remotesensing.org/libtiff/misc.html)
* [Lucent Public License 1.02 (used by Plan 9 now, but different from “the Plan 9 license”)](http://cm.bell-labs.com/plan9/license.html)
* [Microsoft Public License (MS-PL)](http://opensource.org/licenses/MS-PL)
* [MIT/X11/Expat](http://opensource.org/licenses/mit-license.php)
* [MIT adapted by CMU](https://web.archive.org/web/20190922104304/https://fedoraproject.org/wiki/Licensing:MIT?rd=Licensing/MIT#CMU_Style)
* [NCSA](http://opensource.org/licenses/UoI-NCSA.php)
* [OpenSSL](http://www.openssl.org/source/license.html)
* [PHP License 2.02](http://www.php.net/license/2_02.txt) and [3.0](http://www.php.net/license/3_0.txt)
* _PostgreSQL License_
* [Python Imaging Library (PIL) License](https://web.archive.org/web/20190921164759/http://www.pythonware.com/products/pil/license.htm)
* [TCP Wrappers](http://www.blackberry.com/support/blackberrypresenter/opensourcefiles/LICENSE-BSD-LIBWRAP.TXT)
* [Python Software Foundation](http://www.python.org/download/releases/2.3.2/license/)
* [STLport License](https://web.archive.org/web/20190804123932/http://www.stlport.org/doc/license.html)
* [TCP Wrappers](http://www.blackberry.com/support/blackberrypresenter/opensourcefiles/LICENSE-BSD-LIBWRAP.TXT)
* [Unicode, Inc. License Agreement - Data Files and Software](http://www.unicode.org/copyright.html#Exhibit1)
* [Universal Permissive License (UPL), Version 1.0](http://opensource.org/licenses/UPL)
* [W3C Software license](http://opensource.org/licenses/W3C.php)
* [X.Net](http://opensource.org/licenses/xnet.php)
* [Zend Engine License, v2.00](http://www.zend.com/license/2_00.txt)
* [zlib/libpng](http://opensource.org/licenses/zlib-license.php)
* [ZPL](http://opensource.org/licenses/zpl.php)

이와 같이 고지 의무를 요구하는 Permissive 라이선스 하의 오픈소스를 포함하는 소프트웨어를 배포할 경우, "저작권 표시", "라이선스 고지" 등의 의무를 준수해야 합니다. 예를 들어, SK텔레콤이 배포하는 모바일 애플리케이션은 요구되는 고지 사항을 "About" 페이지를 통해 제공할 수 있습니다.

‌세부 절차는 다음 가이드를 참고하세요. : <U>_SK텔레콤 오픈소스 컴플라이언스 프로세스_</U>

## _사용 제한 라이선스_

일부 오픈소스 라이선스는 SK텔레콤의 제품에 사용하기에 적합하지 않은 조건을 포함하고 있습니다.

### Network 서비스 제한 라이선스

AGPL, SSPL은 Network 서비스도 배포로 간주하여 의무사항 준수를 요구하는 조항을 포함합니다. 이에 따라 Network 서비스를 제공하는 서버에 AGPL로 공개된 오픈소스가 포함되어 있다면, 소프트웨어를 배포하지 않아도, AGPL 오픈소스 뿐만 아니라 함께 링크되어 동작하는 다른 소프트웨어의 소스코드 까지 AGPL로 공개해야 하는 의무가 발생합니다. 이 경우, SK텔레콤의 핵심 서버 프로그램까지도 AGPL로 공개해야 하는 위험이 있습니다. 따라서, SK텔레콤의 제품 및 서비스 개발 시, AGPL 및 SSPL 등의 오픈소스 라이선스가 적용된 오픈소스는 사용할 수 없습니다. 

이러한 Network 서비스 시 조건을 부여하는 라이선스는 다음과 같습니다.

* AGPL (GNU Affero General Public License)
* SSPL (Server Side Public License)

이러한 라이선스 하의 오픈소스를 반드시 포함해야 하는 경우라면 OSPO(Open Source Program Office)에 포함할 수 있는 방법을 문의하세요. : <U>_Support (오픈소스 관련)_</U>

### 비상업용 라이선스 

연구, 학습만을 위해서라고 해도 SK텔레콤 내에서 사용한다면 상업적인 활동으로 간주될 수 있습니다. 따라서 비상업적으로만 사용할 수 있도록 제한하는 라이선스에 따라 공개된 오픈소스는 SK텔레콤에서 사용할 수 없습니다. 이러한 비상업용 (Non-Commercial) 라이선스는 다음과 같습니다.‌

* CC BY-NC
* CC BY-NC-SA
* CC BY-NC-ND

### 이외 언급되지 않은 라이선스 

위에서 분류되지 않은 라이선스가 적용된 오픈소스를 SK텔레콤의 제품에 사용하기 위해서는 사전 검토가 필요합니다. OSPO(Open Source Program Office)에 사용 가능 여부를 문의하세요. :  <U>_Support (오픈소스 관련)_</U>