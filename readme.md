
![sheetseeimg](img/next-sheetsee.png)

### Sheetsee.js is a client-side library for connecting Google Spreadsheets to a website and visualizing the information with tables and charts.

---

**This repository is for the [project website](http://jlord.github.io/sheetsee.js) and provides a [compiled version sheetsee.js](./js/sheetsee.js).** Use the compiled version if you want _all_ of what is available in Sheetsee. If you want just the parts that you're going to use in your project and nothing more, you can [build a custom version](./docs/building.md).

**Each part of Sheetsee has its own repository and issues should be opened there.** General issues/pull requests for the site are OK here.

### Repositories for Sheetsee Components

| Component              | Description                                                                                            | Repo                         |
| ------------------- | --------------------------------------------------------------------------------------------------- | ---------------------------- |
| `sheetsee`   | Command line module for building a custom version of Sheetsee.           | [jlord/sheetsee](https://github.com/jlord/sheetsee)   |
| `sheetsee-core`   | **Included in every build**. Has helpful working-with-your-data functions.           | [jlord/sheetsee-core](https://github.com/jlord/sheetsee-core)   |
| `sheetsee-tables` | Contains everything you'll need to create a table including sortable columns, pagination and search. Uses Mustache.js templating.| [jlord/sheetsee-tables](https://github.com/jlord/sheetsee-tables) |
| `sheetsee-maps`   | For making maps with your point, line or polygon spreadsheet data. Uses Leaflet.js and Mustache.js.              | [jlord/sheetsee-maps](https://github.com/jlord/sheetsee-maps)   |

![sheetseeimg](img/next-sheetsee.png)

### Sheetsee.js is a client-side library for connecting Google Spreadsheets to a website and visualizing the information with tables and charts.

---

**This repository is for the [project website](http://jlord.github.io/sheetsee.js) and provides a [compiled version sheetsee.js](./js/sheetsee.js).** Use the compiled version if you want _all_ of what is available in Sheetsee. If you want just the parts that you're going to use in your project and nothing more, you can [build a custom version](./docs/building.md).

**Each part of Sheetsee has its own repository and issues should be opened there.** General issues/pull requests for the site are OK here.

### Repositories for Sheetsee Components

| Component              | Description                                                                                            | Repo                         |
| ------------------- | --------------------------------------------------------------------------------------------------- | ---------------------------- |
| `sheetsee`   | Command line module for building a custom version of Sheetsee.           | [jlord/sheetsee](https://github.com/jlord/sheetsee)   |
| `sheetsee-core`   | **Included in every build**. Has helpful working-with-your-data functions.           | [jlord/sheetsee-core](https://github.com/jlord/sheetsee-core)   |
| `sheetsee-tables` | Contains everything you'll need to create a table including sortable columns, pagination and search. Uses Mustache.js templating.| [jlord/sheetsee-tables](https://github.com/jlord/sheetsee-tables) |
| `sheetsee-maps`   | For making maps with your point, line or polygon spreadsheet data. Uses Leaflet.js and Mustache.js.              | [jlord/sheetsee-maps](https://github.com/jlord/sheetsee-maps)   |
# 自动链接引用和 URL

对 URL、议题、拉取请求和提交的引用会自动缩短并转换为链接。

## URL

GitHub 通过标准 URL 自动创建链接。

`Visit https://github.com`

![呈现的 GitHub Markdown 的屏幕截图，其中显示了 URL 如何呈现为蓝色可单击链接“访问 https://github.com”。](/assets/images/help/writing/url-autolink-rendered.png)

有关创建链接的详细信息，请参阅“[基本写作和格式语法](/zh/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#links)”。

## 议题和拉取请求

在 GitHub 上的对话中，对议题和拉取请求的引用将自动转换为短链接。

> \[!NOTE]
> 在存储库的 wiki 或文件中没有创建自动链接的引用。

| 引用类型                                                                                   | 原始引用                                             | 短链接 |
| -------------------------------------------------------------------------------------- | ------------------------------------------------ | --- |
| 问题或拉取请求 URL                                                                            | <https://github.com/jlord/sheetsee.js/issues/26> |     |
| [#26](https://github.com/jlord/sheetsee.js/issues/26)                                  |                                                  |     |
| `#` 和问题或拉取请求编号                                                                         | #26                                              |     |
| [#26](https://github.com/jlord/sheetsee.js/issues/26)                                  |                                                  |     |
| `GH-` 和问题或拉取请求编号                                                                       | GH-26                                            |     |
| [GH-26](https://github.com/jlord/sheetsee.js/issues/26)                                |                                                  |     |
| `Username/Repository#` 和问题或拉取请求编号                                                      | jlord/sheetsee.js#26                             |     |
| [jlord/sheetsee.js#26](https://github.com/jlord/sheetsee.js/issues/26)                 |                                                  |     |
| `Organization_name/Repository#` 和问题或拉取请求编号                                             | github-linguist/linguist#4039                    |     |
| [github-linguist/linguist#4039](https://github.com/github-linguist/linguist/pull/4039) |                                                  |     |

如果在列表中引用问题、拉取请求或讨论，则引用将展开以显示标题和状态。 有关任务列表的详细信息，请参阅“[关于任务列表](/zh/get-started/writing-on-github/working-with-advanced-formatting/about-task-lists)”。

## 标签

在 Markdown 中引用标签的 URL 时，标签会自动呈现。 仅呈现同一存储库的标签，指向不同存储库标签的 URL 将呈现为任何 [URL](/zh/get-started/writing-on-github/working-with-advanced-formatting/autolinked-references-and-urls#urls)。

通过导航到标签页并单击标签，可找到标签的 URL。 例如，公共[文档存储库](https://github.com/github/docs/)中标签“增强”的 URL 为

```markdown
https://github.com/github/docs/labels/enhancement
```

> \[!NOTE]
> 如果标签名称包含句点 (`.`)，则标签不会从标签 URL 自动呈现。

## 提交 SHA

对提交 SHA 哈希的引用会自动转换为指向 GitHub 上提交的短链接。

| 引用类型                                                                                            | 原始引用                                                                                                                                                                           | 短链接                                                                                                                 |
| ----------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------- |
| 提交 URL                                                                                          | [`https://github.com/jlord/sheetsee.js/commit/a5c3785ed8d6a35868bc169f07e40e889087fd2e`](https://github.com/jlord/sheetsee.js/commit/a5c3785ed8d6a35868bc169f07e40e889087fd2e) |                                                                                                                     |
| [a5c3785](https://github.com/jlord/sheetsee.js/commit/a5c3785ed8d6a35868bc169f07e40e889087fd2e) |                                                                                                                                                                                |                                                                                                                     |
| 安全哈希算法 (SHA)                                                                                    | a5c3785ed8d6a35868bc169f07e40e889087fd2e                                                                                                                                       |                                                                                                                     |
| [a5c3785](https://github.com/jlord/sheetsee.js/commit/a5c3785ed8d6a35868bc169f07e40e889087fd2e) |                                                                                                                                                                                |                                                                                                                     |
| User\@SHA                                                                                       | jlord\@a5c3785ed8d6a35868bc169f07e40e889087fd2e                                                                                                                                | [jlord@a5c3785](https://github.com/jlord/sheetsee.js/commit/a5c3785ed8d6a35868bc169f07e40e889087fd2e)               |
| `Username/Repository@SHA`                                                                       | `jlord/sheetsee.js@a5c3785ed8d6a35868bc169f07e40e889087fd2e`                                                                                                                   | [`jlord/sheetsee.js@a5c3785`](https://github.com/jlord/sheetsee.js/commit/a5c3785ed8d6a35868bc169f07e40e889087fd2e) |

### 引用提交 SHA 的故障排除

从提交消息内部的专用存储库引用提交时，仅当提交的至少一个作者或提交者对所引用的提交具有读取访问权限时，提交 SHA 才会进行短链接。

## 自定义外部资源的自动链接

如果自定义自动链接引用配置用于仓库，则对外部资源（如 JIRA 议题或 Zendesk 事件单）的引用将转换为缩短的链接。 要了解在您的仓库中哪些自动链接可用，请联系拥有仓库管理员权限的人。 有关详细信息，请参阅“[配置自动链接以引用外部资源](/zh/repositories/managing-your-repositorys-settings-and-features/managing-repository-settings/configuring-autolinks-to-reference-external-resources)”。

## 避免指向所链接参考资料的反向链接

默认情况下，引用将生成反向链接。 例如，如果手动在拉取请求中链接到议题，则将自动在议题中生成反向链接到该拉取请求的另一个链接\_\_。
为避免此行为，在引用中构建 URL 时，可以使用 `redirect.github.com` 而不是 `github.com`。 如果在引用链接中使用 `redirect.github.com` URL，则在悬停时将不会显示弹出窗口。

> \[!NOTE]
> 在具有数据驻留的 GitHub Enterprise Cloud (`ghe.com`) 环境中，此方法不受支持。

## 其他阅读材料

* [基本写作和格式语法](/zh/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)# 关于 Enterprise Managed Users

了解企业如何从标识提供者 (dP) 管理 GitHub 上用户的生命周期和身份验证。

## GitHub中的企业托管用户是什么？

通过 Enterprise Managed Users，可以**从外部标识管理系统或 IdP** 管理 GitHub.com 或 GHE.com 上的用户的生命周期和身份验证。

* 你的 的 IdP 在 GitHub 上**预配新用户帐户**，该帐户有权访问企业。
* 用户必须在 **IdP 上进行身份验证**，才能访问 GitHub 上的企业资源。
* 可以通过 IdP 控制**用户名、个人资料数据、组织成员身份和存储库访问权限**。
* 如果企业使用 OIDC SSO，GitHub 将使用 IdP 的**条件访问策略 (CAP)** 验证对企业及其资源的访问。 请参阅“[关于对 IdP 的条件访问策略的支持](/zh/enterprise-cloud@latest/admin/identity-and-access-management/using-enterprise-managed-users-for-iam/about-support-for-your-idps-conditional-access-policy)”。
* 托管用户帐户 **无法在企业外部创建公共内容**或进行协作。 请参阅“[托管用户帐户的功能和限制](/zh/enterprise-cloud@latest/admin/identity-and-access-management/understanding-iam-for-enterprises/abilities-and-restrictions-of-managed-user-accounts)”。

> \[!NOTE] Enterprise Managed Users 并不是每名客户的最佳解决方案。 要确定是否适合你的企业，请参阅 [为 GitHub Enterprise Cloud 选择企业类型](/zh/enterprise-cloud@latest/admin/identity-and-access-management/understanding-iam-for-enterprises/choosing-an-enterprise-type-for-github-enterprise-cloud)。

## EMU 如何与标识管理系统集成？

GitHub 合作伙伴与身份管理系统的一些开发人员合作，提供与 Enterprise Managed Users 的“铺好道路”集成。 为了简化配置并确保获得全面支持，请使用单个合作伙伴 IdP 进行身份验证和预配。\*\*\*\*

### 什么是合作伙伴标识提供者？

合作伙伴 IdP 使用 SAML 或 OIDC 提供身份验证，并提供跨域身份管理系统 (SCIM) 的配置。

<div class="ghd-tool rowheaders">

| 合作伙伴 IdP     | SAML                                                                                                                                                                                                                                                                                                                      | OIDC                                                                                                                                                                                                                                                                                                                                                                                                                         | SCIM                                                                                                                                                                                                                                                                                                                      |
| :----------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Entra ID     | <svg version="1.1" width="16" height="16" viewBox="0 0 16 16" class="octicon octicon-check" aria-label="check icon" role="img"><path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path></svg> | <svg version="1.1" width="16" height="16" viewBox="0 0 16 16" class="octicon octicon-check" aria-label="check icon" role="img"><path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path></svg>                                                                                                    | <svg version="1.1" width="16" height="16" viewBox="0 0 16 16" class="octicon octicon-check" aria-label="check icon" role="img"><path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path></svg> |
| Okta         | <svg version="1.1" width="16" height="16" viewBox="0 0 16 16" class="octicon octicon-check" aria-label="check icon" role="img"><path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path></svg> | <svg version="1.1" width="16" height="16" viewBox="0 0 16 16" class="octicon octicon-x" aria-label="x icon" role="img"><path d="M3.72 3.72a.75.75 0 0 1 1.06 0L8 6.94l3.22-3.22a.749.749 0 0 1 1.275.326.749.749 0 0 1-.215.734L9.06 8l3.22 3.22a.749.749 0 0 1-.326 1.275.749.749 0 0 1-.734-.215L8 9.06l-3.22 3.22a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042L6.94 8 3.72 4.78a.75.75 0 0 1 0-1.06Z"></path></svg> | <svg version="1.1" width="16" height="16" viewBox="0 0 16 16" class="octicon octicon-check" aria-label="check icon" role="img"><path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path></svg> |
| PingFederate | <svg version="1.1" width="16" height="16" viewBox="0 0 16 16" class="octicon octicon-check" aria-label="check icon" role="img"><path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path></svg> | <svg version="1.1" width="16" height="16" viewBox="0 0 16 16" class="octicon octicon-x" aria-label="x icon" role="img"><path d="M3.72 3.72a.75.75 0 0 1 1.06 0L8 6.94l3.22-3.22a.749.749 0 0 1 1.275.326.749.749 0 0 1-.215.734L9.06 8l3.22 3.22a.749.749 0 0 1-.326 1.275.749.749 0 0 1-.734-.215L8 9.06l-3.22 3.22a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042L6.94 8 3.72 4.78a.75.75 0 0 1 0-1.06Z"></path></svg> | <svg version="1.1" width="16" height="16" viewBox="0 0 16 16" class="octicon octicon-check" aria-label="check icon" role="img"><path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path></svg> |

</div>

使用单个合作伙伴 IdP 进行身份验证和预配时，GitHub 支持合作伙伴 IdP 上的应用程序，还支持与 GitHub 的 IdP 集成。

### 是否可以使用受支持合作伙伴以外的标识管理系统？

如果无法使用单个合作伙伴 IdP 进行身份验证和预配，则可使用其他身份管理系统或系统组合。 系统必须：

* 遵循 **GitHub** 的集成准则
* 使用 SAML 提供**身份验证**，遵循 SAML 2.0 规范
* 提供**使用 SCIM 进行用户生命周期管理**功能，遵守 SCIM 2.0 规范并与 GitHub 的 REST API 通信（请参阅“[使用 REST API 通过 SCIM 预配用户和组](/zh/enterprise-cloud@latest/admin/identity-and-access-management/provisioning-user-accounts-for-enterprise-managed-users/provisioning-users-with-scim-using-the-rest-api)”）

GitHub 没有明确支持混合合作伙伴 IdP 来进行身份验证和预配，而且未测试所有身份管理系统。 **GitHub 的支持团队可能无法协助你解决与混合或未测试的系统相关的问题。** 如果需要帮助，必须咨询系统的文档、支持团队或其他资源。

> \[!IMPORTANT] 用于 SSO 和 SCIM 的 Okta 与 Entra ID 的组合显式不受支持\*\*\*\*\*\*\*\*。 如果配置这种组合，GitHub的 SCIM API 将在预配尝试时向标识提供者返回错误。

## 如何管理 EMU 的用户名和配置文件信息？

GitHub 通过对 IdP 提供的标识符进行标准化，自动为每个开发人员创建用户名。 如果在规范化期间删除标识符的唯一部分，则可能会发生冲突。 请参阅“[外部身份验证的用户名注意事项](/zh/enterprise-cloud@latest/admin/identity-and-access-management/managing-iam-for-your-enterprise/username-considerations-for-external-authentication#resolving-username-problems)”。

IdP 提供了 托管用户帐户 的个人资料名称和电子邮件地址：

* 托管用户帐户 \_无法\_更改 GitHub 上的档案名称或电子邮件地址。
* IdP 只能提供一个电子邮件地址。
* 若更改 IdP 中的用户电子邮件地址，会从与用户旧电子邮件地址关联的贡献历史记录中取消链接该用户。

## 如何管理 EMUs 的角色和访问权限？

在 IdP 中，你可以为每个 托管用户帐户 提供**企业中的一个角色**，例如成员、所有者或来宾协作者。 请参阅“[企业中角色的能力](/zh/enterprise-cloud@latest/admin/user-management/managing-users-in-your-enterprise/roles-in-an-enterprise)”。

可手动管理组织成员身份（以及存储库访问权限），也可**使用 IdP 组自动更新成员身份**。 请参阅“[使用标识提供者组管理团队成员身份](/zh/enterprise-cloud@latest/admin/identity-and-access-management/using-enterprise-managed-users-for-iam/managing-team-memberships-with-identity-provider-groups)”。

## 托管用户帐户 如何在 GitHub 上进行身份验证？

托管用户帐户 可向 GitHub 进行身份验证的位置取决于配置身份验证的方式（SAML 或 OIDC）。 请参阅“[Enterprise Managed Users 身份验证](/zh/enterprise-cloud@latest/authentication/authenticating-with-single-sign-on/authenticating-with-a-managed-user-account)”。

默认情况下，当未经身份验证的用户尝试访问你的企业时，GitHub 将显示 404 错误。 你可以选择性地启用自动重定向到单一登录 (SSO)。 请参阅“[在企业中强制执行安全设置策略](/zh/enterprise-cloud@latest/admin/policies/enforcing-policies-for-your-enterprise/enforcing-policies-for-security-settings-in-your-enterprise#managing-sso-for-unauthenticated-users)”。

## 延伸阅读

* [Enterprise Managed Users 入门](/zh/enterprise-cloud@latest/admin/identity-and-access-management/understanding-iam-for-enterprises/getting-started-with-enterprise-managed-users)