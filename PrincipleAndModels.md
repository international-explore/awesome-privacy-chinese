# 隐私相关原则和模型

1. [隐私相关原则和模型](#隐私相关原则和模型)
    1. [隐私处理模型](#隐私处理模型)
        1. [【FIPP (Fair Information Practice Principles)](https://iapp.org/resources/article/fair-information-practices/)](#fipp-fair-information-practice-principleshttpsiapporgresourcesarticlefair-information-practices)
        2. [OECD privacy principle](#oecd-privacy-principle)
        3. [Generally Accepted Privacy Principles (GAPP)](#generally-accepted-privacy-principles-gapp)
        4. [CIA三原则](#cia三原则)
        5. [Privacy Engineering Objectives (NIST 8062)](#privacy-engineering-objectives-nist-8062)
        6. [NCASE rules](#ncase-rules)

## 隐私处理模型

### 【FIPP (Fair Information Practice Principles)](https://iapp.org/resources/article/fair-information-practices/)
目前呈现的FIPP基于 1973 年美国卫生、教育和福利部的一个咨询委员会提出的建议。该委员会的报告指出，“基于保存记录的相互性概念来保障个人隐私，要求保存记录的组织遵守公平信息惯例的某些基本原则”。随后，然该报告描述了几条数据保护原则。

1980 年，OECD 扩展了这些建议，并将其分为上述八条 FIPP。此后，FIPP 被多次引用，特别是在美国。它们继续作为一个重要部分出现在数据隐私和数据保护准则中。

> FIPP目前基本成为隐私立法的一部分，可以理解为整体框架了。例如，个人参与原则（第 7 条）列出了人们应该拥有的一些权利。 CCPA 将其中一些内容编入法律，例如“知情权”，很像个人参与原则的 a) 和 b) 条款中描述的内容。GDPR 还包括“删除权”，类似于个人参与原则 d) 条款所述的“删除数据”的权力

- 1. **The Collection Limitation Principle（收集限制原则）**. There should be limits to the collection of personal data and any such data should be obtained by lawful and fair means and, where appropriate, with the knowledge or consent of the data subject.
- 2. **The Data Quality Principle（数据质量原则）**. Personal data should be relevant to the purposes for which they are to be used and, to the extent necessary for those purposes, should be accurate, complete and kept up-to-date.
- 3. **The Purpose Specification Principle（目的明确原则）**. The purposes for which personal data are collected should be specified not later than at the time of data collection and the subsequent use limited to the fulfillment of those purposes or such others as are not incompatible with those purposes and as are specified on each occasion of change of purpose.
- 4. **The Use Limitation Principle（使用限制原则）**. Personal data should not be disclosed, made available or otherwise used for purposes other than those specified, except
    - a) with the consent of the data subject, or
    - b) by the authority of law.
- 5. **The Security Safeguards Principle（安全保障原则）**. Personal data should be protected by reasonable security safeguards against such risks as loss or unauthorized access, destruction, use, modification or disclosure of data.
- 6. **The Openness Principle（开放性原则）**. There should be a general policy of openness about developments, practices and policies with respect to personal data. Means should be readily available of establishing the existence and nature of personal data and the main purposes of their use, as well as the identity and usual residence of the data controller.
- 7. **The Individual Participation Principle（个人参与原则）**. An individual should have the right:
    - a) to obtain from a data controller, or otherwise, confirmation of whether or not the data controller has data relating to him;
    - b) to have data relating to him communicated to him, within a reasonable time, at a charge, if any, that is not excessive; in a reasonable manner, and in a form that is readily intelligible to him;
    - c) to be given reasons if a request made under subparagraphs (a) and (b) is denied and to be able to challenge such denial; and
    - d) to challenge data relating to him and, if the challenge is successful, to have the data erased, rectified, completed or amended;
- 8. **The Accountability Principle（可审计原则-也叫问责原则）**. A data controller should be accountable for complying with measures which give effect to the principles stated above.


### [OECD privacy principle](http://oecdprivacy.org/)
OECD 隐私标准是当前普遍适用的针对隐私的的框架，主要包括如下八大部分

