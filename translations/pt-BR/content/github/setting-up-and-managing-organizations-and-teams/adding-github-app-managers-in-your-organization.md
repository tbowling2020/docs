---
title: Adicionar gerentes do aplicativo GitHub em sua organização
intro: 'Os proprietários da organização podem conceder aos usuários a capacidade de gerenciar {{ site.data.variables.product.prodname_github_app }} específicos ou todos os {{ site.data.variables.product.prodname_github_app }}s da organização.'
redirect_from:
  - /articles/adding-github-app-managers-in-your-organization
versions:
  free-pro-team: '*'
  enterprise-server: '*'
---

Para obter mais informações sobre as permissões de gerente do {{ site.data.variables.product.prodname_github_app }}, consulte "[Níveis de permissão para uma organização](/articles/permission-levels-for-an-organization#github-app-managers)".

### Dar a um indivíduo a capacidade de gerenciar todos os {{ site.data.variables.product.prodname_github_app }}s possuídos pela organização

{{ site.data.reusables.profile.access_profile }}
{{ site.data.reusables.profile.access_org }}
{{ site.data.reusables.organizations.org_settings }}
{{ site.data.reusables.organizations.github-apps-settings-sidebar }}
1. Em "Management" (Gerenciamento), digite o nome de usuário da pessoa que deseja designar como um gerente do {{ site.data.variables.product.prodname_github_app }} na organização e clique em **Grant** (Conceder). ![Adicionar um gerente do {{ site.data.variables.product.prodname_github_app }}](/assets/images/help/organizations/add-github-app-manager.png)

### Dar a um indivíduo a capacidade de gerenciar um {{ site.data.variables.product.prodname_github_app }} individual

{{ site.data.reusables.profile.access_profile }}
{{ site.data.reusables.profile.access_org }}
{{ site.data.reusables.organizations.org_settings }}
{{ site.data.reusables.organizations.github-apps-settings-sidebar }}
1. Em "{{ site.data.variables.product.prodname_github_app }}s", clique no avatar do app ao qual deseja adicionar um gerente do {{ site.data.variables.product.prodname_github_app }}. ![Selecione {{ site.data.variables.product.prodname_github_app }}](/assets/images/help/organizations/select-github-app.png)
{{ site.data.reusables.organizations.app-managers-settings-sidebar }}
1. Em "App managers" (Gerentes de app), digite o nome de usuário da pessoa que deseja designar como gerente do aplicativo GitHub e clique em **Grant** (Conceder). ![Adicionar um gerente do {{ site.data.variables.product.prodname_github_app }} para um app específico](/assets/images/help/organizations/add-github-app-manager-for-app.png)

{% if currentVersion == "free-pro-team@latest" %}
### Leia mais

- "[Sobre o {{ site.data.variables.product.prodname_dotcom }} Marketplace](/articles/about-github-marketplace/)"
{% endif %}