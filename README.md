# netflix-clone-tutorial

source: 【React+TypeScript】Netflixのクローンを作るチュートリアル

https://zenn.dev/gunners6518/books/4c4672f32dd100

## Attention notice
If the configured s3 setting already exists , this script change the configuration your environment .

## Dependency
Tested only zsh on macOS , so if you want to use script for Windows . Please regulation yourself .

## Require

- Docker
- DockerCompose
- AWS CLI

https://docs.aws.amazon.com/ja_jp/cli/latest/userguide/install-cliv2-mac.html

### Usage

#### please setting REGION in aws cli and cloudformation.sh

For example

```bash:cloudformation.sh
readonly REGION=us-east-1
```

0. all: from create app and build to deploy phase

```bash
$ make
```

1. build phase

```bash
$ make build
```

2. run phase

```bash
$ make run
```

3. to aws deploy phase

```bash
$ make deploy
```

4. stack and s3 remove phase

```bash
$ make remove
```

## Authors
kazuya yuda.
