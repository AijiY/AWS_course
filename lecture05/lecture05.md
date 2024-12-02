# 第5回課題

## サンプルアプリケーションのデプロイおよび動作

### PumaでのRailsアプリ動作確認
![image](./png/1-1.puma_with_rb.png)
![image](./png/1-2.puma_with_service.png)

### 組み込みサーバーとUnix Socketを使ったRailsアプリの動作確認
![image](./png/2-1.puma_socket_with_rb.png)
![image](./png/2-2.puma_socket_with_service.png)
![image](./png/2-3.curl_through_socket.png)

### Nginxの単体起動確認
![image](./png/3.nginx.png)

### Nginxと組み込みサーバー、Unix Socketを組み合わせてのRailsアプリケーション動作確認
![image](./png/4.puma_nginx_socket.png)

## ELB(ALB)の追加
![image](./png/5.alb.png)

## S3の追加

### 登録動作
#### 登録前
![image](./png/6-1.s3_before_save.png)
#### 登録後
![image](./png/6-2.s3_after_save.png)
#### Home遷移後
![image](./png/6-3.s3_after_home.png)
#### S3内の各画像
![image](./png/6-4.s3_picture1.png)
![image](./png/6-5.s3_picture2.png)
![image](./png/6-6.s3_picture3.png)

### 削除動作
![image](./png/6-7.after_destroy.png)

## AWS構成図
![image](./AWS_configuration/AWS_configuration.svg)
