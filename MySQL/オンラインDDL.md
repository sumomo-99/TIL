# オンラインDDL - Online DDL
[MySQL 8.0 リファレンスマニュアル](https://dev.mysql.com/doc/refman/8.0/ja/innodb-online-ddl-operations.html)
- オンラインDDLが実行可能か不安なときは、 `algorighm=inplace` `lock=none` を追加して実行する。オンラインDDLに対応していない場合はエラーになる。