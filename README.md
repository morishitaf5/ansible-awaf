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
┣━ configure_awaf.yaml  
┣━ create_vs.yaml  
┗━ attach_policy.yaml  
