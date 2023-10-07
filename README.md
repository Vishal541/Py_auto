# Python Code using PyAutoGUI

```python
import pyautogui as pg
import time

res = pg.locateOnScreen("subs.png")
temp = pg.locateCenterOnScreen("subs.png")
prem = pg.locateCenterOnScreen("prem.png")
untemp = pg.locateCenterOnScreen("unsubs.png")
untemp1 = pg.locateCenterOnScreen("unsubs1.png")

print(temp)

time.sleep(2)

pg.click(temp)

time.sleep(2)
pg.click(untemp)
time.sleep(2)
pg.click(untemp1)
