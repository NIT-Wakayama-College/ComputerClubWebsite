# 開発環境を整える
1. [公式ホームページ](https://juggernautjp.info/installation/)を参考にhugoをインストール
2. リポジトリをクローンし、`hugo server`で開発用サーバーを起動させる
    ```shell
    $ git clone --recursive https://github.com/NCT-Wakayama-College/ComputerClubWebsiteDevelop.git
    $ cd ComputerClubWebsiteDevelop
    $ hugo server
    ```
3. 起動した開発用サーバーにアクセすることが確認できれば、開発環境を整えられている

# 記事を投稿
![GitHub Repozitory](ripozitory.drawio.svg)

コンピュータ部のWebサイトは2つのリポジトリを用いて開発を進める。ComputerClubWebsiteとComputerClubWebsiteDevelopというリポジトリである。ComputerClubWebsiteDevelop/mainとComputerClubWebsite/mainは常に同期させている。

記事を投稿する場合の手順を示す
1. ComputerClubWebsiteDevelopをクローンし、ブランチをdevelop又は、developから派生させたものにチェックアウトする
1. 記事を記述し、コミットを行う
1. 作業したブランチをリモートリポジロリにプッシュで反映させる
1. GitHubのPullRequestを使い、mainにsquash mergeする
2. これ以降は管理者権限を持っている人の操作である。ComputerClubWebsiteDevelopのmainブランチをプルする
3. ComputerClubWebsiteのmainブランチにmergeする
4. ComputerClubWebsiteにmainブランチをプッシュする