- 1. Collection Limitation Principle: 最小化收集原则
- 2. Data Quality Principle: 数据质量保证原则
- 3. Purpose Specification Principle: 目的明确原则
- 4. Use Limitation Principle: 使用限制原则
- 5. Security Safeguards Principle: 安全保障原则
- 6. Openness Principle: 开放原则
- 7. Individual Participation Principle: 用户参与原则
- 8. Accountability Principle: 可审计原则


### [Generally Accepted Privacy Principles (GAPP)](https://linfordco.com/blog/the-10-generally-accepted-privacy-principles/)
类似OECD，是美国和加拿大提出的十条隐私原则
- 1. **Management：可管控可审计原则**. The entity defines, documents, communicates, and assigns accountability for its privacy policies and procedures.
- 2. **Notice.**The entity provides notice about its privacy policies and procedures and identifies the purposes for which personal information is collected, used, retained, and disclosed.
- 3. **Choice and consent：选择和同意原则**. The entity describes the choices available to the individual and obtains implicit or explicit consent with respect to the collection, use, and disclosure of personal information.
- 4. **Collection.收集目的原则** The entity collects personal information only for the purposes identified in the notice.
- 5. **Use, retention, and disposal.限制使用原则**The entity limits the use of personal information to the purposes identified in the notice and for which the individual has provided implicit or explicit consent. The entity retains personal information for only as long as necessary to fulfill the stated purposes or as required by law or regulations and thereafter appropriately disposes of such information.
- 6. **Access.**The entity provides individuals with access to their personal information for review and update.
- 7. **Disclosure to third parties.三方披露原则** The entity discloses personal information to third parties only for the purposes identified in the notice and with the implicit or explicit consent of the individual.
- 8. **Security for privacy.隐私安全** The entity protects personal information against unauthorized access (both physical and logical).
- 9. **Quality.数据质量原则** The entity maintains accurate, complete, and relevant personal information for the purposes identified in the notice.
- 10. **Monitoring and enforcement.监控和强制执行原则** The entity monitors compliance with its privacy policies and procedures and has procedures to address privacy related complaints and disputes.

### [CIA三原则](https://www.techtarget.com/whatis/definition/Confidentiality-integrity-and-availability-CIA)

数据安全方面涉及比较重要的三个原则。

- **confidentiality**: 机密性，只有授权用户可以获取信息。
- **Integrity**: 完整性，信息在输入和传输的过程中，不被非法授权修改和破坏，保证数据的一致性。
- **Availability**: 可用性，保证合法用户对信息和资源的使用不会被不正当地拒绝。

### [Privacy Engineering Objectives (NIST 8062)](https://ethics.berkeley.edu/privacy/resources/privacy-engineering-and-risk-management-nist-8062)

类似与CIA三原则，NIST提出的关于隐私工程师需要关注的三个核心目标，简而言之，要做到可审计、可管控、脱关联。

- **Predicatability**: 可预测，行为在可控范围内。(Enabling of reliable assumptions by individuals, owners, and operators about personal information and its processing by an information system)
- **Manageability**: 可管控，个人信息精细化管理的能力。(Providing the capability for granular administration of personal information including alteration, deletion, and selective disclosure)
- **disassociability**: 可分离，脱关联匿名化。(Enabling the processing of personal information or events without association to individuals or devices beyond the operational requirements of the system)

### NCASE rules
NCASE是FTC提出的关于隐私的一些核心原则，其中NCASE是五个英文单词的缩写

- **Notice**: 关键信息和个数数据使用需要明确告知用户，比如隐私声明，显著披露等。
- **Choice**: 需要给到用户尽可能多的选择权和关闭权，比如个性化广告推送关闭等等。
- **Access**: 可访问或者可携带，也就是用户需要能够访问相关数据，比如数据下载工鞥呢
- **Security**: 保证数据安全，比如传输安全（https），存储安全（数据脱敏）等等
- **Enforcement**: 强制执行，保证可落地、可审计性和强监控


