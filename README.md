# subject-231220 
( [Replit で実行 : MTN](https://replit.com/@sworc/ALL-PDO-masutamente) )
( [Replit で実行 : REQ](https://replit.com/@sworc/ALL-PDO-Wen-iHe-wase) )
( [Replit で実行 : BOARD](https://replit.com/@sworc/ALL-Jie-Shi-Ban-MVCJie-Shi-Ban-detabesu) )

- ### 🔴 標準化前の社員マスタの修正処理
  - https://github.com/winofsql/php-mtn-v01-update-sqlite  
    - スマホ対応はまだ

- ### 🔴 社員マスタの修正処理( model.php を追加 )
  - https://github.com/winofsql/php-mtn-v02-update-model-sqlite
    - スマホ対応はまだ
    - 基本的な入力チェック
      - form から onsubmit
      - html によるチェック

- ### 🔴 社員マスタの新規登録を追加
  - https://github.com/winofsql/php-mtn-v03-update-insert-sqlite


- ### 🔴 会話コントロールによるコントロールプロテクト
  - https://github.com/winofsql/php-mtn-v04-communication-sqlite

- ### 🔴 Enter キーで次のフィールドへ移動
  - https://github.com/winofsql/php-mtn-v05-enter-control-sqlite

- ### 🔴 コンボボックスの実装
  - https://github.com/winofsql/php-mtn-v06-combo-box-sqlite


```
C:\xampp\apache\bin>httpd /?
Usage: httpd [-D name] [-d directory] [-f file]
             [-C "directive"] [-c "directive"]
             [-w] [-k start|restart|stop|shutdown] [-n service_name]
             [-k install|config|uninstall] [-n service_name]
             [-v] [-V] [-h] [-l] [-L] [-t] [-T] [-S] [-X]
Options:
  -D name            : define a name for use in <IfDefine name> directives
  -d directory       : specify an alternate initial ServerRoot
  -f file            : specify an alternate ServerConfigFile
  -C "directive"     : process directive before reading config files
  -c "directive"     : process directive after reading config files
  -n name            : set service name and use its ServerConfigFile and ServerRoot
  -k start           : tell Apache to start
  -k restart         : tell running Apache to do a graceful restart
  -k stop|shutdown   : tell running Apache to shutdown
  -k install         : install an Apache service
  -k config          : change startup Options of an Apache service
  -k uninstall       : uninstall an Apache service
  -w                 : hold open the console window on error
  -e level           : show startup errors of level (see LogLevel)
  -E file            : log startup errors to file
  -v                 : show version number
  -V                 : show compile settings
  -h                 : list available command line options (this page)
  -l                 : list compiled in modules
  -L                 : list available configuration directives
  -t -D DUMP_VHOSTS  : show parsed vhost settings
  -t -D DUMP_RUN_CFG : show parsed run settings
  -S                 : a synonym for -t -D DUMP_VHOSTS -D DUMP_RUN_CFG
  -t -D DUMP_MODULES : show all loaded modules
  -M                 : a synonym for -t -D DUMP_MODULES
  -t -D DUMP_INCLUDES: show all included configuration files
  -t                 : run syntax check for config files 🔴
  -T                 : start without DocumentRoot(s) check
  -X                 : debug mode (only one worker, do not detach)
```
