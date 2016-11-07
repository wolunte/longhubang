# longhubang
prepare for the further study.
extract:
 import tushare as ts
 ts.top_list('2015-07-01')
export:
 import tushare as ts
 df = ts.get_hist_data('000020')
 df.to_excel('c:/longhubang/000020.xlsx')
