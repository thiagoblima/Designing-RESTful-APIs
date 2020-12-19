# Designing RESTful APIs

> Desining RESTful APIs with quality and securance.

A deep review of designing *RESTful APIS*, simple and straight to the point.

1 ) - Basic _curl_ through *Github API*

```
curl https://api.github.com
```

Should return:

```
{
    "current_user_url": "https://api.github.com/user",
    "current_user_authorizations_html_url": "https://github.com/settings/connections/applications{/client_id}",
    "authorizations_url": "https://api.github.com/authorizations",
    "code_search_url": "https://api.github.com/search/code?q={query}{&page,per_page,sort,order}",
    "commit_search_url": "https://api.github.com/search/commits?q={query}{&page,per_page,sort,order}",
    "emails_url": "https://api.github.com/user/emails",
    "emojis_url": "https://api.github.com/emojis",
    "events_url": "https://api.github.com/events",
    "feeds_url": "https://api.github.com/feeds",
    "followers_url": "https://api.github.com/user/followers",
    "following_url": "https://api.github.com/user/following{/target}",
    "gists_url": "https://api.github.com/gists{/gist_id}",
    "hub_url": "https://api.github.com/hub",
    "issue_search_url": "https://api.github.com/search/issues?q={query}{&page,per_page,sort,order}",
    "issues_url": "https://api.github.com/issues",
    "keys_url": "https://api.github.com/user/keys",
    "label_search_url": "https://api.github.com/search/labels?q={query}&repository_id={repository_id}{&page,per_page}",
    "notifications_url": "https://api.github.com/notifications",
    "organization_url": "https://api.github.com/orgs/{org}",
    "organization_repositories_url": "https://api.github.com/orgs/{org}/repos{?type,page,per_page,sort}",
    "organization_teams_url": "https://api.github.com/orgs/{org}/teams",
    "public_gists_url": "https://api.github.com/gists/public",
    "rate_limit_url": "https://api.github.com/rate_limit",
    "repository_url": "https://api.github.com/repos/{owner}/{repo}",
    "repository_search_url": "https://api.github.com/search/repositories?q={query}{&page,per_page,sort,order}",
    "current_user_repositories_url": "https://api.github.com/user/repos{?type,page,per_page,sort}",
    "starred_url": "https://api.github.com/user/starred{/owner}{/repo}",
    "starred_gists_url": "https://api.github.com/gists/starred",
    "user_url": "https://api.github.com/users/{user}",
    "user_organizations_url": "https://api.github.com/user/orgs",
    "user_repositories_url": "https://api.github.com/users/{user}/repos{?type,page,per_page,sort}",
    "user_search_url":"https://api.github.com/search/users?q={query}{&page,per_page,sort,order"
}
```


## Release History

* 0.2.1
    * CHANGE: Update docs (module code remains unchanged)
* 0.2.0
    * CHANGE: Remove `setDefaultXYZ()`
    * ADD: Add `init()`
* 0.1.1
    * FIX: Crash when calling `baz()` (Thanks @GenerousContributorName!)
* 0.1.0
    * The first proper release
    * CHANGE: Rename `foo()` to `bar()`
* 0.0.1
    * Work in progress

## Meta

Thiago Lima

Distributed under the XYZ license. See ``LICENSE`` for more information.

[https://github.com/thiagoblima/Designing-RESTful-APIs/blob/main/LICENSE.md](https://github.com/thiagoblima/Designing-RESTful-APIs/blob/main/LICENSE.md)

## Contributing

1. Fork it (<https://github.com/thiagoblima/Designing-RESTful-APIs/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request


[wiki]: https://github.com/thiagoblima/Designing-RESTful-APIs/blob/main/README.md/wiki