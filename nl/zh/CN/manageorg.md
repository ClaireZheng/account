---

copyright:

  years: 2015, 2018
lastupdated: "2018-05-21"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:tip: .tip}
{:screen: .screen}
{:new_window: target="_blank"}

# 更新组织和空间
{: #orgupdates}

作为帐户所有者或组织管理员，您可以在组织级别和空间级别执行管理任务。这些任务包括重命名组织或空间，分配或更新 Cloud Foundry 用户角色，管理域以及查看组织配额详细信息。
{:shortdesc}

要在 {{site.data.keyword.Bluemix}} 控制台中管理组织，请单击**管理 > 帐户 > Cloud Foundry 组织**。一次只能查看一个组织的资源。如果您是多个组织的成员，那么可以通过控制台菜单栏中的用户帐户首选项链接来切换组织。

## 重命名组织
{: #orgrename}

要重命名组织，请完成以下步骤。请注意，您所做的任何更改都将应用于组织中的所有用户。

1. 单击**管理** > **帐户** > **Cloud Foundry 组织**。
2. 针对要重命名的组织单击“操作”图标，然后选择**重命名**。  
3. 输入新名称，然后单击**保存**。

## 删除组织和空间
{: #deleteorgs}

### 删除组织

要删除组织，请联系[支持](/docs/get-support/howtogetsupport.html)。删除组织时，还会删除该组织内的所有空间和资源。请务必注意，删除操作不可撤销。 

### 删除空间

删除空间时，还会删除所有包含的资源和用户。要删除空间，请完成以下步骤：

1. 单击**管理** > **帐户** > **Cloud Foundry 组织**。
2. 单击在其中分配空间的组织。
3. 单击“操作”图标，然后选择**删除**。
4. 通过在字段中输入空间名称来确认要删除该空间，然后单击**删除**。

## 编辑用户角色
{: #listmembers}

您可以在组织级别分配的角色是管理员、记帐管理员和审计员。可以在空间级别分配的角色是管理员、开发者和审计员。有关详细的角色描述，请参阅 [Cloud Foundry 角色](/docs/iam/cfaccess.html#cfroles)。

### 编辑组织级别的用户角色

要编辑特定组织的用户角色，请完成以下步骤：

1. 单击**管理** > **帐户** > **Cloud Foundry 组织**。
2. 单击“操作”图标，然后选择**用户**。
3. 根据要修改用户许可权的方式，选中或清除特定角色对应的复选框。
4. 通过单击**保存**来确认更改。 

### 编辑空间级别的用户角色

要编辑特定空间的用户角色，请完成以下步骤：

1. 单击**管理** > **帐户** > **Cloud Foundry 组织**。
2. 单击在其中分配空间的组织。
3. 单击空间的名称。
4. 根据要修改用户许可权的方式，选中或清除特定角色对应的复选框。
5. 通过单击**保存**来确认更改。

## 管理域
{: #managedomains}

作为帐户所有者或组织管理员，您可以针对组织及其空间内构建的应用程序，查看系统域并添加定制域。作为空间管理员，**域**选项卡是分配给该空间的域的只读列表。

1. 单击**管理** &gt; **帐户** &gt; **Cloud Foundry 组织**。
2. 针对组织单击“操作”图标，然后选择**域**。

如果您添加定制域，那么必须配置 DNS 服务器以将您的定制域解析为指向 {{site.data.keyword.Bluemix_notm}} 系统域。这样，当 {{site.data.keyword.Bluemix_notm}} 接收到定制域的请求时，可以将其正确路由到您的应用程序。系统域始终可供空间使用，另外还可为空间分配定制域。空间中创建的应用程序可使用为该空间列出的任何域。有关创建和使用定制域的更多信息，请参阅[使用定制域](/docs/apps/updapps.html#domain)。

## 管理配额
{: #managequota}

您可以查看组织的已用和已分配配额。配额表示创建组织时为其分配的资源限制。组织可用的资源根据您是具有免费帐户还是计费帐户而有所不同。组织内空间中包含的任何应用程序或服务都会使用一定的已分配配额。

要查看组织的已使用和已分配配额，请完成以下步骤：

1. 单击**管理** &gt; **帐户** &gt; **Cloud Foundry 组织**。
2. 针对特定组织单击“操作”图标，然后选择**配额**。

   缺省情况下，会显示 **Cloud Foundry** 配额页面。在此，可以查看以下资源的配额详细信息：
 
   * 应用程序数
   * 内存量 
   * 服务数 
   * 套餐详细信息 

3. 展开行以查看每个区域的空间级别上的配额详细信息。  

要更改为组织所分配的配额，必须开具支持凭单。有关更多信息，请参阅[获取客户支持](/docs/get-support/howtogetsupport.html#getting-customer-support)。 

