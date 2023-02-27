
To update config:

1. `go install  github.com/bep/hugo-mod-bin-config-from-github-release@latest`
1. `hugo-mod-bin-config-from-github-release -owner sass -repo dart-sass-embedded -bin-name sass_embedded/dart-sass-embedded -tag 1.58.3 -target-directory .`

Notes:

* You need to set the `GITHUB_TOKEN` environment variable to a valid GitHub token.
* Make sure to adjust the `-tag` parameter to the relevant release.