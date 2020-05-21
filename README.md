# Pioneer Developers

## Rules

### How to become a team member

1. Fork the repo, do some modifications to fix bugs or add features.
2. Create an over 3 pull requests and merged in any active projects
3. Contact @Lyric (mixin id: 764392)

### How to contribute

We use Github issues to discuss new features or new projects.

### What can I do now

We are preparing a very first project named “Set Flags”(打卡), which is a bot allow to set flags by people. Learn more about it [here](https://github.com/set-flags/set-flags).

There are some projects on the way:

1. A vote bot to create votes and vote for existed one.
2. A twitter clone which use Mixin Messenger to sign in.

If you have any terrific ideas, submit an issue when your project solution document is ready.


### Tech Dependences

By defaults, we ask developers to use following languages/packages/libraries/frameworks in projects:

for back-ends:

- Mixin SDK: https://github.com/fox-one/mixin-sdk
- Database ORM: https://github.com/jinzhu/gorm 
- HTTP Service: https://github.com/gin-gonic/gin

for front-ends:

- NUXT_Template: https://github.com/fox-one/nuxt_ts_template which include nuxt, vue and vuetify

Notice:

1. It’s welcome to use new technologies/languages/libraries/frameworks in the projects, if only more than one contributors agree and use them.
2. It’s welcome to fork and contribute code to the upstream.

### Commit rule

Only English may use in commit log.

It’s recommended to use [Conventional Commits 1.0.0](https://www.conventionalcommits.org/en/v1.0.0/). However, if you want to make life easier at beginning, please follow these prefix at latest:

```
<type>: <description>
```

`<type>` could be:

- `fix`: a commit of the type fix patches a bug in your codebase
- `feat`: a commit of the type feat introduces an additional feature to the codebase
- `refactor`: a commit of the type refactor a part of code to the codebase
- `docs`: a commit of the type update some docs
- `chore`: a commit of other types.

#### Examples

> feat: allow provided config object to extend other configs
>
> BREAKING CHANGE: `extends` key in config file is now used for extending other config files

> refactor: drop support for Node 6

> feat(lang): add polish language

> docs: correct spelling of CHANGELOG

