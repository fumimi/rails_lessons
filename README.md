▽Webrick　起動
rails server -b 0.0.0.0 -p 8080

▽Scaffolding機能を利用したrails generateコマンド
rails generate scaffold test category:string cday:date cid:integer clocation:string cno:integer copresenter_kana1:string copresenter_kana2:string copresenter_kana3:string copresenter_kana4:string copresenter_kana5:string copresenter_kana6:string copresenter_kana7:string copresenter_name1:string copresenter_name2:string copresenter_name3:string copresenter_name4:string copresenter_name5:string copresenter_name6:string copresenter_name7:string copresenter_office1:string copresenter_office2:string copresenter_office3:string copresenter_office4:string copresenter_office5:string copresenter_office6:string copresenter_office7:string croom:string ctime:time ctype:string filename:string form_lang:string leader_belongs:string leader_kana:string leader_name:string leader_office:string prefecture:string title:string title_sub:string zacho_kana:string zacho_name:string zacho_office:string
rake db:migrate