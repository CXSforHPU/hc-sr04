
from building import *

cwd     = GetCurrentDir()
src     = []
path    = [cwd]

src += ["sensor_hc_sr04.c"]
if GetDepend("PKG_USING_SR04_SAMPLE"):
    src += ["sr04_sample.c"]

group = DefineGroup('sr04', src, depend = ['PKG_USING_SR04'], CPPPATH = path)

Return('group')
