# Push to multiple servers

Add new `pushurl`s to `.git/config` under the origin remote.

    [remote "origin"]
        url = https://git.xsfx.dev/xsteadfastx/til.git
        pushurl = https://git.xsfx.dev/xsteadfastx/til.git
        pushurl = https://github.com/xsteadfastx/til.git
        fetch = +refs/heads/*:refs/remotes/origin/*
