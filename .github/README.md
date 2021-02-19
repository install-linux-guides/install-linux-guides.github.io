# Install Linux Guides
[heading__top]:
  #install-linux-guides
  "&#x2B06; Root path for GitHub Pages assets and miscellaneous posts"


Root path for GitHub Pages assets and miscellaneous posts


## [![Byte size of Install Linux Guidesgithubio][badge__gh-pages__install_linux_guides.github.io__source_code]][install_linux_guides.github.io__gh-pages__source_code] [![Open Issues][badge__issues__install_linux_guides.github.io]][issues__install_linux_guides.github.io] [![Open Pull Requests][badge__pull_requests__install_linux_guides.github.io]][pull_requests__install_linux_guides.github.io] [![Latest commits][badge__commits__install_linux_guides.github.io__gh-pages]][commits__install_linux_guides.github.io__gh-pages] [![install-linux-guides.github.io Demos][badge__gh_pages__install_linux_guides.github.io]][gh_pages__install_linux_guides.github.io]


---


- [:arrow_up: Top of Document][heading__top]

- [:building_construction: Requirements][heading__requirements]

- [:zap: Quick Start][heading__quick_start]

- [&#x1F5D2; Notes][heading__notes]

- [:chart_with_upwards_trend: Contributing][heading__contributing]

  - [:trident: Forking][heading__forking]
  - [:currency_exchange: Sponsor][heading__sponsor]

- [:card_index: Attribution][heading__attribution]

- [:balance_scale: Licensing][heading__license]


---



## Requirements
[heading__requirements]:
  #requirements
  "&#x1F3D7; Prerequisites and/or dependencies that this project needs to function properly"


This repository depends upon [Jekyll][jekyll_rb__home] which is supported by [GitHub Pages][github_docs__github_pages__jekyll], further details about setup can be found from [documentation][jekyll_rb__github_pages] published by the Jekyll maintainers regarding GitHub Pages.


______


## Quick Start
[heading__quick_start]:
  #quick-start
  "&#9889; Perhaps as easy as one, 2.0,..."


Clone this project...


```Bash
mkdir -vp ~/git/hub/install-linux-guides

cd ~/git/hub/install-linux-guides

git clone git@github.com:install-linux-guides/install-linux-guides.github.io.git
```


Build with Jekyll...


```Bash
cd ~/git/hub/install-linux-guides/usb-uefi-compatible

bundle exec jekyll build
```


______


## Notes
[heading__notes]:
  #notes
  "&#x1F5D2; Additional things to keep in mind when developing"


This repository may not be feature complete and/or fully functional, Pull Requests that add features or fix bugs are certainly welcomed.


______


## Contributing
[heading__contributing]:
  #contributing
  "&#x1F4C8; Options for contributing to install-linux-guides.github.io and install-linux-guides"


Options for contributing to install-linux-guides.github.io and install-linux-guides


---


### Forking
[heading__forking]:
  #forking
  "&#x1F531; Tips for forking install-linux-guides.github.io"


Start making a [Fork][install_linux_guides.github.io__fork_it] of this repository to an account that you have write permissions for.


- Add remote for fork URL. The URL syntax is _`git@github.com:<NAME>/<REPO>.git`_...


```Bash
cd ~/git/hub/install-linux-guides/install-linux-guides.github.io

git remote add fork git@github.com:<NAME>/install-linux-guides.github.io.git
```


- Commit your changes and push to your fork, eg. to fix an issue...


```Bash
cd ~/git/hub/install-linux-guides/install-linux-guides.github.io


git commit -F- <<'EOF'
:bug: Fixes #42 Issue


**Edits**


- `<SCRIPT-NAME>` script, fixes some bug reported in issue
EOF


git push fork gh-pages
```


> Note, the `-u` option may be used to set `fork` as the default remote, eg. _`git push -u fork gh-pages`_ however, this will also default the `fork` remote for pulling from too! Meaning that pulling updates from `origin` must be done explicitly, eg. _`git pull origin gh-pages`_


- Then on GitHub submit a Pull Request through the Web-UI, the URL syntax is _`https://github.com/<NAME>/<REPO>/pull/new/<BRANCH>`_


> Note; to decrease the chances of your Pull Request needing modifications before being accepted, please check the [dot-github](https://github.com/install-linux-guides/.github) repository for detailed contributing guidelines.


---


### Sponsor
  [heading__sponsor]:
  #sponsor
  "&#x1F4B1; Methods for financially supporting install-linux-guides that maintains install-linux-guides.github.io"


Thanks for even considering it!


Via Liberapay you may <sub>[![sponsor__shields_io__liberapay]][sponsor__link__liberapay]</sub> on a repeating basis.


Regardless of if you're able to financially support projects such as install-linux-guides.github.io that install-linux-guides maintains, please consider sharing projects that are useful with others, because one of the goals of maintaining Open Source repositories is to provide value to the community.


______


## Attribution
[heading__attribution]:
  #attribution
  "&#x1F4C7; Resources that where helpful in building this project so far."


- [GitHub -- `github-utilities/make-readme`](https://github.com/github-utilities/make-readme)


______


## License
[heading__license]:
  #license
  "&#x2696; Legal side of Open Source"


```
Root path for GitHub Pages assets and miscellaneous posts
Copyright (C) 2021 S0AndS0

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as published
by the Free Software Foundation, version 3 of the License.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.
```


For further details review full length version of [AGPL-3.0][branch__current__license] License.



[branch__current__license]:
  /LICENSE
  "&#x2696; Full length version of AGPL-3.0 License"


[badge__commits__install_linux_guides.github.io__gh-pages]:
  https://img.shields.io/github/last-commit/install-linux-guides/install-linux-guides.github.io/gh-pages.svg

[commits__install_linux_guides.github.io__gh-pages]:
  https://github.com/install-linux-guides/install-linux-guides.github.io/commits/gh-pages
  "&#x1F4DD; History of changes on this branch"


[install_linux_guides.github.io__community]:
  https://github.com/install-linux-guides/install-linux-guides.github.io/community
  "&#x1F331; Dedicated to functioning code"

[install_linux_guides.github.io__gh_pages]:
  https://github.com/install-linux-guides/install-linux-guides.github.io/tree/
  "Source code examples hosted thanks to GitHub Pages!"

[badge__gh_pages__install_linux_guides.github.io]:
  https://img.shields.io/website/https/install-linux-guides.github.io/install-linux-guides.github.io/index.html.svg?down_color=darkorange&down_message=Offline&label=Demo&logo=Demo%20Site&up_color=success&up_message=Online

[gh_pages__install_linux_guides.github.io]:
  https://install-linux-guides.github.io/install-linux-guides.github.io/index.html
  "&#x1F52C; Check the example collection tests"

[issues__install_linux_guides.github.io]:
  https://github.com/install-linux-guides/install-linux-guides.github.io/issues
  "&#x2622; Search for and _bump_ existing issues or open new issues for project maintainer to address."

[install_linux_guides.github.io__fork_it]:
  https://github.com/install-linux-guides/install-linux-guides.github.io/
  "&#x1F531; Fork it!"

[pull_requests__install_linux_guides.github.io]:
  https://github.com/install-linux-guides/install-linux-guides.github.io/pulls
  "&#x1F3D7; Pull Request friendly, though please check the Community guidelines"

[install_linux_guides.github.io__gh-pages__source_code]:
  https://github.com/install-linux-guides/install-linux-guides.github.io/
  "&#x2328; Project source!"

[badge__issues__install_linux_guides.github.io]:
  https://img.shields.io/github/issues/install-linux-guides/install-linux-guides.github.io.svg

[badge__pull_requests__install_linux_guides.github.io]:
  https://img.shields.io/github/issues-pr/install-linux-guides/install-linux-guides.github.io.svg

[badge__gh-pages__install_linux_guides.github.io__source_code]:
  https://img.shields.io/github/repo-size/install-linux-guides/install-linux-guides.github.io


[jekyll_rb__home]:
  https://jekyllrb.com/
  "Jekyll home page"

[jekyll_rb__github_pages]:
  https://jekyllrb.com/docs/github-pages/
  "Jekyll documentation for GitHub Pages setup"

[github_docs__github_pages__jekyll]:
  https://docs.github.com/en/github/working-with-github-pages/setting-up-a-github-pages-site-with-jekyll
  "GitHub Pages documentation on Jekyll setup"




[sponsor__shields_io__liberapay]:
  https://img.shields.io/static/v1?logo=liberapay&label=Sponsor&message=install-linux-guides

[sponsor__link__liberapay]:
  https://liberapay.com/install-linux-guides
  "&#x1F4B1; Sponsor developments and projects that install-linux-guides maintains via Liberapay"



