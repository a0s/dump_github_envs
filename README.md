Dump GitHub pipeline variables
==============================

Hope it doesn't include sensitive informations 😆

```
{
  "token": "***",
  "job": "dump",
  "ref": "refs/heads/master",
  "sha": "17a9dd53a8bfa87f9a3193339d27934b7b057f79",
  "repository": "a0s/dump_github_envs",
  "repository_owner": "a0s",
  "repository_owner_id": "418868",
  "repositoryUrl": "git://github.com/a0s/dump_github_envs.git",
  "run_id": "2454441322",
  "run_number": "1",
  "retention_days": "90",
  "run_attempt": "1",
  "artifact_cache_size_limit": "10",
  "repository_id": "500824692",
  "actor_id": "418868",
  "actor": "a0s",
  "workflow": "Dump variables",
  "head_ref": "",
  "base_ref": "",
  "event_name": "push",
  "event": {
    "after": "17a9dd53a8bfa87f9a3193339d27934b7b057f79",
    "base_ref": null,
    "before": "0000000000000000000000000000000000000000",
    "commits": [
      {
        "author": {
          "email": "my@email",
          "name": "Anton Osenenko",
          "username": "a0s"
        },
        "committer": {
          "email": "my@email",
          "name": "Anton Osenenko",
          "username": "a0s"
        },
        "distinct": true,
        "id": "17a9dd53a8bfa87f9a3193339d27934b7b057f79",
        "message": "pipeline",
        "timestamp": "2022-06-07T15:14:10+03:00",
        "tree_id": "e1ece693ba0598fa7f2bb2d8a045192a1a0e4268",
        "url": "https://github.com/a0s/dump_github_envs/commit/17a9dd53a8bfa87f9a3193339d27934b7b057f79"
      }
    ],
    "compare": "https://github.com/a0s/dump_github_envs/commit/17a9dd53a8bf",
    "created": true,
    "deleted": false,
    "forced": false,
    "head_commit": {
      "author": {
        "email": "my@email",
        "name": "Anton Osenenko",
        "username": "a0s"
      },
      "committer": {
        "email": "my@email",
        "name": "Anton Osenenko",
        "username": "a0s"
      },
      "distinct": true,
      "id": "17a9dd53a8bfa87f9a3193339d27934b7b057f79",
      "message": "pipeline",
      "timestamp": "2022-06-07T15:14:10+03:00",
      "tree_id": "e1ece693ba0598fa7f2bb2d8a045192a1a0e4268",
      "url": "https://github.com/a0s/dump_github_envs/commit/17a9dd53a8bfa87f9a3193339d27934b7b057f79"
    },
    "pusher": {
      "email": "418868+a0s@users.noreply.github.com",
      "name": "a0s"
    },
    "ref": "refs/heads/master",
    "repository": {
      "allow_forking": true,
      "archive_url": "https://api.github.com/repos/a0s/dump_github_envs/{archive_format}{/ref}",
      "archived": false,
      "assignees_url": "https://api.github.com/repos/a0s/dump_github_envs/assignees{/user}",
      "blobs_url": "https://api.github.com/repos/a0s/dump_github_envs/git/blobs{/sha}",
      "branches_url": "https://api.github.com/repos/a0s/dump_github_envs/branches{/branch}",
      "clone_url": "https://github.com/a0s/dump_github_envs.git",
      "collaborators_url": "https://api.github.com/repos/a0s/dump_github_envs/collaborators{/collaborator}",
      "comments_url": "https://api.github.com/repos/a0s/dump_github_envs/comments{/number}",
      "commits_url": "https://api.github.com/repos/a0s/dump_github_envs/commits{/sha}",
      "compare_url": "https://api.github.com/repos/a0s/dump_github_envs/compare/{base}...{head}",
      "contents_url": "https://api.github.com/repos/a0s/dump_github_envs/contents/{+path}",
      "contributors_url": "https://api.github.com/repos/a0s/dump_github_envs/contributors",
      "created_at": 1654603771,
      "default_branch": "master",
      "deployments_url": "https://api.github.com/repos/a0s/dump_github_envs/deployments",
      "description": "Dump environment",
      "disabled": false,
      "downloads_url": "https://api.github.com/repos/a0s/dump_github_envs/downloads",
      "events_url": "https://api.github.com/repos/a0s/dump_github_envs/events",
      "fork": false,
      "forks": 0,
      "forks_count": 0,
      "forks_url": "https://api.github.com/repos/a0s/dump_github_envs/forks",
      "full_name": "a0s/dump_github_envs",
      "git_commits_url": "https://api.github.com/repos/a0s/dump_github_envs/git/commits{/sha}",
      "git_refs_url": "https://api.github.com/repos/a0s/dump_github_envs/git/refs{/sha}",
      "git_tags_url": "https://api.github.com/repos/a0s/dump_github_envs/git/tags{/sha}",
      "git_url": "git://github.com/a0s/dump_github_envs.git",
      "has_downloads": true,
      "has_issues": true,
      "has_pages": false,
      "has_projects": true,
      "has_wiki": true,
      "homepage": null,
      "hooks_url": "https://api.github.com/repos/a0s/dump_github_envs/hooks",
      "html_url": "https://github.com/a0s/dump_github_envs",
      "id": 500824692,
      "is_template": false,
      "issue_comment_url": "https://api.github.com/repos/a0s/dump_github_envs/issues/comments{/number}",
      "issue_events_url": "https://api.github.com/repos/a0s/dump_github_envs/issues/events{/number}",
      "issues_url": "https://api.github.com/repos/a0s/dump_github_envs/issues{/number}",
      "keys_url": "https://api.github.com/repos/a0s/dump_github_envs/keys{/key_id}",
      "labels_url": "https://api.github.com/repos/a0s/dump_github_envs/labels{/name}",
      "language": null,
      "languages_url": "https://api.github.com/repos/a0s/dump_github_envs/languages",
      "license": null,
      "master_branch": "master",
      "merges_url": "https://api.github.com/repos/a0s/dump_github_envs/merges",
      "milestones_url": "https://api.github.com/repos/a0s/dump_github_envs/milestones{/number}",
      "mirror_url": null,
      "name": "dump_github_envs",
      "node_id": "R_kgDOHdn6dA",
      "notifications_url": "https://api.github.com/repos/a0s/dump_github_envs/notifications{?since,all,participating}",
      "open_issues": 0,
      "open_issues_count": 0,
      "owner": {
        "avatar_url": "https://avatars.githubusercontent.com/u/418868?v=4",
        "email": "418868+a0s@users.noreply.github.com",
        "events_url": "https://api.github.com/users/a0s/events{/privacy}",
        "followers_url": "https://api.github.com/users/a0s/followers",
        "following_url": "https://api.github.com/users/a0s/following{/other_user}",
        "gists_url": "https://api.github.com/users/a0s/gists{/gist_id}",
        "gravatar_id": "",
        "html_url": "https://github.com/a0s",
        "id": 418868,
        "login": "a0s",
        "name": "a0s",
        "node_id": "MDQ6VXNlcjQxODg2OA==",
        "organizations_url": "https://api.github.com/users/a0s/orgs",
        "received_events_url": "https://api.github.com/users/a0s/received_events",
        "repos_url": "https://api.github.com/users/a0s/repos",
        "site_admin": false,
        "starred_url": "https://api.github.com/users/a0s/starred{/owner}{/repo}",
        "subscriptions_url": "https://api.github.com/users/a0s/subscriptions",
        "type": "User",
        "url": "https://api.github.com/users/a0s"
      },
      "private": false,
      "pulls_url": "https://api.github.com/repos/a0s/dump_github_envs/pulls{/number}",
      "pushed_at": 1654604076,
      "releases_url": "https://api.github.com/repos/a0s/dump_github_envs/releases{/id}",
      "size": 0,
      "ssh_url": "git@github.com:a0s/dump_github_envs.git",
      "stargazers": 0,
      "stargazers_count": 0,
      "stargazers_url": "https://api.github.com/repos/a0s/dump_github_envs/stargazers",
      "statuses_url": "https://api.github.com/repos/a0s/dump_github_envs/statuses/{sha}",
      "subscribers_url": "https://api.github.com/repos/a0s/dump_github_envs/subscribers",
      "subscription_url": "https://api.github.com/repos/a0s/dump_github_envs/subscription",
      "svn_url": "https://github.com/a0s/dump_github_envs",
      "tags_url": "https://api.github.com/repos/a0s/dump_github_envs/tags",
      "teams_url": "https://api.github.com/repos/a0s/dump_github_envs/teams",
      "topics": [],
      "trees_url": "https://api.github.com/repos/a0s/dump_github_envs/git/trees{/sha}",
      "updated_at": "2022-06-07T12:09:31Z",
      "url": "https://github.com/a0s/dump_github_envs",
      "visibility": "public",
      "watchers": 0,
      "watchers_count": 0
    },
    "sender": {
      "avatar_url": "https://avatars.githubusercontent.com/u/418868?v=4",
      "events_url": "https://api.github.com/users/a0s/events{/privacy}",
      "followers_url": "https://api.github.com/users/a0s/followers",
      "following_url": "https://api.github.com/users/a0s/following{/other_user}",
      "gists_url": "https://api.github.com/users/a0s/gists{/gist_id}",
      "gravatar_id": "",
      "html_url": "https://github.com/a0s",
      "id": 418868,
      "login": "a0s",
      "node_id": "MDQ6VXNlcjQxODg2OA==",
      "organizations_url": "https://api.github.com/users/a0s/orgs",
      "received_events_url": "https://api.github.com/users/a0s/received_events",
      "repos_url": "https://api.github.com/users/a0s/repos",
      "site_admin": false,
      "starred_url": "https://api.github.com/users/a0s/starred{/owner}{/repo}",
      "subscriptions_url": "https://api.github.com/users/a0s/subscriptions",
      "type": "User",
      "url": "https://api.github.com/users/a0s"
    }
  },
  "server_url": "https://github.com",
  "api_url": "https://api.github.com",
  "graphql_url": "https://api.github.com/graphql",
  "ref_name": "master",
  "ref_protected": false,
  "ref_type": "branch",
  "secret_source": "Actions",
  "workspace": "/home/runner/work/dump_github_envs/dump_github_envs",
  "action": "__run"
}
```
