# [] を入れて [] を返す
def cordCompress(lst):
    tempList = sorted(set(lst))
    re = { v: i for i, v in enumerate(tempList) }
    return list(map(lambda v: re[v]+1, lst))

