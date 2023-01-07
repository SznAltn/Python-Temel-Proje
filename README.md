# Python-Temel-Proje
l = [['flower', 25 ,'s','u','z','a','n',['butterfly'], 500],[[[625]],'bird'],64,125]
l1 = []
def flatten(n):
    for i in n :
        if isinstance(i,list):
            flatten(i)
        else:
            l1.append(i)

flatten(l)
print(l1)
