# データベースおよび演習 中間レポート用
教科書: `実装で学ぶフルスタックWeb開発 エンジニアの視野と知識を広げる「一気通貫」型ハンズオン`

# セットアップ
## 1. リポジトリのクローン

```bash
git clone https://github.com/SatooRu65536/univ-database-2
```

## 2. 依存関係のインストール

```bash
cd frontend
yarn install
```

## 3. 起動

```bash
docker compose up
```

## 4. DBのマイグレーション

```bash
make login-backend
python manage.py migrate --settings config.settings.development
```
