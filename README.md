# amass intel - اكتشف أهداف التعداد
# amass enum - إجراء عمليات التعداد وتعيين الشبكة
# amass viz - تصور نتائج التعداد
# amass track - تتبع الاختلافات بين عمليات التعداد
# amass db - معالجة قاعدة بيانات الرسم البياني Amass


##### ENUM #####
Find subdomains by PASSIVE SCANNING:-
amass enum -passive -norecursive -noalts -d () -o ().txt

Find subdomains by BRUTE FORSING:-
amass enum -brute -w /root/Amass/examples/wordlists/all.txt -d testphp.vulnweb.com
-o target.txt
_________________________________________________________________________
##### INTEL #####

amass intel -org (tesla) --> will give asn

 
amass intel -asn -active ASN

amass intel -active -cidr (ip/24) --> give yor .com .sn etc ..
