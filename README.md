# hello-spring-batch

Spring Batchの基礎を学ぶためのデモプロジェクト

## プロジェクト構造

```
src/
├── main/
│   └── java/
│       └── com/
│           └── udemy/
│               └── hello/
│                   ├── HelloSpringBatchApplication.java
│                   ├── config/
│                   │   └── SpringConfig.java
│                   └── tasklet/
│                       └── HelloTasklet1.java
└── test/
    └── java/
        └── com/
            └── udemy/
                └── hello/
                    └── HelloSpringBatchApplicationTests.java
```

## 作成済みモジュール

- **SpringConfig.java**: Spring Batchの基本設定クラス
  - パッケージ: `com.udemy.hello.config`
  - JobLauncher、JobRepository、TransactionManagerを定義

- **HelloTasklet1.java**: シンプルなTasklet実装
  - パッケージ: `com.udemy.hello.tasklet`
  - "Hello Spring Batch - Tasklet1"を出力するタスク