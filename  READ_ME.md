# Laravel で使用する DDD 用コード生成コマンド Template

Laravel project の app/Console は以下で実行
Service, Repository, UseCase, Interface の作成等を自動で行うコマンドを作成する

```
git clone
```

# Installation

Requirement で列挙したライブラリなどのインストール方法を説明する

```bash
git clone https://github.com/hoge/~　Commands
cd examples
rm -rf .git
```

# Usage

下記コマンドで

```bash
# serviceの作成
php artisan make:service SampleService
# serviceインターフェースの作成
php artisan make:serviceInterface SampleServiceInterface

# repositoryの作成
php artisan make:repository SampleRepository
# repositoryインターフェースの作成
php artisan make:repositoryInterface SampleRepositoryInterface

# usecaseの作成
php artisan make:usecase SampleUseCase
# usecaseインターフェースの作成
php artisan make:useCaseInterface SampleUseCaseInterface
```

# Note

注意点などがあれば書く

# Author

作成情報を列挙する

- 永松
- 極秘
- kouheidesu03@gmail.com

# License

ライセンスを明示する

"This" is under [MIT license](https:/).
