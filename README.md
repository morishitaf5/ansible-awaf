# はじめに
ここで紹介している設定ファイル等は、F5社が公式にサポートするものではありません。  
あくまでも検証等のサンプル用として、ご利用ください。

# ディレクトリ構成
・  
┣━ group_vars  
┃　　┗━ awaf_demo.yaml  
┃  
┣━ host_vars  
┃　　┣━ bigip01.yaml  
┃　　┗━ bigip02.yaml  
┃  
┣━ 01_setup.yaml  
┣━ 02_configure_awaf.yaml  
┣━ 03_create_vs.yaml  
┗━ 04_attach_policy.yaml  
