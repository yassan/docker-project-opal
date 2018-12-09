# docker-project-opal

Project Opal(Visual appearance modernization project for Redmine)'s Docker Compose

[redmine-cp/project-opal](https://github.com/redmine-cp/project-opal) をDockerで利用するためのリポジトリ

### Directory Tree

```text
├── data
│   ├── backups
│   ├── certs <-ここにSSL証明書をいれる
│   │   ├── dhparam.pem
│   │   ├── redmine.crt
│   │   ├── redmine.csr
│   │   └── redmine.key
│   ├── dotfiles
│   ├── files
│   ├── plugins <-ここに使いたいプラグインを git clone
│   │   ├── redmine_logs
│   │   └── redmine_theme_changer
│   ├── themes
│   │   └── opal <-ここにproject-opalのリソースやsassから生成したcssを配置
│   │       ├── favicon
│   │       ├── fonts
│   │       ├── images
│   │       │   ├── emoji
│   │       │   ├── files
│   │       │   ├── icons
│   │       │   └── images
│   │       └── stylesheets
│   │           ├── application.css
│   │           ├── application.css.map
│   │           ├── global
│   │           │   ├── #breadcrumbs.css
│   │           │   ├──  :
│   │           └── local
│   │               ├── #activity.css
│   │               ├──  : 
│   └── tmp
├── docker-compose.yml
└── postgres
```