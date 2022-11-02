

import matplotlib.pyplot as plt
import numpy as np
import pandas as pd

post_线程数_循环数=[400,200,100,50,25,10]
plt.rcParams['font.sans-serif']=['SimHei']

'''50
post_总执行时间=[36391,34928,28998,22180,12586,7115]
plt.plot(post_线程数_循环数,post_总执行时间,color='orange',label='post')
plt.xlabel('线程数')
plt.ylabel('总执行时间')
plt.title('读写效率对比图')

getrid_总执行时间=[23357,22462,21621,21879,16525,14582]
getid_总执行时间=[25382,20414,21510,20848,16880,14777]

plt.plot(post_线程数_循环数,getrid_总执行时间,color='green',label='get_随机选择id')
plt.plot(post_线程数_循环数,getid_总执行时间,color='blue',label='get_顺序选择id')

plt.legend()
plt.show()

'''

'''30
post_总执行时间=[24841,22717,25655,20567,14409,7772]
getrid_总执行时间=[18293,18792,18640,18193,16442,14880]
getid_总执行时间=[18410,18065,18666,18913,16912,14383]

#画图，以post_线程数_循环数为x轴，post_总执行时间为y轴，并且颜色为暗橙色，标签为post
plt.plot(post_线程数_循环数,post_总执行时间,color='darkorange',label='post')
#画图，以post_线程数_循环数为x轴，getrid_总执行时间为y轴，并且颜色为暗绿色，标签为get_随机选择id
plt.plot(post_线程数_循环数,getrid_总执行时间,color='darkgreen',label='get_随机选择id')
#画图，以post_线程数_循环数为x轴，getid_总执行时间为y轴，并且颜色为暗蓝色，标签为get_顺序选择id
plt.plot(post_线程数_循环数,getid_总执行时间,color='darkblue',label='get_顺序选择id')
'''

'''

x=[400,200,100,50]
getrid_总执行时间1=[42910,35268,26892,21065]
getrid_总执行时间2=[64773,44674,31237,18381]
getid_总执行时间1=[40159,38707,29755,20179]
getid_总执行时间2=[33753,43792,27334,20689]
fig,ax=plt.subplots(2,1)
ax[0].plot(x,getrid_总执行时间1,color='orange',label='get_随机选择id_没开二级缓存')
ax[0].plot(x,getrid_总执行时间2,color='green',label='get_随机选择id_开二级缓存')
plt.legend()
ax[1].plot(x,getid_总执行时间1,color='darkorange',label='get_顺序选择id_没开二级缓存')
ax[1].plot(x,getid_总执行时间2,color='darkgreen',label='get_顺序选择id_开二级缓存')
'''

post_总执行时间50=[36391,34928,28998,22180,12586,7115]
getrid_总执行时间50=[23357,22462,21621,21879,16525,14582]
getid_总执行时间50=[25382,20414,21510,20848,16880,14777]
plt.plot(post_线程数_循环数,post_总执行时间50,color='orange',label='50_post')
#plt.plot(post_线程数_循环数,getrid_总执行时间50,color='red',label='50_get_随机选择id')
#plt.plot(post_线程数_循环数,getid_总执行时间50,color='red',label='50_get_顺序选择id')





post_总执行时间30=[24841,22717,25655,20567,14409,7772]
getrid_总执行时间30=[18293,18792,18640,18193,16442,14880]
getid_总执行时间30=[18410,18065,18666,18913,16912,14383]

plt.plot(post_线程数_循环数,post_总执行时间30,color='darkgreen',label='30_post')
#plt.plot(post_线程数_循环数,getrid_总执行时间30,color='darkgreen',label='30_get_随机选择id')
#plt.plot(post_线程数_循环数,getid_总执行时间30,color='darkblue',label='30_get_顺序选择id')

plt.xlabel('线程数')
plt.ylabel('总执行时间')
plt.title('不同druid初始化物理连接个数读写效率对比图')
plt.legend()
plt.show()
