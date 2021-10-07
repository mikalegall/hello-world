# hello-world

Windows GitBash

    git init
    git add .
    git config user.email "lorem.ipsus@foo.bar"
    git config user.name "Lorem Ipsus"
    git commit -m"init"
    git remote add origin git@github.com:loremipsus/hello-world.git


    ssh-keygen -t ed25519 -C "lorem.ipsus@foo.bar"


    eval $(ssh-agent -s)
    ssh-add C:/Users/YOUR_LOCAL_ACCOUNT_NAME/.ssh/id_ed25519

Kopioi tiedoston
C:/Users/YOUR_LOCAL_ACCOUNT_NAME/.ssh/id_ed25519.pub
sisältö GitHubiin
https://github.com/settings/keys

    git push -u origin main


git config --global --unset user.name
