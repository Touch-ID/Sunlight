二进制转换：
#==================================================
##域名list转换为二进制
mihomo convert-ruleset domain text XXX.list XXX.mrs
##ip-list转换为二进制
mihomo convert-ruleset ipcidr text XXX.list XXX.mrs
##二进制转换为list （目前不支持yaml反向转换）
mihomo convert-ruleset domain mrs XXX.mrs XXX.list
##域名yaml转换为二进制
mihomo convert-ruleset domain yaml XXX.yaml XXX.mrs
